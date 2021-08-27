<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128535586/16.1.4%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T532263)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Default.aspx](./CS/Default.aspx) (VB: [Default.aspx](./VB/Default.aspx))
* [Default.aspx.cs](./CS/Default.aspx.cs) (VB: [Default.aspx.vb](./VB/Default.aspx.vb))
<!-- default file list end -->
# ASPxGridView - How to show the date range header filter’s dates in filter row editors
<!-- run online -->
**[[Run Online]](https://codecentral.devexpress.com/t532263/)**
<!-- run online end -->


By default, ASPxGridView doesn't provide functionality to show start and end dates from the header date range filter in the filter row because only one date editor is displayed in this row. This example illustrates how to display these dates in custom date editors in the filter row once the header date range filter is applied and synchronize these editors' values with the date editors located in the header filter popup.<br><br>To accomplish this task, you can add two custom ASPxDateEditors in an appropriate column's FilterTemplate as demonstrated in the <a href="https://www.devexpress.com/Support/Center/p/E1990">Date Range Filtering in the Filter Row</a> example. Process the applied date range filter in the grid's CustomJSProperties event handler and pass the filter dates to the client side by using JSProperties. Then, set your custom ASPxDateEditor filter row editors in the client-side EndCallback even handler based on the passed JSProperties. You can apply the filter set by these custom filter row editors as demonstrated in the <a href="https://www.devexpress.com/Support/Center/p/E1990">Date Range Filtering in the Filter Row</a> example.

<br/>


