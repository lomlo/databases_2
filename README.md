# Databases 2

An exercise to learn three things:

1. Explain how to use CRC cards to model a domain
2. Model a simple domain using CRC cards
3. Infer database structure from domain structure

## Instructions

Following are some user stories.

1. Using [CRC cards](http://agilemodeling.com/artifacts/crcModel.htm), model the domain in an Object-Oriented way. (20 minutes)
2. Draw out the structure of the database for the model you have built, in the following way (the example is a possible implementation of a `cohorts` table:

```
Table: cohorts

|  id  |     name     |
|---------------------|
|  1   |  "May 2016"  |
```

> This exercise will involve the use of foreign keys and associations. There may be one or more 'join' tables involved too, to implement many-to-many relationships.

### Resources

- [ELI5: Relational Databases](https://www.reddit.com/r/explainlikeimfive/comments/3qqm9h/eli5_relational_databases/)
- [ActiveRecord guide: Database Associations](http://guides.rubyonrails.org/association_basics.html#the-types-of-associations) (with diagrams!)

## User Stories

```
As a coach
So I can get to know all students
I want to list students' names
```

```
As a coach
So I don't get overwhelmed with a massive list of everyone
I want to view a list of students' names filtered by cohort name
```

```
As a coach
So I can learn students' names
I want to view all the URLs for images of students' faces
```

```
As a coach
So I can mark certain students
I want to add named tags to students
```

```
As a coach
So I can see students with the same tag
I want to filter students in the list by tag name
```

```
As a student
So I can exemplify an XP value
I want to give feedback daily
```

```
As a coach
So I can get an overview of feedback
I want to see an average daily rating for each student
```