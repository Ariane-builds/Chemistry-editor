# Chem Editor

Chem Editor is a simple browser-based editor for writing chemistry notes and equations. It supports basic rich-text formatting and automatic equation processing.

---

## Features

* Bold and italic text
* Automatic formatting of equations written inside quotation marks
* Open and save `.txt` and `.html` files
* Save notifications and smooth UI effects

---

## How It Works

* Type normally in the editor
* Write an equation inside quotes:

```
"H2 + O2"
```

* The editor detects the quoted text
* The equation is formatted automatically
* Text and formatting outside the quotes remain unchanged

---

## Technologies

* HTML
* CSS
* JavaScript
* File System Access API
* Selection and Range API

---

## File Support

* `.txt`
* `.html`

Note: File access works only on HTTPS or localhost.

---

## Notes

* Uses a `contenteditable` element instead of a textarea
* Allows real bold and italic formatting
* Formatting is stored as HTML

---

## Browser Support

* Chrome: Full support
* Edge: Full support
* Safari: Partial support
* Firefox: Limited support

---

## Purpose

Chem Editor was built to make writing chemistry notes easier and faster, especially when working with chemical equations.

---

## Author

Ariane Hirwa
