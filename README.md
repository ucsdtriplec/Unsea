# UnSea 
**为UCSD中国留学生打造的多平台匿名论坛**  
[Website](https://unsea.ucsdtriplec.org)  
[Design](https://www.figma.com/file/9engUOmPwjAsvcumfgMbUw/UnSea-V2?node-id=0%3A1)  
[GitLab](https://gitlab.com/ucsd-triple-c/treehole)  
![UnSea_Logo](https://unsea.ucsdtriplec.org/images/unsea%20logo.png)

## 目录
- [成员](#项目组成员)
- [技术栈/框架](#技术栈/框架)
- [基本功能](#基本功能)
- [核心亮点](#核心亮点)
- [不足/反思](#不足/反思)
    - [技术](#技术)
    - [UI设计](#UI设计)
    - [产品设计](#产品设计)
    - [商业发展](#商业发展)
- [优点](#优点)
- [未来发展](#未来发展)
- [联系方式](#联系方式)


## 项目组成员
- Jasmine Tu (Product Manager & UI/UX Designer)   
- Mingxuan Fan (Tech Lead)
- Xinpei Tan (Developer & Former Product Manager)
- Jiaxi Wang (Developer)
- Qingran Li (Developer)
- Yifei Ye (UI/UX Designer)
- Lucy Guo (UI/UX Designer)
- JiaYang Bao (Business Development Supervisor)
- Yuru Zhou (Test Engineer)

## 技术栈/框架
**前端：**  
- Taro.js
- React Native
- Redux

**后端：**
- Spring MVC
- MySQL

**设计：**  
- Figma

## 基本功能
- 浏览/搜索帖子
- 匿名发帖或评论
- 点赞/收藏/删除/举报 其他用户的帖子

## 核心亮点
- UnSea支持多平台客户端，目前提供包括Android，iOS，微信小程序共3个平台的访问支持
- UnSea实现了对用户身份的保密。用户ID以加密形式存储在持久化数据库中，且无法在客户端显式获取
- UnSea实现了以DFA算法为基础的敏感文字过滤和通过Amazon ReKognition API实现的敏感图片过滤
- UnSea实现了以STOMP和Websocket为基础的即时消息服务

## 不足/反思
### 技术
- 在框架选型上存在失误，错误判断了所使用框架的可靠性，低估了原生开发的优势
- 前端Taro框架和后端Spring MVC框架的配置都非常繁琐，启动项目需要一定的学习成本
- 后端的MVC设计模式随着服务的增多显得愈发冗杂，建议以面向服务的模式和Spring AOP的理念重构
- 整个项目代码质量有限，可读性低，维护成本很高

### UI设计 & 产品设计
- 基于 Google Material Design & Apple Human Interface Design Guidelines设计
- 采用现流行的风格，白色背景让其干净舒适
- 使用Figma 让设计师间可以同时设计合作也让工程师们可以即时的知道设计的变化 

### 商业发展
- 

## 未来发展
- 如果你想重启这个项目 或 复用这个项目的代码，欢迎联系我。联系方式在下方

## 联系方式
- **Email:** ptrfmx@aliyun.com
- **Wechat:** FmX1010111
