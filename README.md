# jquery-export-excel-modify-from-rainabba-table2excel-v1.0.2
This plugin modify from https://github.com/rainabba/jquery-table2excel

How to used :

1. Include library :
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="src/jquery.table2excel.js"></script>

2. Call the plugin :
$("#download_xls").on("click", function (e) {
    $("#table").tableExcelArpast({
        // exclude CSS class
        exclude: ".noExl",
        name: "Excel Document Name",
        filename: "file name after download"
    });
});

exclude: ".noExl" is exclude export, example 
<tr class="noExl">
  <th>#</th>
  <th>Column heading</th>
  <th>Column heading</th>
  <th>Column heading</th>
</tr>

filename is name file download
