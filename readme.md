# pure_css_navbar

- pure CSS Navigation
- pure CSS Dropdown

Adopted from [ga-wdi-exercises/cat_fancy](https://github.com/ga-wdi-exercises/cat_fancy)


```css
/* Hide all the sections that are not targeted */
section:not(:target) {
    display: none;
}

/* Then, show only the default section. */
section:nth-child(3) {
    display: block;
}

/*
Dropdown functionalities:
- When the dropdown button is hovered, show the dropdown menu items.
- When the mouse leaves, hide the dropdown.
*/

.dropdown input[type=radio] {
    display: none;
}
.dropdown:not(:hover) label {
    display: none;
}
.dropdown input[type=radio]:checked + label {
    text-decoration: underline;
}
```
