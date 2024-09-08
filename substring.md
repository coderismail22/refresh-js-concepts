The substring() method:

- Extracts a part of a string based on specified start and end index positions.
- The start index is inclusive, while the end index is exclusive.
- If the end index is omitted, the substring extends to the end of the string.

```javascript
let text = "Hello world!";
let result = text.substring(1, 4);
console.log(result); // Output: "ell"
```

In this example:

1. text is initialized with the string "Hello world!".
2. substring(1, 4) extracts the characters from index 1 (inclusive) to index 4 (exclusive) of the text string.
3. The extracted substring, "ell", is assigned to the result variable and then printed to the console.
