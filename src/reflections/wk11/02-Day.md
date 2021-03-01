# Week 11 Day 2
__2/23/2021__

## What is the difference between a primary key and a foreign key

A primary key is a unique identifier key for a sql table. A foreign key is for referencing a primary key that is on a different table. 

## What is an Alias?

An alias is property that is created to store the values under a different name. This allows you to be able to join to parts of a table that share the same key.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE patients (
  id INT NOT NULL AUTO_INCREMENT,
  -- CODE OMITTED
  PRIMARY KEY (id)
)

CREATE TABLE doctors (
  id INT NOT NULL AUTO_INCREMENT,
  doctorId INT NOT NULL,
  patientId INT NOT NULL,

  FOREIGN KEY (doctorId)
    REFERENCES doctors(id),
  FOREIGN KEY (patientId)
    REFERENCES patients(id),
)
SELECT 
doc*,
pat* 
FROM doctors doct
JOIN patients pat ON doc.patientId = pat.id



### Daily link
https://github.com/NathanDavis97/contracts