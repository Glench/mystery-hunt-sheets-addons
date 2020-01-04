# mystery-hunt-sheets-addons
A set of useful Google Sheets functions for Mystery Hunt.

Click on Code.gs above and use GitHub's raw file feature to make it easy to copy and
paste all of the code.

Got to your Google sheet, select the Tools menu and then select Script Editor.

Copy and paste all of the code in there, eliminating the example function they
started you with. Press save button.

Now formulas like `=caesarShift(F2,I2)` should work in your spreadsheet.

## Useful functions included in this script


### `normalizeString(text)`

Converts a string to capital letters without whitespace or punctuation, and uppercases.
e.g. `normalizeString("Hello, World!")` => `"HELLOWORLD"`


### `wikiLookup(text, key)`

Looks up `key` in wikipedia infobox e.g. `wikiLookup("George Washington", "born")` => `1732`


### `nth(text, number*)`

Returns the nth character of the text e.g. `nth("abcd", 2)` => `"b"`. Also works with multiple numbers e.g. `nth("abcd", 2, 4)` => `"ad"`.

### `countChar(text, char)`

Returns the number of times a given character appears in a given string.
e.g. `countChar("abaab", "a")` => `3`

Look in [the source](https://github.com/mmachenry/mystery-hunt-sheets-addons/blob/master/Main.gs) for more useful functions.
