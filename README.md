<!DOCTYPE html>
<html>
<head>
	<title>clacee</title>
</head>
<body bgcolor="skyblue">
	<style>
		input[type=button]
		{
			width: 30px;
			height: 40px;
			background-color: black;
			color: white;
		}
		input[type=text]
		{
			border: 1px solid gray
			background-color: red;
		}
		input[type=reset]
		{
			width: 65px;
			height: 40px;
			background-color: red;
			color: white;
		}
		input[type=submit]
		{
			width: 65px;
			height: 40px;
			background-color: green;
			color: white;
		}
		input[name=email]
		{
			width: 180px;
			height: 40px;
			background-color: orange;
			color: white;
		}
		input[name=name]
		{
			width: 180px;
			height: 40px;
			background-color: orange;
			color: white;

		}
		textarea[name=message]
		{
			width: 180px;
			height: 40px;
			background-color: orange;
			color: white;
			
		}
		input[value=00]
		
	</style>

	<center><h2> CALCULATOR</h2></center>
	<br>
	<br>
	<center>
		<div class="wrap">
			<form name="cal">
			<input type="text" name="display">
			<br><br>
			<input type="button" value="9" onclick="cal.display.value+='9'">
			<input type="button" value="8" onclick="cal.display.value+='8'">
			<input type="button" value="7" onclick="cal.display.value+='7'">
			<input type="button" value="+" onclick="cal.display.value+='+'">
			<br><br>
			<input type="button" value="6" onclick="cal.display.value+='6'">
            <input type="button" value="5" onclick="cal.display.value+='5'">
            <input type="button" value="4" onclick="cal.display.value+='4'">
            <input type="button" value="-" onclick="cal.display.value+='-'">
            <br><br>
            <input type="button" value="3" onclick="cal.display.value+='3'">
            <input type="button" value="2" onclick="cal.display.value+='2'">
            <input type="button" value="1" onclick="cal.display.value+='1'">
            <input type="button" value="*" onclick="cal.display.value+='*'">
            <br><br>
            <input type="button" value="0" onclick="cal.display.value+='0'">
            <input type="button" value="/" onclick="cal.display.value+='/'">
            <input type="button" value="%" onclick="cal.display.value+='%'">
            <input type="button" value="=" onclick="cal.display.value =eval(cal.display.value)">
            <br><br>
             <input type="button" value="00" onclick="cal.display.value+='00'">
             <input type="reset" value="DELETE" onclick="cal.display.value= ''" id="del">
              <input type="button" value="." onclick="cal.display.value+='.'">
           

</form>



		</div>
	</center>
	<br>
	<br>
	 <form>
                <input name="name" placeholder="Name" type="text" required /><br/>
                <input name="email" placeholder="Email" type="email" required /><br/>
                <textarea name="message" placeholder="Message" required ></textarea>
                <input type="submit" value="SEND" class="submit" />
            </form>
            <br>
            <br>

</body>
</html>
