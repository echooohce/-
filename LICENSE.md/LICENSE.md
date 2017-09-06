<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
	</head>
	<body>
		<script>
			//set的用法：成员的值都是唯一的，没有重复的值		
			//数组去重
			 var arr = [1,2,1,2,3,4,3,4,6,6,2];
			 console.log(arr);//在控制台打印arr数组
			 var arr2= new Set (arr);//利用Set去重
			 console.log(arr2);//在控制台打印去重以后的新数组arr2
			 var newArr = new Array (...arr2);//展开数组
			 console.log(newArr);
		</script>
	</body>
</html>
