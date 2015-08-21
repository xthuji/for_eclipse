Eclipse 修改注释的 date time 日期时间格式，即${date} ${time}变量格式
相关插件包位置：
找到eclipse安装目录下面的plugins目录，搜索 org.eclipse.text ，找到一个jar包，
例如我找到的jar包为：org.eclipse.text_3.5.300.v20130515-1451.jar

修改
org.eclipse.jface.text.templates.GlobalTemplateVariables

采用“yyyy-MM-dd HH:mm:ss”格式