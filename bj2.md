### 判断语句

```js
流程控制语句
     判断语句
      //语法1
     	if 条件表达式{
            
        }
		let a = 1;
		if(a!==1){
			console.log('为true了')
		}

	 //语法2	
       if 条件表达式{
      	 }else{
        }

		let a = 1;
		if(a!==1){
			console.log('为true了')
		}else{
			console.log('为fasle了')
		}
     //语法3、
		let a = 1;
		if(a!==1){
			console.log('进入if了')
		}else if(a===1){
			console.log('进入elseif了')
		}else{
			// 前面不满足条件，就会执行else
			console.log('进入else')
		}

```
### 选择语句

```js
// 选择语句
			var sw = 11;
			switch(sw){
				case 11:
					console.log('11')
					break; //结束switch语句
				case 22:
					console.log('22')
					break;
				case 33:
					console.log('33')
					break;
				// default不管写在那个位置，都是最后最后执行的。
				default:
					console.log('默认了')
					break;
				
			}
```
### 循环语句

```js
 for:
         // 初始化表达式 条件表达式  循环后表达式
			for(var a=0;a<10;a++){
				console.log(a)
			}
     while:
         var count = 0
         while(count<10){
			   console.log(count);
			   count+=1;
		   }
     do while:至少会执行一次
    		var count = 0
			do{
				console.log(count);
				count+=1;
			}while(count<10)
```

>循环语句

for(初始值;条件;增量){<br/>
	重复执行的操作<br/>
}

>函数

function 函数名(参数){<br/>
	函数体/函数执行的操作<br/>
	返回语句<br/>
}

发生事件的元素.on事件名=function(){<br/>
	发生事件是执行的操作<br/>
}

发生事件的元素.addEventListener(事件名字符串,function(){<br/>
	发生事件时执行的操作<br/>
})