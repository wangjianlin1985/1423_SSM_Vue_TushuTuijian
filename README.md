
开发软件：Eclipse/Idea  数据库：Mysql

  本次设计任务是要设计一个基于协同过滤算法的图书推荐系统，通过这个系统能够满足图书推荐的管理功能。系统的主要包括首页、个人中心、用户管理、书籍管理、书籍分类管理、热门图书管理、我的收藏管理、系统管理、订单管理等功能。
管理员可以根据系统给定的账号进行登录，登录后可以进入图书推荐系统对个性化智能图书推荐所有模块进行管理。包括查看和修改自己的个人信息以及登录密码。
  该系统为每一个用户都分配了一个用户账号，用户通过账号的登录可以在系统中查看个性化智能图书推荐信息及对个人信息进行修改等功能。

前台地址：http://localhost:8080/ssmz87c4/front/pages/login/login.html
后台地址：http://localhost:8080/ssmz87c4/admin/dist/index.html#/login
后台账号密码： abo/abo  前台账号密码：11/11

协同过滤算法简介
  协同过滤算法是一种较为著名和常用的推荐算法，它基于对用户历史行为数据的挖掘发现用户的喜好偏向，并预测用户可能喜好的产品进行推荐。也就是常见的“猜你喜欢”，和“购买了该商品的人也喜欢”等功能。它的主要实现由：
　　●根据和你有共同喜好的人给你推荐
　　●根据你喜欢的物品给你推荐相似物品
　　●根据以上条件综合推荐
　　因此可以得出常用的协同过滤算法分为两种，基于用户的协同过滤算法(user-based collaboratIve filtering)，以及基于物品的协同过滤算法(item-based collaborative filtering)。特点可以概括为“人以类聚，物以群分”，并据此进行预测和推荐。
