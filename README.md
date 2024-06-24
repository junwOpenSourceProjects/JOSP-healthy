# :smile: junwSpringBootHealth 项目

本项目旨在实现健身房管理和健康管理项目的开发，基于 Dubbo 和 MVC 模式。
spring MVC的开发模式已经过时，后面有时间继续补全，目前暂时停止开发。
采用 soa，面向服务的模式，有移动端的服务，先看看。

## 功能

- 健身房模块：支持健身房管理、会员管理、课程管理、教练管理、团体课管理等功能
- 健康管理模块：支持用户健康档案管理、在线体测、健康数据分析等功能

## 系统架构

- 后端：SpringBoot + Mybatis
- 前端：Vue.js + Element-UI

## 使用说明

1. 克隆项目
```
git clone https://github.com/junw1997/junwSpringBootHealth.git
```

2. 修改数据库配置

修改根目录下的application.yml文件，将数据库配置改为自己的数据库配置。

3. 启动服务

```
cd junwSpringBootHealth
mvn spring-boot:run
```

4. 访问系统

访问 http://localhost:8080 即可访问系统。
