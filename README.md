# Todo app' example

<!-- TOC -->

- [Todo app' example](#todo-app-example)
    - [What is this ?](#what-is-this-)
    - [Prerequisites](#prerequisites)
    - [How to run](#how-to-run)
    - [How to test](#how-to-test)
        - [Web API Testable Functionalities](#web-api-testable-functionalities)

<!-- /TOC -->

## What is this ?

A very basic CRUD of todos lists to get a hang at Flask

## Prerequisites

A standard Docker Desktop install on your dev machine.

## How to run

From root repo, run `docker compose up`.

## How to test

From root repo, run `docker exec -t todo_app_example-python-1 bash -c "python app.test.py"`

### Web API Testable Functionalities

- base URL of the api is `/api`
- a user can create lists of todos
- a user can delete lists of todos
- a user can create a todo under a given list
- a user can update a todo's completion
- a user can delete a todo
