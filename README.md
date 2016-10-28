# LoginPage
新用户注册页面

## 新用户注册账号
+ 验证电话
+ 发送验证码
+ 更新验证码
+ 发送验证码倒计时
+ 验证密码（不得小于6位数）
+ 验证确认密码（两次密码输入一致）

## 发送验证码，通过ajax发送给后台
```js
			$.ajax({
				url:' ',
				type:'post',
				data:{
					'mobile': ,
					'email': ,
					'validateCode': ,
					'password': 
					},
					async:false,
					success:function(data){
						
					},
					error:function(msg){
						
					}
				});

```
