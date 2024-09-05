# LanguageHigh

A code block syntax highlighter for BDScript, ForgeScript, and aoi.js.

## How to Use

1. **Include the Highlighter:**

   Ensure the following script and stylesheet links are included at the bottom of your website, right before the closing `</body>` tag:

   ```html
   <script src="path/to/bdshighlighter.js"></script>
   <link rel="stylesheet" href="path/to/styles/style-dark.css">
   ```

2. **Add Language Tags to Code Blocks:**

   To enable syntax highlighting, specify the appropriate language tag within the `class` attribute of your `<code>` blocks, as shown below:

   ```html
   <pre><code class="lang-tag">
   // Your code here
   </code></pre>
   ```

   ### Available Language Tags:

   - `bdscript`
   - `forgescript` *(in development)*
   - `aoi` *(in development)*

3. **Available Styles:**

   Choose your preferred theme by linking one of the following stylesheets:

   - `style-dark.css`
   - `style-light.css`

## To-Do List

- Finalize colors and optimizations for BDScript.
- Add support for ForgeScript.
- Add support for aoi.js.

---

Originally made by @.koomball and Modified by me (@clyders).
