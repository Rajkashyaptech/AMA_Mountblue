# AMA

## Recursion in Python
- A function that calls itself to solve smaller parts of a problem.
- Needs a base case to stop and a recursive case that reduces the problem.

## Lambda Function in Python
- An anonymous, one-line function: `lambda args: expression`.
- Useful for short inline functions (e.g., in `map`, `filter`, `sorted`).

## Concatenate Two Lists in Python
- New list: `c = a + b`.
- In-place extend: `a.extend(b)` (modifies `a`).
- Unpack: `c = [*a, *b]`.

## Use of `IF EXISTS` in SQL
- Avoids errors when dropping or altering objects that might not exist.
- Example: `DROP TABLE IF EXISTS users;`.

## ACID Properties in SQL
- Atomicity: All parts of a transaction succeed or none do.
- Consistency: Database stays valid before and after a transaction.
- Isolation: Concurrent transactions don’t interfere with each other.
- Durability: Committed changes persist after crashes.

## Python Generators and Memory Efficiency
- Generators produce values lazily using `yield` (one at a time).
- They don’t store the whole sequence, so they use very little RAM for large data.

## Foreign Key Constraint
- A column (or columns) referencing a primary key in another table.
- Ensures referential integrity and prevents orphaned child rows.

## Composite Key in SQL
- A primary key composed of two or more columns together.
- Uniquely identifies a row by that column combination.

## Why Use Indexing in SQL
- Speeds up searches and SELECT queries.
- Trade-offs: extra storage and slower INSERT/UPDATE/DELETE.

## How CSS Specificity Works
- Priority order: inline styles > IDs > classes/attributes/pseudo-classes > elements/pseudo-elements.
- Higher specificity wins; if tied, the later rule in the stylesheet wins.

## How the Browser Renders HTML and CSS
- Parse HTML → build the DOM.
- Parse CSS → build the CSSOM.
- Combine into the Render Tree, then Layout (compute sizes/positions), Paint (draw), and Composite (merge layers).

## The GIL in Python
- GIL = Global Interpreter Lock (in CPython).
- Only one native thread executes Python bytecode at a time, which limits CPU-bound parallelism.
- Use threading for I/O-bound tasks and multiprocessing for CPU-bound work.
