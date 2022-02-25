//use console.log(mathfloor)Math.ceil for smallest integer input
<FORM>
Fahrenheit:<INPUT TYPE="text" NAME="F" VALUE="" SIZE="6" MAXLENGTH="6" onChange="eval('C.value = ' + this.form.C_expr.value);eval('K.value = ' + this.form.K_expr.value)">
              <INPUT TYPE="hidden" NAME="F_expr" VALUE="(Math.round(((212-32)/100 * C.value + 32)*100))/100;">
<INPUT TYPE="hidden" NAME="F_expr2" VALUE="(Math.round(((212-32)/100 *(K.value - 273) + 32)*100))/100; ">
 Celsius:<INPUT TYPE="text" NAME="C" VALUE="" SIZE="6" MAXLENGTH="6" onChange="eval('F.value = ' + this.form.F_expr.value);eval('K.value = ' + this.form.K_expr.value)">
              <INPUT TYPE="hidden" NAME="C_expr" VALUE="(Math.round((100/(212-32) * (F.value - 32))*100))/100"> <INPUT TYPE="hidden" NAME="C_expr2" VALUE="(Math.round(K.value - 273))">&nbsp;
Kelvin:<INPUT TYPE="text" NAME="K" VALUE="" SIZE="6" MAXLENGTH="6" onChange="eval('F.value = ' + this.form.F_expr2.value);eval('C.value = ' + this.form.C_expr2.value)">
              <INPUT TYPE="hidden" NAME="K_expr" VALUE="(Math.round((100/(212-32) * (F.value - 32))*100))/100 + 273">&nbsp;
  
<INPUT TYPE="button" NAME="Reset" VALUE="Submit">
<INPUT TYPE="Reset" NAME="Reset" VALUE="Reset">
</FORM>
