# 資財三乙 107AB0723 徐薇妮 期末
 case "title":
?>
<p class="cent">新增標題區圖片</p>
<hr>
<form action="api.php?do=addData" method="post" enctype="multipart/form-data">
<table style="width:65%;margin:auto">
  <tr>
    <td>標題區圖片：</td>
    <td><input type="file" name="file"></td>
  </tr>
  <tr>
    <td>標題區替代文字：</td>
    <td><input type="text" name="text" value=""></td>
  </tr>
  <tr>
    <td class="cent" colspan="2">
    <input type="hidden" name="table" value="title">
      <input type="submit" value="新增">
      <input type="reset" value="重置">
    </td>
  </tr>
</table>
</form>
<?
  break;
