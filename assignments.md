# Symmetry Take Home Assignment
If you have come to this page, it means that you are participating in the Symmetry Engineering Interview Process. We are excited to have you participating. We wish you the best of luck as you pursue opportunities with our team.

The Symmetry take home assignment is an important part of our Interview process. As noted in our [Readme](README.md), candidates have the option of working on the take home assignment or to go through one of the other three options. We give candidates the ability to display their abilities in a low stress, work from home approach rather than a time-based experience in a Zoom room. Ideally, most candidates select the take home assignment. If they choose one of the other options, it won't have any impact on the outcome of their interview.

# Developer Projects
We have many different roles at Symmetry ranging from backend developer to machine learning to product designer. As such, we have different assignments for the different roles. We will change the assignment from time to time. Most assignments will stay active for 4-6 months.

Assignments should take somewhere between 2-4 hours to complete. In some rare cases, the assignment will take a few hours longer. If the assignment is taking more than a day, let us know.

## Frontend Developers
Our project for frontend developers involves building a small, single web page application (SPA) using ReactJS. Your SPA should make use of the [Pokemon API](https://pokeapi.co/) which is fully annotated [here](https://pokeapi.co/docs/v2). Essentially, we want you to build a small [Pokedex](https://pokemon.fandom.com/wiki/Pok%C3%A9dex) in which you can perform certain basic searching and rendering of the data. We are looking for clean, organized code and a crisp UI experience that would make any Product Designer proud of your skills.

We are big believers in testing and continuous integration. As such, we want you to add linting, unit tests and integration tests to a CI pipeline.  

### Project Requirements
* Built in ReactJS
* Contain both Unit and Integration Tests
* Basic linting (Bonus would be to add code coverage)
* Has some form of Continuous Integration pipeline with linting, unit and integration testing either through GitHub Actions or TravisCI
* Write an informative and descriptive README explaining what your built, why you built it, how to set it up and how to use it.

### High-Level User Stories to Cover
User Story 1: As a Pokemon fan, I would like to search a catalog of Pokemon characters (Pokedex) by their name or by some of the characters in their name in order to return one or more Pokemon and their trading card attributes.

User Story 2: As a Pokemon fan, I would like know how many (count) unique Pokemon are in the Pokedex, as well as unique Pokemon Types and Pokemon Species.

User Story 3: As a Pokemon fan, I would like to filter and narrow my search criteria based on Pokemon Type and Pokemon Species.

User Story 4: As a Pokemon fan, I would like to see pictures of the Pokemon characters with some identifying attributes (trading card information) about the creatures presented in the screen.

User Story 5: As a Pokemon fan, I would like to sort the order of the Pokemon characters based on one or more identifying attributes about the character.

## Backend Developers
Our backend project is designed to demonstrate your comfort level building a small web application interacting with a pre-existing data set (relational or non-relational). 

You need to demonstrate an understanding of ORM for persistence purposes with any data store that you choose. We also want to see some basic test automation (Unit and Integration).

We would like you to pick a minimum of one or two data sets from the list below which can be combined into a single, shareable data set in your data store. You will need to ingest the data through some means into your data store as part of your build step.

*There are tons of amazing open and free data sets to play with. Here are a few for inspiration:*

* [Data.gov](https://www.data.gov/open-gov/)
* [NYC Open Data](https://nycopendata.socrata.com/)
* [Austin, TX Data](https://data.austintexas.gov/browse)
* [AWS Open Data](https://aws.amazon.com/public-data-sets/)
* [OpenData Baltimore](https://data.baltimorecity.gov/)

We are big believers in testing and continuous integration. As such, we want you to add linting, unit tests and integration tests to a CI pipeline.  

### Project Requirements
* Available languages to program: Python or Go.
* Import data as part of the build step.
* Make use of an ORM for loaders/persisters.
* Include logging and error handling.
* Your code should be DRY, maintainable and readable.
* 100% automated: Should be simple as a clone and a few commands to run.
* Simple, yet robust API for CRUD (Create, Read, Update and Delete): Get, Post, Put and Delete.   
* Has some form of Continuous Integration pipeline with linting, unit and integration testing either through GitHub Actions or TravisCI.
* Write an informative and descriptive README explaining what your built, why you built it, how to set it up and how to use it.

### High-Level User Stories to Cover
User Story 1: As a user, I would like to return or fetch all records of my data set.

User Story 2: As a user, I would like to return or fetch some records of my data set when I provide additional identifying information about the data set.

User Story 3: As a user, I would like create a new record in the data set.

User Story 4: As a user, I would like to delete a single record in the data set.

User Story 5: As as user, I would like to update/modify a single record in the data set.

# Preparing for your Symmetry interview

## What to Expect
The interview process at Symmetry is efficient and quick. It's intended to give candidates the chance to meet most of the team in a short window of time. Our goal is to give the candidate as much exposure to the people, process and product.

The process begins with an initial conversation with our head of company operations. This gives Symmetry the chance to learn about your interest in joining our team, as well for you to set your expectations on what you are looking for in a company, career and culture. This usually takes between 30-45 minutes. Candidates are encouraged to prepare a few questions you might want to know more about the company.

You will likely have a follow-up interview with the VP of Engineering or the hiring leader to go into greater details about the opportunity. This interview will be part behavioral and part technical. This interview typically runs between 45 and 60 minutes. We recommend that you prepare a few questions about the team, process, technology and/or company.

The technical interview is scheduled after the hiring leader interview. Candidates will have the choice of the project above, present an existing solution, a hands-on technical interview or an online skills assessment (which includes a team interview after). The technical interview will involve 1-2 members of our engineering team plus yourself. It typically takes 60 to 90 minutes. Similar to above, we love when candidates bring us questions.

The final discussion involves meeting one or both of our founders. We think it's very important for all members joining Symmetry to get a chance to meet our founders to learn why they started Symmetry. It will be a standard interview format. It may last 30 to 45 minutes. Candidates are encouraged to prepare questions they would like to ask either our CEO or CTO about the company and our future.  

## How to Prepare
There's a bit of a theme in the section above. We really want candidates to learn as much as they can about our company and the space we are competing. Most importantly, we want candidates to prepare questions at all stages of interactions with our team at Symmetry. Each meeting with a Symmetry teammate is a chance to learn something that might not be known by reading our web site or watching a YouTube video of a presentation we might have given at a conference or show.
