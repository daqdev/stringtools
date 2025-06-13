# stringtools

This simple page provides tools for analyzing and formatting lists of values. Paste data into the input area and use **Analyze Data** to detect each value. The export format is now configurable with the following controls:

- **Separator Toggle** – switches between separating values with commas or new lines.
- **Single Quotes / Double Quotes / No Quotes** – choose how each value is wrapped.

Use the language toggle to switch interface languages and the clear button to reset the form.

## Building CSS

This project uses Tailwind CSS for styling. Run the following command to generate
`styles.css` from `input.css`:

```bash
npx tailwindcss -i input.css -o styles.css --minify
```

The `tailwind.config.js` file limits the build to the classes found in
`index.html` so the output CSS stays small.
