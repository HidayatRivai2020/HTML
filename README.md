# HTML
- HTML stands for Hyper Text Markup Language
- HTML is the standard markup language for creating Web pages
- HTML describes the structure of a Web page
- HTML consists of a series of elements
- HTML elements tell the browser how to display the content
- HTML is not case sensitive

## [Basic HTML Tag](https://github.com/HidayatRivai2020/HTML/blob/main/index.html)
- `<!DOCTYPE html>`: defines that this document is an HTML5 document
- `<html>`: the root element of an HTML page
- `<head>`: contains meta information about the HTML page
- `<title>`: specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
- `<body>`: document's body, and is a container for all the visible contents
- `<h1>`: large heading
- `<p>`: paragraph
- `<hr>`: horizontal line
- `<pre>`: pre-defined text, display text as it written in html code
- `<!--   -->`: comment that will not be displayed at browser

## [HTML](https://github.com/HidayatRivai2020/HTML/blob/main/index.html)
- `<lang="en">`: declare the document language.
- `<style="...">`: apply css with inline style, can be used on another tags.

## [Heading](https://github.com/HidayatRivai2020/HTML/blob/main/heading.html)
- titles or subtitles that you want to display on a webpage.
- defined with the `<h1>` to `<h6>` tags
- has different size
- `<h1>` is the biggest header
- `<h6>` is the smallest header

## [Formating](https://github.com/HidayatRivai2020/HTML/blob/main/formatting.html)
- `<b>`: Bold text
- `<strong>`: Important text
- `<i>`: Italic text
- `<em>`: Emphasized text
- `<mark>`: Marked text
- `<small>`: Smaller text
- `<del>`: Deleted text
- `<ins>`: Inserted text
- `<sub>`: Subscript text
- `<sup>`: Superscript text

## [Quotation](https://github.com/HidayatRivai2020/HTML/blob/main/quotation.html)
- `<abbr>` Defines an abbreviation or acronym
    - `title`: Description of `<abbr>`
- `<address>` Defines contact information for the author/owner of a document
- `<bdo>` Defines the text direction
- `<blockquote>` Defines a section that is quoted from another source
- `<cite>` Defines the title of a work
- `<q>` Defines a short inline quotation

## [Style CSS](https://github.com/HidayatRivai2020/HTML/blob/main/style.html)
- Cascading Style Sheets
- used to format the layout of webpage
- can be used on html in 3 ways:
    - inline: inside HTML elements
    - `<style>`: in the `<head>` section
    - `<link>`: using external CSS file
- `<link>` can be used for favicon

## [Division](https://github.com/HidayatRivai2020/HTML/blob/main/division.html)
- `<div>`: block display values
- `<span>`: inline displate value

## [List](https://github.com/HidayatRivai2020/HTML/blob/main/list.html)
- `<ol>`: ordered-list
- `<ul>`: unordered list
- `<li>`: list item
- nested list is a list inside of list
- `<dl>`: description list
- `<dt>`: terms of `<dl>`
- `<dd>`: description of `<dt>` 

## [Image](https://github.com/HidayatRivai2020/HTML/blob/main/image.html)
- `<img>`: embed an image in a web page
    - `src`: specificies the path to the image
    - `alt`: specificies an alternate text for the image
    - `usemap`: use map so image can be clicked
    - `height`: height of image
    - `width`: width of image
- `<map>`: image map with clickable areas
- `<area>`: area of image that can be clicked
    - `coords`: the coordinate
    - `shape`: shape of area
    - `alt`: alternative text
    - `href`: destination after click
- `<picture>`: multiple image resource


## [Links](https://github.com/HidayatRivai2020/HTML/blob/main/image.html)
- `<a>`: anchor tag, used as hyperlinks
    - `href`: url of destination link
    - `target`: specifies where to open the linked document
- jump into another document when clicked
- the cursor will turn into a little hand when mouse over
- `target` values:
    - `_self`: default. open the document in the same window/tab
    - `_blank`: open the document in a new window/tab
    - `_parent`: open the document in parent frame
    - `_top`: open the document in the full body of window

