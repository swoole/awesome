<div align="center">

# Awesome Swoole ![](https://github.com/swoole/awesome-swoole/workflows/Awesome%20Bot/badge.svg)

A curated list of awesome things related to <a href="//github.com/swoole/swoole-src">swoole</a>.

<img src="https://cdn.jsdelivr.net/gh/sy-records/staticfile/images/swoole/logo.png">

</div>

## 客户端

- [swoole/grpc](https://github.com/swoole/grpc) 由 Swoole 驱动的 Grpc 协程客户端, 底层使用高性能协程 Http2-Client 客户端
- [swoole/ext-zookeeper](https://github.com/swoole/ext-zookeeper) 基于 Swoole 协程的 PHP ZooKeeper 客户端
- [swoole/ext-postgresql](https://github.com/swoole/ext-postgresql) 基于 Swoole 协程的 PHP PostgreSQL 客户端
- [swlib/saber](https://github.com/swlib/saber) PHP 异步协程 HTTP 客户端
- [hyperf/jet](https://github.com/hyperf/jet) 一个统一模型的 RPC 客户端，内置 JSONRPC 协议的适配，该组件可适用于所有的 PHP 环境，包括 PHP-FPM 和 Swoole
- [hyperf/consul](https://github.com/hyperf/consul) 由 Hyperf 提供的 Consul 协程客户端
- [hyperf/elasticsearch](https://github.com/hyperf/elasticsearch) 由 Hyperf 提供的 Elasticsearch 协程客户端
- [hyperf/etcd](https://github.com/hyperf/etcd) 由 Hyperf 提供的 ETCD 协程客户端
- [Yurunsoft/Guzzle-Swoole](https://github.com/Yurunsoft/Guzzle-Swoole) 让基于 Guzzle 的项目完美无缝兼容 Swoole 协程，支持：Guzzle、Elasticsearch Client
- [Yurunsoft/YurunHttp](https://github.com/Yurunsoft/YurunHttp) 完美支持 Curl、Swoole 协程的 PHP HTTP 客户端，支持链式操作，简单易用
- [simps/mqtt](https://github.com/simps/mqtt) 适用于 PHP 的 MQTT 协议解析和协程客户端

## 消息队列

- [longyan/phpkafka](https://github.com/longyan/phpkafka) PHP Kafka 协程客户端
- [hyperf/amqp](https://github.com/hyperf/amqp) 由 Hyperf 提供的 AMQP 协程组件
- [hyperf/async-queue](https://github.com/hyperf/async-queue) 由 Hyperf 提供的简单的基于 Redis 的异步队列组件

## 数据库

- [simple-swoole/db](https://github.com/simple-swoole/db) 封装 Swoole Library 中提供的数据库连接池组件
- [hyperf/database](https://github.com/hyperf/database) 由 Hyperf 提供的基于 Eloquent 衍生的数据库 ORM
- [hyperf/model](https://github.com/hyperf/model) 由 Hyperf 提供的基于 hyperf/database 组件的自动模型缓存组件
- [mix-php/database](https://github.com/mix-php/database) 基于 Swoole 的协程数据库组件，内置连接池
- [mix-php/redis](https://github.com/mix-php/redis) 基于 Swoole 的协程 Redis 组件，内置连接池
- [mix-php/redis-subscribe](https://github.com/mix-php/redis-subscribe) 基于 Swoole 协程的 Redis 订阅库

## Crontab

- [osgochina/swoole-crontab](https://github.com/osgochina/swoole-crontab) 基于 Swoole 的定时器程序，支持秒级处理，完全兼容 Crontab 语法
- [hyperf/crontab](https://github.com/hyperf/crontab) 由 Hyperf 提供的秒级定时任务组件

## Task

- [swlib/archer](https://github.com/swlib/archer) 基于协程 Swoole 的 Task 组件，支持多种模式。轻松实现协程 Task 的队列、并发、Defer、计时器等
- [hyperf/task](https://github.com/hyperf/task) 由 Hyperf 提供的 Task 组件，对 Swoole 的 Task 机制进行了封装及抽象，提供便捷的注解用法

## 热更新

- [mix-php/swoolefor](https://github.com/mix-php/swoolefor) 一个由 Mixphp 实现的通用热更新组件

## 开发调试

- [swoole/sdebug](https://github.com/swoole/sdebug) 用于协助开发与调试，xdebug 的协程改造版
- [swoole/ide-helper](https://github.com/swoole/ide-helper) 用于在 IDE 中自动补全代码
- [swoole/debugger](https://github.com/swoole/debugger) Swoole 远程调试器，业务无需做任何修改，只需要加一行代码即可引入一个功能强大的远程终端
- [Swoole Tracker](https://business.swoole.com/tracker.html) 提供内存泄漏分析、阻塞检测、性能分析、运行状态及调用统计等功能

## 日志

- [hyperf/logger](https://github.com/hyperf/logger) 由 Hyperf 提供的基于 PSR-3 的日志管理器，一个基于 monolog 的抽象及封装
- [mix-php/monolog](https://github.com/mix-php/monolog) 支持 Swoole 协程的 Monolog，支持 cli 控制台打印

## 服务治理

- [hyperf/tracer](https://github.com/hyperf/tracer) 由 Hyperf 提供的 OpenTracing 分布式调用链追踪组件
- [mix-php/tracing-zipkin](https://github.com/mix-php/tracing-zipkin) Zipkin 调用链追踪库，基于 Opentracing 标准

## 第三方 SDK

- [Yurunsoft/PaySDK](https://github.com/Yurunsoft/PaySDK) 支持 Swoole 协程的支付宝/微信支付 SDK
- [Yurunsoft/YurunOAuthLogin](https://github.com/Yurunsoft/YurunOAuthLogin) 支持 Swoole 协程的第三方登录授权 SDK(QQ、微信、微博、Github、Gitee 等)

## 集成

- [swooletw/laravel-swoole](https://github.com/swooletw/laravel-swoole) 基于 Swoole 的高性能 HTTP 服务器。加快您的 Laravel 或 Lumen 应用程序
- [hhxsv5/laravel-s](https://github.com/hhxsv5/laravel-s) Swoole 和 Laravel/Lumen 之间开箱即用的适配器
- [pachico/Slim-Swoole](https://github.com/pachico/slim-swoole) 使用 Swoole 运行 SlimPHP 应用程序的便捷库
- [liufee/yii2-swoole](https://github.com/liufee/yii2-swoole) yii2 和 Swoole 的集成
- [phwoolcon/phwoolcon](https://github.com/phwoolcon/phwoolcon) Phalcon 和 Swoole 的集成
- [mezzio/mezzio-swoole](https://github.com/mezzio/mezzio-swoole) Mezzio 和 Swoole 的集成

## 其他

- [mix-php/sync-invoke](https://github.com/mix-php/sync-invoke) Swoole 同步阻塞代码调用库，用于执行无法被 Swoole Hook 协程化的同步阻塞代码
- [viest/php-ext-xlswriter](https://github.com/viest/php-ext-xlswriter) 支持 Swoole 协程环境，可用于在 Excel 2007+ XLSX 文件中读取数据，插入多个工作表，写入文本、数字、公式、日期、图表、图片和超链接
