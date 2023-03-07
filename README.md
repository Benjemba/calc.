# calc.
table width="480px" border="0" cellspacing="0" cellpadding="0" background="http://www.superskinnyme.com/blog/wp-content/themes/repro/images/bg1.jpg" align="left">
  <tbody><tr>
    <td align="left"><form>
      <table width="490" align="left" border="0" cellpadding="5" cellspacing="2" bgcolor="#F8FDFF" class="wp" background="http://www.superskinnyme.com/blog/wp-content/themes/repro/images/bg1.jpg">
        <tbody><tr>
          <td align="right" class="style4">Gender&nbsp;</td>
          <td><label for="s1">
            <input type="radio" id="s1" name="s" value="m" onclick="sex(this.form)">
            <span class="wp">            Male</span></label>
              <span class="wp">
              <label for="s2">              </label>
              </span>
              <label for="s2">
              <input type="radio" id="s2" name="s" value="f" onclick="sex(this.form)">
              <span class="wp">Female</span></label></td>
        </tr>
        <tr>
          <td align="right" class="wp"><strong>Preferred measurement&nbsp;</strong></td>
          <td><label for="d1">
            <input type="radio" id="d1" name="d" value="1">
            <span class="wp">Centimetres</span></label>
              <label for="d2">
              <input type="radio" id="d2" name="d" value="2.54">
              <span class="wp">Inches</span></label>
              <span class="wp">
              <label for="d2"></label>
              <label for="d2"> </label>
              </span>
              <label for="d2"></label></td>
        </tr>
        <tr>
          <td><div align="right" class="wp"><strong>Height&nbsp;</strong></div></td>
          <td><input type="text" id="h" name="h" size="6" class="calcbox"></td>
        </tr>
        <tr>
          <td align="right" class="wp"><strong>Neck&nbsp;</strong></td>
          <td><input type="text" id="n" name="n" size="6" class="calcbox"></td>
        </tr>
        <tr>
          <td align="right"><strong class="wp">Waist</strong>&nbsp;</td>
          <td><input type="text" id="w" name="w" size="6" class="calcbox"></td>
        </tr>
        <tr>
          <td align="right" class="wp"><strong>Hips</strong>&nbsp;</td>
          <td><input type="text" id="r" name="r" size="6" disabled="disabled" class="calcbox"></td>
        </tr>
        <tr>
          <td colspan="2" align="center"><input type="button" value="Calculate" onclick="calc(this.form);return false;" name="button2" class="calcbutton" style="font-size:12px;font-family:Verdana, Arial, Helvetica, sans-serif;font-weight: bold;color:#305996;vertical-align:middle">
                <input type="reset" value="Reset" onclick="clearForm(this.form)" class="calcbuttons" style="font-size:12px;font-family:Verdana, Arial, Helvetica, sans-serif;font-weight: bold;color:#305996; vertical-align:middle"></td>
          </tr>
        <tr>
          <td height="19" colspan="2" align="center" class="bigbold">&nbsp;</td>
        </tr>
        <tr>
          <td height="19" colspan="2" bgcolor="#DDDDDD" id="mus"><div align="center"><span class="smallw">RESULT</span></div></td>
        </tr>
        <tr>
          <td align="right"><strong>BODY FAT </strong></td>
          <td><input type="text" id="f" name="f" size="6" readonly="readonly" class="calcboxa"></td>
        </tr>
      </tbody></table>
    </form></td>
  </tr>
</tbody></table>
