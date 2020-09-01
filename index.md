<html>
<head>
<style type="text/css">
/* important styles */

.container {
   /* Attach fixed-th-table to this container,
      in order to layout fixed-th-table
      in the same way as scolled-td-table" */
   position: relative;

   /* Truncate fixed-th-table */
   overflow: hidden;
}

.fixed-th-table-wrapper td,
.fixed-th-table-wrapper th,
.scrolled-td-table-wrapper td,
.scrolled-td-table-wrapper th {
   /* Set background to non-transparent color
      because two tables are one above another.
    */
   background: white;
}
.fixed-th-table-wrapper {
   /* Make table out of flow */
   position: absolute;
}
.fixed-th-table-wrapper th {
    /* Place fixed-th-table th-cells above 
       scrolled-td-table td-cells.
     */
    position: relative;
    z-index: 1;
}
.scrolled-td-table-wrapper td {
    /* Place scrolled-td-table td-cells
       above fixed-th-table.
     */
    position: relative;
}
.scrolled-td-table-wrapper {
   /* Make horizonal scrollbar if needed */
   overflow-x: auto;
}


/* Simulating border-collapse: collapse,
   because fixed-th-table borders
   are below ".scrolling-td-wrapper table" borders
*/

table {
    border-spacing: 0;
}
td, th {
   border-style: solid;
   border-color: black;
   border-width: 1px 1px 0 0;
}
th:first-child {
   border-left-width: 1px;
}
tr:last-child td,
tr:last-child th {
   border-bottom-width: 1px;
}

/* Unimportant styles */

.container {
    width: 250px;
}
td, th {
   padding: 5px;
}
</style>
</head>

<body>
<div class="container">

<div class="fixed-th-table-wrapper">
<!-- fixed-th-table -->
<table>
    <tr>
         <th>aaaaaaa</th>
         <td>ccccccccccc asdsad asd as</td>
         <td>ccccccccccc asdsad asd as</td>
    </tr>
    <tr>
         <th>cccccccc</th>
         <td>xxxxxxxxxxxxxxxxxxxx yyyyyyyyyyyyyy zzzzzzzzzzzzz</td>
         <td>xxxxxxxxxxxxxxxxxxxx yyyyyyyyyyyyyy zzzzzzzzzzzzz</td>
    </tr>
</table>
</div>

<div class="scrolled-td-table-wrapper">
<!-- scrolled-td-table
     - same as fixed-th-table -->
<table>
    <tr>
         <th>aaaaaaa</th>
         <td>ccccccccccc asdsad asd as</td>
         <td>ccccccccccc asdsad asd as</td>
    </tr>
    <tr>
         <th>cccccccc</th>
         <td>xxxxxxxxxxxxxxxxxxxx yyyyyyyyyyyyyy zzzzzzzzzzzzz</td>
         <td>xxxxxxxxxxxxxxxxxxxx yyyyyyyyyyyyyy zzzzzzzzzzzzz</td>
    </tr>
</table>
</div>

</div>
</body>
</html>
