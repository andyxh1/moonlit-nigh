## 日常cording 

​	18-12-14

​	在jsp中关于jQ的JavaScript	

```jsp
<script>
	$(function() {
		$(".recording").mouseover(function(){
			$(".recording_body").show();
			$(".recording").mouseout(function(){
				$(".recording_body").hidden();
				
			});
		});
		
	});
</script>
```

关于JQ的JavaScript

​	onmouseover写为	.mouseover()	注意：非	.onmouseover = 

​	补充：关于修改css样式：$(" 		").css("propertyname","value");