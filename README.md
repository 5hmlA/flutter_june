
### 通过action 发布github page
 - 1 settings -- secret -- actions -- New repository secret -- 添加 dev_secret
     - *build.yml* 编译同时发布到release页面 需要配置 RELEASE_TOKEN
     - *ghpage.yml* 编译flutter web 同时部署 github page 需要配置 RELEASE_TOKEN