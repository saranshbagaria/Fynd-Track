## Tables
- [tags](#tags)
  - [tr](#tr-table-row)
  - [td](#td-table-element)
  - [thead](#thead-table-heading)
  - [tfoot](#tfoot-table-footer)
  - [tbody](#tbody-table-body)
- [time table example](#time-table-example)
- [format text](#format-text)
  - [b](#1-b-bold-text)
  - [strong](#2-strong-important-text)
  - [italic](#3-i-italic-text)
  - [em](#4-em-emphasized-text)
  - [mark](#5-mark-marked-text)
  - [small](#6-small-smaller-text)
  - [del](#7-del-deleted-text)
  - [ins](#8-ins-inserted-text)
  - [sub](#9-sub-subscript-text)
  - [sup](#10-sup-super-text)
  
  
### TAGS

#### `<tr>`  Table Row
- is table row

#### `<td>` Table Element
- is table element

```html
<table>
    <tr>
        <td>  element 1 </td>
        <td>  element 2</td>
        <td>  element 3</td>
    </tr>
</html>
```

#### OUTPUT :-

<table>
    <tr >
        <td>  element 1 </td>
        <td>  element 2</td>
        <td>  element 3</td>
    </tr>
</table>


```html
<table>
    <tr><td>element 1</td></tr>
    <tr><td>element 1</td></tr>
    <tr><td>element 1</td></tr>
</table>
```

#### OUTPUT :-

<table>
    <tr><td>element 1</td></tr>
    <tr><td>element 2</td></tr>
    <tr><td>element 3</td></tr>
</table>


#### `<thead>` Table Heading

- set the content in bold format
- th is deprecated

<br><br>

#### `<tfoot>` Table Footer

- generally used is foot of the table

<br><br>

#### `<tbody>` Table Body

- we can define middle part within this tag

<br><br>

```html
<table>
    <tfoot>
        <td>Foot</td>
    </tfoot>
    <tbody>
        <tr><td>element 2</td></tr>
        <tr><td>element 3</td></tr>
    </tbody>
    <thead>
        <td> Head</td>
    </thead>
</table>
```

### OUTPUT :-

<table>
    <tfoot>
        <td>Foot</td>
    </tfoot>
    <tbody>
        <tr><td>element 1</td></tr>
        <tr><td>element 2</td></tr>
    </tbody>
    <thead>
        <td> Head</td>
    </thead>
</table>

#### \<colgroup\> Column Group

- we can change property of whole column
- here span group columns in serial manner

````html
<colgroup>
    <col span="2" style="background-color: yellow">
    <col  style="background-color: red">
</colgroup>
````

### Time Table Example


<table border="1" >
    <colgroup>
        <col style="background-color: #94ff51; font-weight: bold">
    </colgroup>
    <thead>
    <tr style="background-color: burlywood">
        <td align="center"  width = "100">
            <b>Day/Period</b>
        </td>
        <td align="center"  width = "100">
            <b>9:30-10:20</b>
        </td>
        <td align="center"  width = "100" >
            <b>10:20-11:10</b>
        </td>
        <td align="center"  width = "100" >
            <b>11:10-12:00</b>
        </td>
        <td align="center"  width = "100">
            <b>12:00-12:40</b>
        </td>
        <td align="center"  width = "100" >
            <b>12:40-1:30</b>
        </td>
        <td align="center"  width = "100" >
            <b>1:30-2:20</b>
        </td>
    </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center"  width = "100" >Monday</td>
            <td align="center"  width = "100" style="background-color: yellow">JavaScript</td>
            <td align="center"  width = "100" style="background-color: blue">Html</td>
            <td align="center"  width = "100" style="background-color: #2ab7ca">CSS</td>
            <td align="center"  width = "100" rowspan="6" style="background-color: chocolate"><h2>L<br>U<br>N<br>C<br>H</h2></td>
            <td align="center"  width = "100" colspan="2"style="background-color: #E1F8DC">Drill</td>
        </tr>
        <tr>
            <td align="center"  width = "100">Tuesday</td>
            <td align="center"  width = "100" colspan="2"style="background-color: #E1F8DC">Drill</td>
            <td align="center"  width = "100"style="background-color: #fe4a49">Angular</td>
            <td align="center"  width = "100"style="background-color: green">Node</td>
            <td align="center"  width = "100"style="background-color: blue">Html</td>
        </tr>
        <tr>
            <td align="center"  width = "100"> Wednesday</td>
            <td align="center"  width = "100" style="background-color: yellow">JavaScript</td>
            <td align="center"  width = "100" style="background-color: #fe4a49">Angular</td>
            <td align="center"  width = "100" style="background-color: #2ab7ca">CSS</td>
            <td align="center"  width = "100"style="background-color: green">Node</td>
            <td align="center"  width = "100" style="background-color: blue">Html</td>
        </tr>
        <tr>
            <td align="center"  width = "100" >Thursday</td>
            <td align="center"  width = "100" style="background-color: blue">Html</td>
            <td align="center"  width = "100" style="background-color: #fe4a49">Angular</td>
            <td align="center"  width = "100" style="background-color: #2ab7ca">CSS</td>
            <td align="center"  width = "100" style="background-color: yellow ">JavaScript</td>
            <td align="center"  width = "100"style="background-color: green">Node</td>
        </tr>
        <tr>
            <td align="center"  width = "100"> Friday</td>
            <td align="center"  width = "100" style="background-color: #fe4a49">Angular</td>
            <td align="center"  width = "100" style="background-color: blue">Html</td>
            <td align="center"  width = "100" style="background-color: yellow">JavaScript</td>
            <td align="center"  width = "100" style="background-color: #2ab7ca">CSS</td>
            <td align="center"  width = "100"style="background-color: green">Node</td>
        </tr>
        <tr>
            <td align="center"  width = "100"> Saturday</td>
            <td align="center"  width = "100" style="background-color: #fe4a49">Angular</td>
            <td align="center"  width = "100" style="background-color: yellow">JavaScript</td>
            <td align="center"  width = "100"style="background-color: green">Node</td>
            <td colspan="2" align="center"  width = "100" style="background-color: #2ab7ca">CSS</td>
        </tr>
    </tbody>
    <tfoot>
    <tr style=" background-color: #b52bc0">
        <td colspan = "7" align="center" > <a style="font-size:30px; text-autospace: ideograph-alpha">HOLLY-DAY</a></td>
    </tr>
    </tfoot>
</table>


## Format text

#### 1.  `<b>`  Bold text

```html
<b>bold text</b>
```

##### OUTPUT :-

<b>bold text</b>

#### 2. `<strong>` Important text 

```html
<strong>important text</strong>
```

#### OUTPUT :-

<a> Hello <strong> bold text</strong></a>


#### 3. `<i>`  Italic text

```html
<i>Italic text</i>
```

#### OUTPUT :-

<a> Hello <i> italic text</i></a>


#### 4. `<em>` Emphasized text

```html
<em>Emphasized text</em>
```

#### OUTPUT :-

<a> Hello<em>Emphasized text</em> </a>

#### 5. `<mark>` Marked Text

```html
<mark>Marked Text</mark>
```

#### OUTPUT :-

<a> Hello <mark>Marked Text</mark> </a>

####  6. `<small>` Smaller Text

```html
<small>Smaller Text</small>
```

#### OUTPUT :-

<a> Hello <small> Smaller Text </small> </a>

#### 7. `<del>` Deleted Text

```html
<del> Deleted Text</del>
```

#### OUTPUT :-

<a>Hello<del> Deleted Text</del></a>

#### 8. `<ins>` Inserted Text

```html
<ins> inserted text</ins>
```

#### OUTPUT :-

<a>Hello<ins> inserted text</ins></a>


#### 9. `<sub>` Subscript Text

```html
<sub>subscript text</sub>
```

#### OUTPUT :-

<a>Hello<sub>subscript text</sub></a>


#### 10. `sup` Super text


```html
<sup>Superscript text</sup>
```

##### OUTPUT :-

<a>Hello<sup>Superscript text</sup><a>
