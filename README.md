# layui按钮组

#### 项目介绍
使用layui配合jquery完成按钮组


# 使用说明

* 后台按钮组
* elem -- 对应的选择器
* size -- 按钮大小，可选项：【lg】【sm】【xs】
* click_color -- 初始和点击按钮的颜色，默认值：layui-btn-warm 可选：原始-【layui-btn-primary】百搭-【layui-btn-normal】暖色-【layui-btn-warm】警告-【layui-btn-danger】禁用-【layui-btn-disabled】
* no_click_color -- 点击后其他按钮的颜色，默认值：layui-btn-normal 可选：原始-【layui-btn-primary】百搭-【layui-btn-normal】暖色-【layui-btn-warm】警告-【layui-btn-danger】禁用-【layui-btn-disabled】
* id -- 唯一，这块是为了保证每个按钮组的唯一性，或者不填
* placeholder --  input搜索框里placeholder的值
* input_other -- input其他属性，可自己选填，默认为readonly，可以加入如style
* button -- 自定义按钮组【如果此选项为对象，那么默认的不再显示，以及默认的搜索框不再显示，需要有date才能显示】
*      init -- 有此值时，为默认点击，初始化成功后也是把此number先返回给本回调
*      number -- 回调的第一个参数值
*      name -- 按钮名称
* date -- 此值需要配合button才有效，只需要传入按钮名称
* success -- 回调
*      有两个参数，number 和 text
*      number -- 返回的button 中的number值，或返回默认按钮组的number值
*      text -- 只有当number为0时才会返回，此值为input框内的值
* 默认按钮组：
*       今天：number -- 1
*       昨日：number -- 2
*       七天：number -- 3
*       本月：number -- 4
*       全部：number -- 5
*       搜索：number -- 0
* 值得注意的是。success回调里，必须要用双引号，否则会报没包好



