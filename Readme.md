# DataTables CSV exporter

CSV exporter is a plug-in for the DataTables, which adds a button for downloading visible data from table in csv format. 
CSV exporter export data as is - WYSIWYG (What You See Is What You Get), it means for example if you filtered a table and hide some columns,
you will get exactly the same data in resulted CSV file. Key features include:

* Client Side
* Does not require Flash (.swf)
* Works well with filtering, columns visibility (ColVis)
* Supports DataTables version 1.9 as well as 1.10

# Basic Usage

CSV exporter is initialised using the `V` option that it adds to DataTables' `dom` option. For example:
```js
// Datatables v. >= 1.10
$(document).ready(function () {
    $('#example').DataTable({
        dom: 'Vlfrtip'
    });
});
```

```js
// Datatables v. < 1.10
$(document).ready(function () {
    $('#example').dataTable({
        sDom: 'Vlfrtip'
    });
});
```
