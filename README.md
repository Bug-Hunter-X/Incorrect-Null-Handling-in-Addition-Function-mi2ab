# Incorrect Null Handling in JavaScript Function
This repository demonstrates a common error in JavaScript: incorrect handling of null values in a function. The `foo` function is designed to add two numbers, but it doesn't handle null values correctly.  The solution demonstrates how to properly handle nulls to avoid unexpected behavior. 

## Bug
The original `foo` function immediately returns `null` if either input is null.  This is incorrect; the correct approach is typically to treat `null` as 0. 

## Solution
The solution shows how to modify the `foo` function to correctly handle null values by converting them to 0 before performing addition.