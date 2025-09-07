# Tables

## Table structure

- `<table>` - wraps the whole table
- `<tr>` - (table row) wraps around a set of elements, defining them as belonging to the same row. Attributes: colspan, rowspan, headers
- `<th>` - (table header) defines a header for a column. Attributes: colspan, rowspan, scope
- `<td>` - (table data) marks the actual bits of data

```
<table>
    <tr>
        <th>Header1</th>
        <th>Header2</th>
        <th>Header3</th>
        <th>Header4</th>
    </tr>
    <tr>
        <td>Data1</td>
        <td>Data2</td>
        <td>Data3</td>
        <td>Data4</td>
    </tr>
    <tr>
        <td>Data1</td>
        <td>Data2</td>
        <td>Data3</td>
        <td>Data4</td>
    </tr>
    <tr>
        <td>Data1</td>
        <td>Data2</td>
        <td>Data3</td>
        <td>Data4</td>
    </tr>
</table>
```

#### Html tip :
> if you have a **button** use the ***button element***, if you have a **table** use the ***table element***
