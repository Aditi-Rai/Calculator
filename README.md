<html>
<head>
<style>
.b{background-color:brown;
color:yellow;
padding:15px 30px;
text-align:center;
font-size:25px;
}
.t{font-size:20px}
.h{background-color:green
color:white;}
</style>
<script>
function ac()
{
document.getElementById("res").value="";
}
function show(input)
{
document.getElementById("res").value+=input;
}
function cal()
{
var output= eval(document.getElementById("res").value);
document.getElementById("res").value=output;
}
</script>
</head>
<body>
<table border="1" cellspacing="5px" cellpadding="5px">>
<caption><h1 class="h">SIMPLE CALCULATOR</h1></caption>
<tr>
<td colspan="3" align="center" bgcolor="black"><input type="text" class="t" id="res"></td>
<td align="center"><button class="b" onclick="ac()">AC</button></td>
</tr>
<tr>
<td align="center"><button class="b" onclick="show('1')">1</button></td>
<td align="center"><button class="b" onclick="show('2')">2</button></td>
<td align="center"><button class="b" onclick="show('3')">3</button></td>
<td align="center"><button class="b"onclick="show('+')">+</button></td>
</tr>
<tr>
<td align="center"><button class="b" onclick="show('4')">4</button></td>
<td align="center"><button class="b" onclick="show('5')">5</button></td>
<td align="center"><button class="b" onclick="show('6')">6</button></td>
<td align="center"><button class="b" onclick="show('-')">-</button></td>
</tr>
<tr>
<td align="center"><button class="b" onclick="show('7')">7</button></td>
<td align="center"><button class="b" onclick="show('8')">8</button></td>
<td align="center"><button class="b" onclick="show('9')">9</button></td>
<td align="center"><button class="b" onclick="show('*')">*</button></td>
</tr>
<tr>
<td align="center"><button class="b" onclick="show('0')">0</button></td>
<td align="center"><button class="b" onclick="show('%')">%</button></td>
<td align="center"><button class="b" onclick="show('/')">/</button></td>
<td align="center"><button class="b" onclick="cal()">=</button></td>
</tr>
</body>
</html>
