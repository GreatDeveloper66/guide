---
title: Map State to Props
---
# Map State to Props

## Problem

This problem asks us to write a function that takes a state as a parameter and returns an object that maps that state to the messages property. This can be accomplished with a single function using arrow notation.

````javascript
const function = (param) => {
  return {property: param};
};
````

## Solution

````javascript
const mapStateToProps = (state) => {
    return {messages: state};
};
````
