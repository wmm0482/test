<!DOCTYPE html>
<html>
 <head>
  <title> new document </title>
  <meta charset="utf-8">
 </head>
 <body>
  <h1>使用代码触发事件</h1>
	 <button id="btn1">btn1</button>
	 <button id="btn2">btn2</button>
   <script src="js/jquery-1.11.3.js"></script>
  <script>
   $("#btn1").click(function(){
     alert("提交");
   });
   //模拟点击操作
   $("#btn2").click(function(){
     $("#btn1").trigger("click");
   });
  </script>
 </body>
</html>
