&nbsp;

# Excel to JSON to HTML

Get elements from excel/CSV file, convert them to JSON object and wrap everything in HTML tags.

## Usage

1. **For JSON object** In our excel/csv test file
  * the top/first row is for Object.keys *(LW,TW,Title,Artist,Link,...useAnyKeyName)*
  * every row below is Object.key.value
  Drop your file in the dropzone, and manually open parsed **JSON object** from accordion.

2. **For JSON and instant HTML** In our function fn_json2html()
  * we .map() through each excel/csv row, where we apply our HTML template for each row
  * modify HTML template in the code and use your ${Object.key} to wrap everything as you need.


[Original Spreadsheet Data Toolkit](https://github.com/SheetJS/sheetjs)

&nbsp;
