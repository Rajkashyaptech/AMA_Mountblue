# AMA

## Diff between `undefined` and `null`
- `undefined`: a variable exists but has no value (auto). `typeof undefined` → `'undefined'`.
- `null`: explicitly set to “no value”. `typeof null` → `'object'` (historic quirk).
- `null == undefined` is true, but `null === undefined` is false.

## What is Deep Copy?
- A copy of an object and all nested objects so changes to the copy don't affect the original.
- Methods: `structuredClone(obj)` (recommended), `JSON.parse(JSON.stringify(obj))` (loses functions/Date), or libraries like `_.cloneDeep`.

## How to Select HTML Elements Using JS
- `document.getElementById('id')` — single element by id.
- `document.querySelector(selector)` — first match (CSS selector).
- `document.querySelectorAll(selector)` — all matches (NodeList).
- `getElementsByClassName`, `getElementsByTagName` — live HTMLCollections.

## What is the Use of `rsync`?
- `rsync` syncs files/directories locally or over network efficiently.
- Uses incremental transfers, preserves permissions/timestamps, great for backups and deployments (often over SSH).

## What is Hoisting in JavaScript?
- Declarations are conceptually moved to the top of their scope before execution.
- `var` and function declarations are hoisted (usable before their line). `let`/`const` are hoisted but in a temporal dead zone until initialized.

## What is a Closure?
- A function that retains access to its outer (lexical) scope even after the outer function has finished.
- Useful for data privacy, factories, and callbacks.

## What is the DOM?
- Document Object Model: a tree-like representation of HTML/XML nodes that scripts can read and modify.
- Provides APIs to traverse and manipulate the page structure, styles, and content.

## What is a Callback Function?
- A function passed as an argument to be called later (on event, completion, or asynchronously).
- Example: `arr.forEach(item => doSomething(item))` where the arrow is a callback.

## Purpose of `JSON.stringify()` and `JSON.parse()`
- `JSON.stringify(value)`: convert JS value to a JSON string (for storage or transfer).
- `JSON.parse(text)`: parse a JSON string back into JS objects.
- Note: functions and `undefined` are not preserved; Dates become strings.

## Explain `async` and `await` in JavaScript
- `async` marks a function that returns a Promise.
- `await` pauses execution inside an `async` function until a Promise resolves or rejects — makes async code read like synchronous code.

## Difference Between Primitive and Reference Types
- Primitives: `number`, `string`, `boolean`, `null`, `undefined`, `symbol`, `bigint`. They are immutable and copied by value.
- Reference types: objects, arrays, functions — variables hold references; copying the variable copies the reference, not the object.

## Higher-Order Functions in JavaScript
- Functions that take other functions as arguments or return functions.
- Examples: `map`, `filter`, `reduce`, and functions that create or wrap other functions.
