
What are Combinator Selectors?
- Combinator Selectors selects HTML elements based on specific relationship between them.

```
span, li.red {
	background: red;
}

div b {
	background: red;
}

div > .red {
	background: red;
}

li.red ~ li {
	background: red;
}

li.red + li {
	background: red;
}
```