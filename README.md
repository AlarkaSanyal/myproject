# Simple REST API using Golang

## Description

This is a simple API which stores the name and address of a list of people

## GET

Returns a list of people

    Example:
    URL: localhost:12345/people

## GET with id

Returns the details of a person

    Example:
    URL: localhost:12345/people/1

## POST

Adds the details of a new person

    Example:
    URL: localhost:12345/people/3
    Request body: {"firstname":"Tom","lastname":"Doe"}

## Delete

Deletes the details of a person

    Example:
    URL: localhost:12345/people/2