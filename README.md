![typescript image](images/TypeScript.png)

# Beginner Level (Focus: Basic Types, Functions, and Simple Interfaces)

The exercises in this section aim to solidify understanding of fundamental TypeScript features, including primitive types, function typing, and basic object shaping.

## Exercise B1: Basic Type Declarations

> **Goal**: Declare and initialize variables using TypeScript's primitive types.

**Requirements**:

1. Declare a variable `userName` and explicitly assign the type `string`. Initialize it with a name.
2. Declare a variable `userAge` and explicitly assign the type `number`. Initialize it with an age.
3. Declare a variable `isActive` and explicitly assign the type `boolean`. Initialize it.
4. **Self-Check**: Attempt to assign a number to userName to confirm the compiler error.

## Exercise B2: Function Typing and Return Values

> **Goal**: Define a function with strictly typed parameters and an explicit return type.

**Requirements**:

1. Write a function `calculateArea` that accepts two parameters: `width` and `height`.
2. Both parameters must be explicitly typed as `number`.
3. The function must explicitly declare its return type as `number`.
4. The function body should return the product of `width` and `height`.

## Exercise B3: Type Aliases

> **Goal**: Use a `type` alias to create a custom name for a simple type.

**Requirements**:

1. Create a type alias named `ProductID` for the primitive type `string`.
2. Define a function `logProduct` that accepts one parameter `id` of type `ProductID`.
3. The function should print a message including the product ID.

## Exercise B4: Defining a Simple Interface

> **Goal**: Define and implement a simple `interface` for object structure.

**Requirements**:

1. Define an interface InventoryItem with the following properties:

   - `id`: `number`
   - `name`: `string`
   - `inStock`: `boolean`

2. Create a variable `keyboard` and assign an object that conforms exactly to the `InventoryItem` interface.

## Exercise B5: Array and Union Types

> **Goal**: Use array syntax and union types to define an array that holds multiple distinct types.

**Requirements**:

1. Declare an array named `logData`.
2. This array must be able to hold elements that are either a `string` or a `number`.
3. Initialize `logData` with at least three elements: one string, one number, and another string.
