- ## 使用方式

  下载FT4.0到本地，解压后文件本地，用chrome打开index.html,在右侧文本框输入文本。

  学术家族树以文本形式输入，点击提交文本框。

- ## 文本格式

  ### 输入:

  学术家族树以文本形式输入，点击提交文本框，考虑学术家族树的文本格式是这样的：

  导师：张三

  2016级博士生：天一、王二、吴五

  2015级硕士生：李四、王五、许六

  2016级硕士生：刘一、李二、李三

  2017级本科生：刘六、琪七、司四

   导师：吴五
  2016级博士生：天一、王二、吴

  2015级硕士生：李四、王五、许六

  2016级硕士生：刘一、李二、李三

  2017级本科生：刘2、琪七、司四

  导师：刘2
  2016级博士生：天一、王二

  2015级硕士生：李四、王五、许六

  2016级硕士生：刘一、李、李三

  2017级本科生：刘、琪七、司四

  导师：王二
  2016级博士生：天一、王二

  2015级硕士生：李四、王五、许六

  2016级硕士生：刘、李二、李三

  !!!文本最后不能换行

  其中，"导师："，"级博士生："，"级硕士生："，"级本科生："和"、"当做关键词处理；若有多组输入，中间空一行。

  ### 输出:

  **树的节点，鼠标点击后是可以缩放的。同时，支持呈现多棵树并存、两棵关联树共存等形式。**

  在左侧家族树下会显示可缩放的树状结构，即生成的家族树。
