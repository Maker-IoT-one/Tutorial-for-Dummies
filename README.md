# Tutorial-for-Dummies
> Git日常维护傻瓜式流程

# 1、创建前注意:

1、将自己Github的对外用户名改为自己姓名的拼音，便于识别

  - 点击头像进入设置

  <img src="./img/点击头像.png" width="600">

  <img src="./img/进入设置.png" width="600">

  - 修改对外展示姓名并保存

   <img src="./img/public.png" width="600">

# 2、创建组织内仓库

- 进入IoT组织--->点击Repositorie-->点击New Repositories

    <img src="./img/选择组织.png" width="600">


    <img src="./img/进入组织.png" width="600">

    <img src="./img/流程0.png" width="600">

- 输入新建仓库的参数信息，
   - 仓库名："团队英文名简称-个人姓名拼音"<br>
   - 仓库简介："日期-团队英文名简称-个人中文姓名-开发模块"
      - SCT:Smart Carbon Technology(智碳科技团队)
      - AVP:Audio-visual pigs on the cloud(视听云上猪团队)
      - AD:AuNPs Detection(纳米金检测团队)
      - CSR:Cervical Spondylopathy Recovery(颈康复团队)
      - DAS:Depression assessment and screening(抑郁评估团队)
      - PAS:Parkinson's Assessment and Screening (抗帕助手团队)
      - VD:Virtual doctors(虚拟术士团队)
   - 点击 "Public"（公开仓库）
   - 点击 "Add a README file"（创建仓库介绍文件）
   - Creat repository (创建仓库)

  - 示例截图

       <img src="./img/创建仓库参数填写示例.png">

# 3、迁移组织内仓库到团队（项目负责人进行，成员无权限，可跳过）

- 进入Github---->进入IoT组织--->点击Teams--->点击个人所在的团队

    <img src="./img/流程1.png" width="600">

- 点击Repositories

    <img src="./img/流程2.png" width="600">

- 将组织仓库添加到团队内

    <img src="./img/流程3.png" width="600">

- 完成示例
    <img src="./img/完成示例.png" width="600">

# 4、维护仓库

- 将仓库克隆到本地

  ```ps
  #打开powershell
  win + s ， 输入powerhsell ，点击即可进入

  #进入电脑桌面
  cd Desktop

  #使用仓库的url克隆仓库，url通过下图方式获取
  git clone repository_url
  ```
  <img src="./img/http_url.png" width="600">

   成功示例

  <img src="./img/clone示例.png" width="600">

- 开始工作

  ```ps
  #进入仓库
  cd SCT-LiHaonan

  #查看本地仓库内容
  ls

  #工作内容省略
  ......
  ```
  成功示例<br>

  <img src="./img/进入仓库.png" width="600">

- 更新仓库

  ```ps
  # 添加所有改动到暂存区
  git add .

  # 提交暂存区的改动到本地仓库，""内填写提交信息
  git commit -m ""

  # 将本地仓库的改动推送到远程仓库的main分支
  git push origin main
  ```
