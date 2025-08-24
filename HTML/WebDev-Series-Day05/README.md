# 📌 Tables in HTML

Tables display data in **rows and columns**.

##🔹 Basic Table Tags
* `<table>` → Creates table.
* `<tr>` → Table row.
* `<td>` → Table data (cell).
* `<th>` → Table header (bold & centered).
* `<caption>` → Adds a title to the table.

  
🔹 Attributes

* `border` → Adds border to the table.
* `cellpadding` → Space inside each cell.
* `cellspacing` → Space between cells.
* `colspan` → Merge columns.
* `rowspan` → Merge rows.
Styling attributes (but CSS is recommended)

### 📝 Example

```html
<table border="1" cellpadding="8">
  <tr>
    <th>Name</th>
    <th>Subject</th>
    <th>Marks</th>
  </tr>
  <tr>
    <td>Ayesha</td>
    <td>Math</td>
    <td>90</td>
  </tr>
  <tr>
    <td>Ali</td>
    <td>Science</td>
    <td>85</td>
  </tr>
</table>
```

### 🎯 Output

| Name   | Subject | Marks |
| ------ | ------- | ----- |
| Ayesha | Math    | 90    |
| Ali    | Science | 85    |

