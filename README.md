# node-angular-blog
继续开更，低产continue中。增加了无人回复的话题这一块以及友情链接，调整了部分样式，并将最新的版本部署到了VPS上。  
/*  
这是之前的更新内容  
本次更新内容如下:  
修复了一些bug，调整了一些样式，在用户模型中增加了注册时间项，增加了用户个人信息页视图userInfo.html的展示，对应Angular的控制器为userInfoCtrl，服务端通过userInfo-controller.js处理对用户个人信息的请求。  
更新内容如下：  
用户信息中增加了‘用户评论的话题’和‘用户发表的话题’这两个数组项，为后期用户信息页的展示提供数据，当用户删除自己发表的话题后，会对所有用户信息进行检测，在‘用户发表的话题’和‘用户评论的话题’中删除该话题。  
修复了一些bug，当用户修改了自己的个人信息时，通过modify-controller.js进行处理，在话题详情页showTopic.html中该用户的评论或者回复中的用户信息也‘同步’变化，以及若该用户为作者，作者信息也‘同步’变化。  
*/
