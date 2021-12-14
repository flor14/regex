# Regular Expresions

> A **regular expression**, often abbreviated to **regex**, is a method of using a sequence of characters to define a search to match strings. 

* Regular expressions are used in:
    -  **search engines**,
    -  **search and replace** dialogs of word processors and text editors,
    -  in **text processing** utilities and in lexical analysis. 

* Many programming languages provide regex capabilities either built-in or via libraries, as it has uses in many situations

In _data science_, regular expressions are particularly useful for defining **filters**.

## Anchors ⚓
---
### Start of string

`^` (caret) 

Shortcut: <kbd>Alt</kbd> 94

Matches at the start of the string the regex pattern is applied to.

For example `^A` finds all the strings starting with A

---
### End of string

`$` (dollar sign)

Shortcut: <kbd>Alt</kbd> 36

Matches at the end of the string the regex pattern is applied to.

For example `A$` finds all the strings ending with A

---

> EXTRA 
> the dot (.) is a special character used to match any one character

---

### Exercise
How many sentences starting with and ending with `s` are in `sentences.csv`
1. Open `sentences.csv`
2. Press <kbd>Ctrl</kbd> + <kbd>F</kbd> and use the search tab with <kbd>.*</kbd> and <kbd>aA</kbd> activated








