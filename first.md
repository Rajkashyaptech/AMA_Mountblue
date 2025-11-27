# AMA

## **SQL Normalization**
- **Definition:** Process to organize tables to reduce redundancy and improve integrity.
- **Why:** Avoid update/insert/delete anomalies and save space.

## **Block-level Elements (HTML)**
- **Definition:** Elements that start on a new line and take full available width.
- **Examples:** `div`, `p`, `h1`-`h6`, `ul`, `ol`, `li`, `form`.

## **Include CSS in HTML**
- **Inline:** element-level `style` attribute: `<p style="color:blue">Text</p>`.
- **Internal:** inside `<head>` with `<style>`:
	- `<style> .btn{color:red;} </style>`
- **External:** separate file with `<link rel="stylesheet" href="styles.css">`.

## **Difference: `<b>` vs `<strong>`**
- **`<b>`:** purely visual bolding (no semantic meaning).
- **`<strong>`:** semantic importance; default renders bold and is meaningful to assistive tech.

## **Traverse a Dictionary (Python)**
- **By keys:** `for k in my_dict:`
- **By values:** `for v in my_dict.values():`
- **By items (key, value):** `for k, v in my_dict.items():`
- **Example:**
	- `d = {'a':1, 'b':2}`
	- `for k,v in d.items(): print(k, v)`

## **When and Why Use Typecasting**
- **Definition:** Convert value from one type to another (e.g., string → int).
- **When:** needed for arithmetic, API inputs, or when interfacing between systems.
- **Example (Python):** `int('42') + 1  # -> 43`

## **What is `__name__` in Python**
- **Definition:** Special variable that holds module name; `'__main__'` when run directly.
- **Typical use:** `if __name__ == '__main__':` to run test/demo code only when executed, not on import.
- **Example:**
	- `def main(): print('run')`
	- `if __name__ == '__main__': main()`

## **Virtual Environment (Python)**
- **Definition:** Isolated environment for Python packages per-project.
- **Why:** Prevent dependency/version conflicts between projects.
- **Quick commands:**
	- `python -m venv env`
	- `source env/bin/activate` (Linux/macOS)
	- `deactivate` to exit

## **Apply a Class to Element (HTML)**
- **How:** Add `class` attribute: `<div class="card">...</div>`
- **CSS:** target with `.card { padding: 1rem; }`

## **CSS Reset**
- **Definition:** Small stylesheet to remove browser default margins/padding and normalize styles.
- **Why:** Ensure consistent appearance across browsers.
- **Tiny example:** `* { box-sizing: border-box; margin: 0; padding: 0; }`

## **Use of META Tag (HTML)**
- **Purpose:** Provide metadata to browser/search engines.
- **Common examples:**
	- `<meta charset="utf-8">`
	- `<meta name="viewport" content="width=device-width, initial-scale=1">`
	- `<meta name="description" content="Short description">`

## **"media" in CSS**
- **Definition:** Targets stylesheets or rules to specific media types/conditions.
- **Use cases:** responsive design and print styling.
- **Examples:**
	- Link attribute: `<link rel="stylesheet" href="print.css" media="print">`
	- Media query: `@media (max-width:600px) { body{font-size:14px} }`
