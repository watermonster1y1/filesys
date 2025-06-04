实验七


E-R图
![49294caf53a34fbf44405ece0332d4b7](https://github.com/user-attachments/assets/fbc08c25-88ee-44ac-8754-c8899cee4185)

UML图
![99db5eda4bbb0f4e4aae346115ea7412](https://github.com/user-attachments/assets/644112c3-05bf-4819-9609-63a446d1012d)
管理员关联：
    1对多发布公告
    1对多管理员工
    1对多上传文档

员工关联：
    多对多查看公告
    多对多下载文档

文档组成：
    1对多包含附件

核心属性：
   管理员：用户名、密码、角色
   员工：工号、姓名、性别、岗位
   文档：名称、类型
   公告：内容、发布时间
    附件：名称
