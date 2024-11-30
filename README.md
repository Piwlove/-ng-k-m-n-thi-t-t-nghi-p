<html lang="en">
<head> <title> Đăng kí môn thi tốt nghiệp </title> </head>
<bodY> 
<form action="Đã xác nhận" method="get">
<fieldset> <legend> Đăng kí môn thi tốt nghiệp </legend> 
<table> 
<tr> 
<td> <caption> <input type="button" id="loichao" value="Lời chào"> </caption> </td>
</tr>
<tr> 
<td> <label for="hoten"> Họ và tên: </label></td>
<td> <input type="text" id="hoten" name="hoten" placeholder="Họ và tên" required> </td>
</tr>
<tr>
<td> <label for="cccd"> CCCD:</label></td>
<td> <input type="number" id="cccd" name="cccd" placeholder="CCCD" required> </td>
</tr>
<tr>
<td> <label for="date"> Ngày sinh: </label> </td>
<td> <input type="date" id="date" name="date" required> </td>
</tr>
<tr> 
<td> <label for="gt" > Ngày sinh: </label> </td>
<td> <input type="radio" id="gt1" name="gt"> Nam </td>
<td> <input type="radio" id="gt2" name="gt"> Nữ </td>
</tr>
<tr> 
<td> <label for="thongtin"> Mô tả thêm thông tin: </label> </td>
<td> <textarea rows="5" cols="20" maxlength="300" name="thongtin" > </textarea></td>
</tr>
<tr>
<td> <label for="monthi"> Môn thi </label> </td>
<td> <input type="checkbox" id="mt1" name="monthi"> Toán <br>
<input type="checkbox" id="mt2" name="monthi"> Ngữ Văn <br>
<input type="checkbox" id="mt3" name="monthi"> Ngoại ngữ </td>
</tr>
<tr> <td>
<label for="tohop"> Tổ hợp </label> </td>
<td> <select id="th1" name="tohop"> 
<option value="Khoa học tự nhiên"> Khoa học tự nhiên </option>
<option value="Khoa học xã hội"> Khoa học xã hội </option> </td>
</tr>
<tr>
<td> <label for="syll"> Sơ yếu lí lịch </label> </td>
<td> <input type="file" id="syll" name="syll" value="Chọn tệp"> </td>
</tr>
<tr> <td> <label for="email"> Email: </label> </td>
<td> <input type="text" id="email" name="email" required> </td></tr>
<tr> <td colspan="3" align="center"> <input type="submit" value="Đăng kí"> 
</td> 
</tr>



</table>
</body>


<input list="trinhduyet">
<datalist id="trinhduyet">
<option value="Opera">
<option value="Chrome">
<option value="Safari">
<option value="Firefox">
<option value="Microsoft Edge">
</datalist> 

</html>
