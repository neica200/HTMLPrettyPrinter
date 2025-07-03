# HTMLPrettyPrinter

**HTMLPrettyPrinter** is a Bash script that reads an input HTML file and outputs a properly indented and formatted version, making it easier to read and debug. It adds line breaks and indentation to ensure each HTML tag appears on a new line and is appropriately nested according to its depth in the document structure.

---

## Features

- Validates the input file.
- Adds line breaks between HTML tags.
- Indents nested tags using 4 spaces per level.
- Skips empty lines for cleaner output.
- Handles self-closing and void elements correctly (e.g., `<br>`, `<img>`, `<meta>`, etc.).

---

## Output

The formatted HTML content is saved in a new file named:  
**`<original_name>_formatted.html`**

For example, if the input file is `index.html`, the output will be `index_formatted.html`.

---

## Usage

```bash
./HTMLPrettyPrinter.sh your_file.html
