# freshman_1-fornt_end-

总体需求：实现一套用户注册、登录、列表展示的功能

# 第一步需求：htmlDemo1
1. jquer的引入以及ID选择器的使用，监控 提交按钮
2. js 判断输入的账号密码 和预设的账号密码是否一致（跳转成功界面），判断是否必填项是否为空。
3. html常见元素 form input 和页面跳转超链接元素

# 改善的需求：（第二版)(2018.1.29)
穿插了 chrome的断点调试（F8 F10 F11）
1. 正则表达式：添加手机号验证功能： 必须以139开头 而且必须是11位
2. 添加二级联动下拉框，出生省份和所在城市，可以只取3个省份，每个省份取3个城市。城市根据省份联动.
3. 引入jquery validation 框架验证必填项是否为空

# 第三版
1. 引入bootstrap 样式（注册和登录界面)
2. 添加bootstrap -table插件，实现 列表展示所有注册的用户信息


# 注意事项：
1. 密码框 input  type 要写成 password
2. jquery validation的时候，submit 之前要做处理，否则会忽略触发的js 校验代码
3. jquery validation的提交按钮 不能是 button  必须是 input type=submit
