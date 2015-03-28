<HTML>
<BODY>
<FORM METHOD="POST" ACTION="DealWithArrayFormData.php">
<H1>Contact Information</H1>
<TABLE>
<TR>
  <TD>Childrens' Names:</TD>
</TR>
<TR>
  <TD><INPUT TYPE="TEXT" NAME="children[]"></TD>
</TR>
<TR>
  <TD><INPUT TYPE="TEXT" NAME="children[]"></TD>
</TR>
<TR>
  <TD><INPUT TYPE="TEXT" NAME="children[]"></TD>
</TR>
<TR>
  <TD><INPUT TYPE="TEXT" NAME="children[]"></TD>
</TR>
<TR>
  <TD><INPUT TYPE="TEXT" NAME="children[]"></TD>
</TR>
</TABLE>
<BR>
<BR>
<BR>
<INPUT TYPE="SUBMIT" VALUE="Submit">
<BR>
<BR>
<INPUT TYPE="RESET"  VALUE="Clear the Form">
</FORM>
</BODY>
</HTML>

<!-- DealWithArrayFormData.php

<?php
foreach ($children as $index => $child){
    echo "<BR>child[$index]=$child";
}
echo "<BR>";

sort($children);

foreach ($children as $index => $child){
    echo "<BR>child[$index]=$child";
}
?>
-->
           
