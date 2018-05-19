dnmp开发环境
1.docker + nginx + php + mysql + redis 服务结构
2.每个服务均支持多版本共存,方便phper开发时快速切换环境版本的需求
3.nginx目前仅支持1.14 支持自定义配置host主机
4.php目前支持5.4,5.6,7.2三个版本
5.mysql目前支持8.0和5.7二个版本
6.redis目前支持4.0版本
7.每个服务配置文和数据目前均已映射到host
8.web root目前支持自定义，只需要到docker-compose.yml做调整