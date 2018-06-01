# extend.VerifyAction
php300framework扩展插件：数据验证类库

下载类库文件放到框架目录的`Extend/Class`下即可

演示：
```
extend('VerifyAction.class.php');

if(\VerifyAction::isMobile($userName) === false) return ['code' => 101 , 'msg' => '手机号不正确'];

if(\VerifyAction::isEmpty($Password) === false) return ['code' => 101 , 'msg' => '密码不得为空'];

``` 
