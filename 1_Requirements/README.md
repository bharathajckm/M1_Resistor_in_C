# Requirements

## Introduction

This application allows you to write out the equivalent resistor value in Ohms.

## Research
### Objective
The goal of this project is to find the value of resistor in the given colour code.

### Benefits
Helps to know which resistor value for given colour code.

## Cost and Features
The cost for implementing a project invloving resistor color calculator is minimal none. And the features are:
1. reistor value for given color code 
2. Show the color value also
3. Show reistor value in ohm

### Defining Our System
Assume that you are given the color codes of a resistor as a series of four characters, where each character represents a number and 
a place, with the last color representing the multiplier. Your task is to read in these four characters (i.e., colors) and write out the
equivalent resistor value in Ohms. The first three bands are digits and the fourth band is the multiplier. Write a function that takes a
character argument representing a color and returns an integer representing the band value or the multiplier. Call this function four
times to compute the numeric value of your resistor.

The table given is as follows:

Character Color Band Value Multiplier

B Black 0 1

N Brown 1 10

R Red 2 100

O Orange 3 1K

Y Yellow 4 10K

G Green 5 100K

L Blue 6 1M

V Violet 7 10M

E Gray 8

W White 9

## 4W's and 1'H
### Who:
* Students who want to know the value of reistor for given color code
* Electrical engineers

### What:
* To find the value of resistor.

### When:
* Students who want to know the resistor value, can use this program.
* Come to a great use when finding answers.

### Where:
* Students, electrical and electronics engineers all over the world.

### How:
* This program can be executed in a system which has Linux or Windows operating system.

## High Level Requirements
| ID   | Description                                | Category  | Status      |
| -----|:------------------------------------------:|:---------:|:-----------:|
| HR01 | User can be able to know resistor value    | Technical | IMPLEMENTED |



## Low Level Requirements
| ID    | Description                                                             | HLR ID | Status (Implemented/Future) |
| ------|:-----------------------------------------------------------------------:| ------:|----------------------------:|
| LR01  | User must choose the color code                                         | HR01   | IMPLEMENTED |
