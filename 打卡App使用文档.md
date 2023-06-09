# 一、图标
1. 图标为一个笔记本和一根笔的图片
2. 名为每日打卡app
   
如图：
![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315152407627-355224968.png)
# 二、整体布局
1. 采用蓝色为背景基色，整体显得简洁整齐。
2. 顶部有统一的标题栏，点击返回图标可返回上一个页面，方便使用。

如图:
![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315153014844-1179431825.png)
# 三、注册页面
![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315153204169-1948949366.png)
**使用方法**
1. 依次输入学号、姓名、手机号、班级、密码、确认密码
2. 点击注册，弹出注册成功提示信息,并且返回到登录页面，账号数据将存储到SQLite本地数据库，并且将刚才注册的账号自动添加到登录页面。
   ![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315154423242-1340132204.png)

另外：确认密码失去焦点后两次的密码若不一致则会弹出提示信息。
![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315153732425-904564666.png)

# 四、登录界面
**使用方法**
点击学生登陆或教师登录分别进入学生界面或教师界面,
并且弹窗提示。

# 五、学生打卡界面
### 界面介绍
![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315161656774-1579548890.png)
1. 顶部通过查询远程数据库记录显示坚持天数和最长连续天数。
2. 中上部分输入打卡日期关键字和总结。
    点击选择按钮弹出日期选择框，选择日期
    ![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315162114339-693995347.png)
    填入关键字和总结后点击打卡按钮即可打卡。
    ![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315162621158-350338282.png)
    点击刷新按钮，顶部的信息将会刷新。
3. 点击查看打卡记录按钮将会挑战到打卡记录界面
   其中已打卡的日期将会标记为绿色
    ![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315162820168-1795256889.png)
4. 在提醒内容出输入内容，点击设置提醒选择时间
    ![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315163101108-1298157421.png)
    到达提醒时间将会弹出提醒
    ![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315163205746-556182604.png)
# 六、教师页面
1. 在登陆页面点击教师登录即可进入教师页面
![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315163356373-1732278709.png)
2. 点击查询全部会将远程数据库中的全部信息查询出显示在一个页面中。
![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315163512667-1492776413.png)
3. 输入关键字可按照关键字查询
   ![img](https://img2023.cnblogs.com/blog/2909356/202303/2909356-20230315163621367-1730483455.png)






