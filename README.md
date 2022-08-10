# 📐 Guidelines
My guidelines for designing, coding, and working in general.

- [Coding Guidelines](#coding-guidelines)
    - [General](#general)
    - [Coding Resources](#coding-resources)
    - [Git](#git)
    - [HTML](#html)
    - [CSS](#css)

## Coding Guidelines

### General
- All classes, functions and variables names must be in english. Avoid abbreviations.
- Use 2 spaces indentation for HTML, CSS and Javascript. 4 spaces for PHP.

### Coding Resources
- Oh, shit, git: http://ohshitgit.com/

### Git
- Use the present tense ("Add feature" not "Added feature") and the imperative mood ("Move class to..." not "Moves class to...") on commits and pull requests.
- Pull requests must be reviewed before merged.
- Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), eg: `feat: Add button to header`.

### HTML
- Keep white space to a minimum.
- Use 2 spaces for indentation
- Do not use XHTML closing syntax `<br />` - just use standard syntax `<br>` instead
- Lowercase all elements and attributes (it just looks so much neater).
- Indent main 'sections' - for example:
  ```html
    <html>
      <head>
        <meta>
      </head>
      <body>
        Content
      </body>
    </html>
  ```
- Keep `<head>` section in the following order…
    1. `<title>` element
    2. `<meta>` elements
    2. Any ***required*** scripts (e.g. [Modernizr](http://modernizr.com/) or the [HTML5 Shiv](https://github.com/aFarkas/html5shiv), scripts that must be loaded **before** page render)
    3. Style sheets
- Keep HTML structure simple and not too deeply nested.
- Use styles up top in the `<head>` and scripts at the bottom before `</body>`.
- Compress your styles and scripts.
- Use HTML5 form controls when **applicable** to trigger the right keyboard on mobile (`url`, `email`…)

### CSS
- https://github.com/airbnb/css
