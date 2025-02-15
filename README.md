# Unexpected behavior with loose equality (==) and null values
This example demonstrates a common error in JavaScript when using loose equality (==) with null or undefined values.
The function `foo` is intended to add two numbers but it fails to correctly handle null values. The loose equality operator (==) does type coercion, which leads to unexpected results when comparing numbers and null.