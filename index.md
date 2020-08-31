
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

<table data-table data-tablelook="1696">
<tbody>
<tr>
<td data-celllook="65536">
<p>T&iacute;nh&nbsp;năng&nbsp;website&nbsp;</p>
</td>
<td data-celllook="65536">
<p>G&oacute;i&nbsp;phổ&nbsp;th&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="65536">
<p>G&oacute;i&nbsp;chuy&ecirc;n&nbsp;nghiệp&nbsp;1&nbsp;</p>
</td>
<td data-celllook="65536">
<p>G&oacute;i&nbsp;chuy&ecirc;n&nbsp;nghiệp&nbsp;2&nbsp;</p>
</td>
<td data-celllook="65536">
<p>G&oacute;i&nbsp;cao&nbsp;cấp&nbsp;1&nbsp;</p>
</td>
<td data-celllook="65536">
<p>G&oacute;i&nbsp;cao&nbsp;cấp&nbsp;2&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang&nbsp;chủ&nbsp;website&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang&nbsp;giới&nbsp;thiệu&nbsp;doanh&nbsp;nghiệp&nbsp;dạng&nbsp;tin&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang&nbsp;giới&nbsp;thiệu&nbsp;doanh&nbsp;nghiệp&nbsp;dạng&nbsp;landing page&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang&nbsp;sản&nbsp;phẩm&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang&nbsp;dịch&nbsp;vụ&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang tin&nbsp;tức&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang&nbsp;h&igrave;nh&nbsp;ảnh&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>&nbsp;C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang video&nbsp;hoạt&nbsp;động&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang&nbsp;li&ecirc;n&nbsp;hệ&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Trang&nbsp;kh&aacute;ch&nbsp;h&agrave;ng&nbsp;-&nbsp;dự&nbsp;&aacute;n&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>T&iacute;nh&nbsp;năng&nbsp;tư&nbsp;vấn,&nbsp;hỗ&nbsp;trợ&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Website&nbsp;c&oacute;&nbsp;phi&ecirc;n&nbsp;bản&nbsp;cho&nbsp;m&aacute;y&nbsp;t&iacute;nh,&nbsp;m&aacute;y&nbsp;t&iacute;nh&nbsp;bảng,&nbsp;điện&nbsp;thoại&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Thiết&nbsp;kế&nbsp;3&nbsp;ảnh&nbsp;slide&nbsp;cho&nbsp;website&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Hỗ&nbsp;trợ&nbsp;c&agrave;i&nbsp;đặt&nbsp;c&ocirc;ng&nbsp;cụ&nbsp;chat online&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>M&aacute;y&nbsp;chủ&nbsp;20GB&nbsp;SDD&nbsp;băng&nbsp;th&ocirc;ng&nbsp;kh&ocirc;ng&nbsp;giới&nbsp;hạn&nbsp;(miễn&nbsp;ph&iacute;&nbsp;1&nbsp;năm)&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>T&ecirc;n&nbsp;miền&nbsp;(miễn&nbsp;ph&iacute;&nbsp;1&nbsp;năm)&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Email&nbsp;doanh&nbsp;nghiệp&nbsp;theo&nbsp;t&ecirc;n&nbsp;miền&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Giao&nbsp;diện&nbsp;website&nbsp;</p>
</td>
<td data-celllook="0">
<p>Đẹp,&nbsp;chuy&ecirc;n&nbsp;nghiệp,&nbsp;tương&nbsp;th&iacute;ch&nbsp;mọi&nbsp;thiết&nbsp;bị&nbsp;</p>
</td>
<td data-celllook="0">
<p>Đẹp,&nbsp;chuy&ecirc;n&nbsp;nghiệp,&nbsp;tương&nbsp;th&iacute;ch&nbsp;mọi&nbsp;thiết&nbsp;bị&nbsp;</p>
</td>
<td data-celllook="0">
<p>Đẹp,&nbsp;chuy&ecirc;n&nbsp;nghiệp,&nbsp;tương&nbsp;th&iacute;ch&nbsp;mọi&nbsp;thiết&nbsp;bị&nbsp;</p>
</td>
<td data-celllook="0">
<p>Đẹp,&nbsp;chuy&ecirc;n&nbsp;nghiệp,&nbsp;tương&nbsp;th&iacute;ch&nbsp;mọi&nbsp;thiết&nbsp;bị&nbsp;</p>
</td>
<td data-celllook="0">
<p>Đẹp,&nbsp;chuy&ecirc;n&nbsp;nghiệp,&nbsp;tương&nbsp;th&iacute;ch&nbsp;mọi&nbsp;thiết&nbsp;bị&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Cho&nbsp;ph&eacute;p&nbsp;thay&nbsp;đổi&nbsp;m&agrave;u&nbsp;sắc&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Cho&nbsp;ph&eacute;p&nbsp;thay&nbsp;đổi&nbsp;bố&nbsp;cục&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Nhận&nbsp;được&nbsp;c&aacute;c&nbsp;bản&nbsp;cập&nbsp;nhật&nbsp;module&nbsp;v&agrave;&nbsp;hệ&nbsp;thống&nbsp;miễn&nbsp;ph&iacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Li&ecirc;n&nbsp;tục&nbsp;nhận&nbsp;được&nbsp;c&aacute;c&nbsp;tối&nbsp;ưu&nbsp;th&ecirc;m&nbsp;về&nbsp;SEO&nbsp;cho&nbsp;website&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Hỗ&nbsp;trợ,&nbsp;hướng&nbsp;dẫn&nbsp;online&nbsp;l&acirc;u&nbsp;d&agrave;i&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Được&nbsp;sử&nbsp;dụng&nbsp;tất&nbsp;cả&nbsp;c&aacute;c&nbsp;module&nbsp;c&oacute;&nbsp;tr&ecirc;n&nbsp;hệ&nbsp;thống&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>Kh&ocirc;ng&nbsp;</p>
</td>
<td data-celllook="0">
<p>C&oacute;&nbsp;</p>
</td>
</tr>
<tr>
<td data-celllook="0">
<p>Chi&nbsp;ph&iacute;&nbsp;trọn&nbsp;g&oacute;i&nbsp;</p>
</td>
<td data-celllook="0">
<p>12.000.000&nbsp;</p>
</td>
<td data-celllook="0">
<p>15.000.000 VNĐ&nbsp;</p>
</td>
<td data-celllook="0">
<p>18.000.000 VNĐ&nbsp;</p>
</td>
<td data-celllook="0">
<p>22.000.000 VNĐ&nbsp;</p>
</td>
<td data-celllook="0">
<p>30.000.000 VNĐ&nbsp;</p>
</td>
</tr>
</tbody>
</table>
