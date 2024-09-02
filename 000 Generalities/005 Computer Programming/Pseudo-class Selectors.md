
What are Pseudo-class Selectors?
- Pseudo-class Selectors selects and style a part of a HTML element.

```
li: hover {
	background: red;
}

input: focus {
	background: red;
}

input: required {
	background: red;
}

input: checked {
	margin: 50px;
}

li:nth-child(2n) {
	background: red;
}

span:first-of-type {
	background: red;
}

span:not(.green) {
	background: red;
}
```