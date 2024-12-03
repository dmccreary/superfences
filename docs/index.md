# Test of Superfences Custom

Our goal it to use uppercase letters to style the ordered list like this:

![](./img/ordered-list-upper-alpha.png){width="100px"}

This is used in ordered lists within multiple-choce question responses.

Our final result is to a superfence that adds
a <div\> with a class in markdown.

```markdown
<div class="upper-alpha">
1. Response 1
2. Response 2
3. Response 3
4. Response 4
</div>
```

Which renders this:

<div class="upper-alpha">
1. Response 1
2. Response 2
3. Response 3
4. Response 4
</div>

The HTML that is created by mkdocs is this:

```html
<div class="upper-alpha">
  <ol>
    <li>Response 1</li>
    <li>Response 2</li>
    <li>Response 3</li>
    <li>Response 4</li>
  </ol>
</div>
```
