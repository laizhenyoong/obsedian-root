
What are Attribute Selectors?
- Attribute Selectors selects HTML elements based on attribute or attribute value.

```
[data-red] {
	background: red;
}

[data-red ='123'] {
	background: red;
}

[data-red ^='12'] {
	background: red;
}

[data-red *='23'] {
	background: red;
}

[data-red *='2'] {
	background: red;
}
```