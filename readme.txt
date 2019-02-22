1.初始化node项目
npm init --yes

2.编码，关联git

3.npm注册（首次）
npm adduser

4.npm publish(提交前先提交代码)

(5.登录npm login)

(6.验证是否登录npm who am i)

7.更新npm version patch
npm push .

大型node插件目录结构
.
├── bin                         #运行目录
├── lib                         #主代码目录
├── example                     #示例目录
├── test                        #测试目录，提供单元测试
├── .travis.yml                 #集成自动测试配置
├── .npmignore                  #npm发布时忽略的文件
├── CHANGELOG.md               #版本更新说明
├── LICENSE                     #许可证书
├── package.json                #npm配置
├── README.md                   #README
