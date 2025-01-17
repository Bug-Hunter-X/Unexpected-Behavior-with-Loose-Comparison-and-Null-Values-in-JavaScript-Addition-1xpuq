# JavaScript Null Value Handling in Addition

This repository demonstrates a common JavaScript error related to loose comparison (==) and null values when performing addition.  The bug occurs when the loose comparison fails to explicitly check for null values, leading to unexpected results.

## The Bug

The provided JavaScript code attempts to add two numbers. However, it does not correctly handle cases where one or both of the inputs are null.  This can result in unintended type coercion and incorrect output.

## The Solution

The solution addresses this issue by explicitly checking for null values before performing the addition. By handling null values separately, the code ensures correct and predictable behavior.  This is a best practice to avoid subtle bugs related to type coercion.