## [Table](https://github.com/HidayatRivai2020/HTML/blob/main/table.html)
- `<table>`: Defines a table
    - `border`: Specifies the size of border
- `<th>`: Defines a header cell in a table
- `<tr>`: Defines a row in a table
- `<td>`: Defines a cell in a table
    - `colspan`: create a cell span over multiple columns
    - `rowspan`: create a cell span over multiple rows
- `<caption>`: Defines a table caption
- `<colgroup>`: Specifies a group of one or more columns in a table for formatting
- `<col>`: Specifies column properties for each column within a `<colgroup>` element
    - `span`: Specifies how many columns affected by col
- `<thead>`: Groups the header content in a table
- `<tbody>`: Groups the body content in a table
- `<tfoot>`: Groups the footer content in a tables

## [Form](https://github.com/HidayatRivai2020/HTML/blob/main/form.html)
- `<form>`: element to collect user input
- user input most often sent to a server for processing

### [Form Attribute](https://github.com/HidayatRivai2020/HTML/blob/main/form.html)
- `accept-charset`: Specifies the character encodings used for form submission
- `action`: Specifies where to send the form-data when a form is submitted
- `autocomplete` Specifies whether a form should have autocomplete on or off
- `enctype` Specifies how the form-data should be encoded when submitting it to the server (only for method="post")
- `method` Specifies the HTTP method to use when sending form-data
- `name` Specifies the name of the form
- `novalidate` Specifies that the form should not be validated when submitted
- `rel` Specifies the relationship between a linked resource and the current document
- `target` Specifies where to display the response that is received after submitting the form

### [Form target values](https://github.com/HidayatRivai2020/HTML/blob/main/form.html)
`_blank`: The response is displayed in a new window or tab
`_self`: The response is displayed in the current window
`_parent`: The response is displayed in the parent frame
`_top`: The response is displayed in the full body of the window
`framename` The response is displayed in a named iframe

### [Form method values](https://github.com/HidayatRivai2020/HTML/blob/main/form.html)
- GET:
    - Appends the form data to the URL, in name/value pairs
    - The length of a URL is limited (2048 characters)
    - Useful for form submissions where a user wants to bookmark the result
- POST:
    - Appends the form data inside the body of the HTTP request
    - the submitted form data is not shown in the URL
    - has no size limitations- 
    - Form submissions with POST cannot be bookmarked

### [Form method values](https://github.com/HidayatRivai2020/HTML/blob/main/form.html)
- `Text` (default): single-line random character.
- `Password`: password
- `Submit`: button to submit form-data
- `Reset`: button to set everything into default value
- `Radio`: limited choice that let user select one value
- `Checkbox`: limited choice that let user select multiple value
- `Button`: button
- `Color`: color-picker
- `Date`: date-picker
- `Datetime-local`: date-picker with no time zone
- `Email`: email restriction input
- `Image`: defines image as submit button
- `File`: file-select field and a "Browse" button for file uploads
- `Hidden`: hidden input that will not visible to user
- `Month`: date-picker for a month and year
- `Number`: alphanumeric input
- `Range`: slider input where exact value is not important
- `Search`: searching input
- `Tel`: telephone input
- `Time`: time picker with no time-zone
- `url`: URL address
- `week`: date-picker with week and year


### [Form method attribute](https://github.com/HidayatRivai2020/HTML/blob/main/form.html)
- `value`: input value
- `readonly`: value can not be updated
- `disabled`: non-active input
- `size`: input size with default value 20
- `maxlength`: maximum length of input
- `min`: minimum value
- `max`: maximum value
- `multiple`: set input so user can select multiple value
- `pattern`: regular expression
- `placeholder`: hint
- `required`: input must be set
- `step`: number with interval value
- `autofocus`: auto focus when webpage is open
- `height`: height
- `width`: width
- `list`: use datalist as input
- `autocomplete`: can use old value if autocomplete is on
