# 短链接口令
## 生成短链接（需要授权）
    url + (pwd) + 'url' + ('code')
    
> 参数
>> pwd：填写则生成带访问密码的短链接，否则生成不带访问密码带短链接
>> 
>> url：替换为需要转成短链接的链接
>> 
>> code（需要单独授权）：替换为自定义带code值；填写则生成自定义后缀带短链接，否则生成随机六位后缀带短链接

> 例子
>> url https://zhe.xiaobannet.com
>> 
>> url pwd https://zhe.xiaobannet.com
>> 
>> url https://zhe.xiaobannet.com youhui

## 重置密码
    pwd + 'url'

> 参数
>> url：替换为生成的短链接

> 例子
>> pwd https://urler.cn/youhui

## 查看近期生成的短链接（需要授权）
    alldata

## 查看短链接数据（需要授权）
    data + 'url'

> 参数
>> url：替换为生成的短链接

> 例子
>> data https://urler.cn/youhui
