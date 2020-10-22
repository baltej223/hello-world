<!--make a form with action "http://www.google.com/search"-->
<html>
<body id="mam">
<h1>search google</h1>
<div style="background-color:#f1f1f1;">
<form method="get" action="http://www.google.com/search">
<input type="text" name="q" size="50" id="src-box"  title="q"  onkeypress="changeth()" placeholder="search here...." autocomplete="off">
<br>
<input type="text" name="rlz" size="50" id="ox"  title="rlz" value="1C1SQJL_enIN889IN889" readonly>
<br>
<input type="text" name="oq" size="50" id="sr-ox"  title="oq" value="" placeholder="here automatic words will we written." readonly>
<br>
<input type="text" name="aqs" size="50" id="s-ox"  title="aqs" value="chrome..69i57j69i59l2j69i60l5.315j0j9" readonly>
<br>
<input type="text" name="sourceid" size="50" id="s-ox"  title="sourceid" value="chrome" readonly>
<br>
<input type="text" name="ie" size="50" id="s-ox"  title="ie" value="UTF-8" readonly>
<br>
<input type="submit" value="search" title="search on goooogle.ccccccoooooooommmmm"  id="sub" onclick="bavi">
</form>
  <!--write this script-->
<script>
function changeth(){
 var a = document.getElementById("src-box").value;
 document.getElementById("sr-ox").value=a;
}
</script>
</div>
</body>
</html>
