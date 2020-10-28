# 短链接口令
## 生成短链接
	url + 'url' + ('code')

* 参数

		url：替换为需要转成短链接的链接
		
		code（高级权限）：替换为自定义带code值；填写则生成自定义后缀的短链接，否则生成随机六位后缀的短链接

* 例子

		url https://zhe.xiaobannet.com
		
		url https://zhe.xiaobannet.com youhui

## 重置密码
	pwd + 'url'

* 参数

		url：替换为生成的短链接

* 例子

		pwd https://urler.cn/youhui
		
## 清空密码
	clear + 'url'
	
* 参数

		url：替换为生成的短链接

* 例子

		clear https://urler.cn/youhui

## 查看近期生成的短链接
	alldata

## 查看短链接数据
	data + 'url'

* 参数

		url：替换为生成的短链接

* 例子

		data https://urler.cn/youhui
