# SPEC.md - JOSP-healthy

## 1. Project Overview

- **Project Name**: JOSP-healthy
- **Project Type**: Maven Multi-Module Project (Spring)
- **Description**: Spring框架学习项目，包含Spring框架的基础配置和Maven多模块项目结构示例。项目目前处于规划阶段，主要用于学习Spring框架的核心概念和配置方式。
- **Location**: /Users/junw/Documents/GitHub/JOSP-healthy

## 2. Build Status

**Unknown** - No compilation attempted (per task requirements for "other" type projects)

## 3. Project Structure

```
JOSP-healthy/
├── spring_parent/              # Maven parent module
│   ├── pom.xml                  # Parent POM
│   ├── spring_health_common/    # Common utilities module
│   ├── spring_health_interface/ # Interface module
│   ├── spring_health_backend/   # Backend web module (Spring MVC)
│   └── health_service_provider/# Service provider module (Dubbo)
├── README.md
├── LICENSE
└── .gitignore
```

## 4. Technology Stack

- Java 8+
- Spring 5.x (Traditional Spring MVC, not Spring Boot)
- Maven Multi-Module
- Dubbo (RPC framework)
- MyBatis
- MySQL
- Redis
- MongoDB
- ElementUI (Frontend)

## 5. Module Descriptions

| Module | Description |
|--------|-------------|
| spring_parent | Parent POM, manages dependency versions |
| spring_health_common | Common utilities, models, entities |
| spring_health_interface | Service interfaces (API definitions) |
| spring_health_backend | Web layer with Spring MVC |
| health_service_provider | Service implementation with Dubbo |

## 6. Key Features (Planned)

- 健康数据管理
- 运动计划制定
- 饮食建议功能
- 数据可视化
- 多端支持 (Web, Mobile, WeChat Mini)

## 7. README Status

- README.md: EXISTS
- SPEC.md: CREATED (this file)

## 8. Gitignore

Standard Java gitignore covering:
- Compiled class files (*.class)
- Log files (*.log)
- Maven target/ directories
- IDE files (.idea, .iml)
- OS files (.DS_Store)

## 9. Note

This is a traditional Spring MVC project (not Spring Boot), organized as a Maven multi-module project. It uses:
- Spring XML configuration files
- Dubbo for service RPC
- MyBatis for data access

## 10. Last Updated

2026-04-22
