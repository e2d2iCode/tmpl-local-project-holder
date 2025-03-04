<!-- markdownlint-disable MD041-->
Last but not least, a custom CSS must be defined to take control over the HTML code generated by the extension. Due to the fact that only the `div container` containe and the `title paragraph` are assigned a CSS class, the CSS code to use is not so trivial. Indeed:

- `Div containers` are easy to select as they are simply any `div` elements with the `admonition` class.

- `Tilte paragraph` are the `p` elements with the `admonition-title` class **that are within the above `div` container**.

- `Body paragraphs` are the `p` elements that are within the above `div` container but that **do not have the `admonition-title` class**. That last condition is not easy to implement using CSS, since there are no such selectors as "not" or "except". The easiest way to do it is to make sure that `body paragraphs` are styled **above** the `title paragraph` and that the latter override every style that is not desired. Here is an example of a working CSS code snippet that implements the above rules:

```css
.admonition.foo {
    border: 1px solid gray;
    border-radius: 0.5em;
    padding: 0.5em;
    margin: 1em 0;
    color: darkGray;
}

div.admonition.foo p {
    margin: 0;
    padding: 0;
    border: 0;
    background-color: transparent;
    color: yellow;
}
.admonition.foo .admonition-title {
    font-weight: bold;
    font-variant: small-caps;
    font-size: 90%;
    margin: 0;
    padding: 0;
    border: 0;
    background-color: transparent;
    color: red;
}
```

<!-- markdownlint-enable MD041-->
