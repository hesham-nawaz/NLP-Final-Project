<img src="https://venturebeat.com/wp-content/uploads/2018/09/natural-language-processing-e1572968977211.jpg" alt="Logo of the project" align="right">

# NLP-Final-Project; [![Build Status](https://img.shields.io/travis/npm/npm/latest.svg?style=flat-square)](https://travis-ci.org/npm/npm) [![npm](https://img.shields.io/npm/v/npm.svg?style=flat-square)](https://www.npmjs.com/package/npm) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/your/your-project/blob/master/LICENSE)
> Final project for 6.8610 (Quantitative Methods for Natural Language Processing)

There have been numerous advancements in the field of natural language processing (NLP) in
recent years that attempt to solve the task of summarization. However, these have generally
focused on summarization for a singular document. While important in its own right, single
document summarization is insufficient when there are thousands of related documents that need
to be aggregated and summarized. Given the ever-growing volume of information in the modern
age, this is an increasingly relevant challenge. Consider the case when we want to summarize
opinions from several different editorials regarding a current event. Or the case when there are
thousands of different reviews for a product that we want to summarize. This is the problem of
multi-document summarization.

This project will work with a dataset of movie reviews. Websites like Rotten Tomatoes have
users that post thousands of reviews on a daily basis. Users looking for movie recommendations
will usually not want to read through all of these. To address this, Rotten Tomatoes has paid
editors that read through, and then write a short summary of these reviews. In our project, we
intend to build and test models that can automate the process of summarizing these reviews. We
also hope that in addition to helping solve the task at hand, insights from our model(s) can be
applied to other similar problems in the realm of multi-document summarization.

## Installing / Getting started

Go to a folder and run the following to clone this repository and move into the right file directory

```shell
git clone https://github.com/hesham-nawaz/NLP-Final-Project.git
cd NLP-Final-Project
```

After cloning the repository, manually add the appropriate datasets to the folder NLP-Final-Project

### Getting the Dataset 

Download Kaggle Datasets from [HERE](https://www.kaggle.com/datasets/stefanoleone992/rotten-tomatoes-movies-and-critic-reviews-dataset). 
There are two files to place into the `NLP-Final-Project` folder: `rotten_tomatoes_critic_reviews.csv` and `rotten_tomatoes_movies.csv`

## Developing

### Built With
List main libraries, frameworks used including versions (React, Angular etc...)

### Prerequisites
What is needed to set up the dev environment. For instance, global dependencies or any other tools. include download links.


### Setting up Dev

Here's a brief intro about what a developer must do in order to start developing
the project further:

```shell
git clone https://github.com/your/your-project.git
cd your-project/
packagemanager install
```

And state what happens step-by-step. If there is any virtual environment, local server or database feeder needed, explain here.

### Building

If your project needs some additional steps for the developer to build the
project after some code changes, state them here. for example:

```shell
./configure
make
make install
```

Here again you should state what actually happens when the code above gets
executed.

### Deploying / Publishing
give instructions on how to build and release a new version
In case there's some step you have to take that publishes this project to a
server, this is the right time to state it.

```shell
packagemanager deploy your-project -s server.com -u username -p password
```

And again you'd need to tell what the previous code actually does.

## Versioning

We can maybe use [SemVer](http://semver.org/) for versioning. For the versions available, see the [link to tags on this repository](/tags).


## Configuration

Here you should write what are all of the configurations a user can enter when using the project.

## Tests

Describe and show how to run the tests with code examples.
Explain what these tests test and why.

```shell
Give an example
```

## Style guide

Explain your code style and show how to check it.

## Api Reference

If the api is external, link to api documentation. If not describe your api including authentication methods as well as explaining all the endpoints with their required parameters.


## Database

Explaining what database (and version) has been used. Provide download links.
Documents your database design and schemas, relations etc... 

## Licensing

State what the license is and how to find the text version of the license.
