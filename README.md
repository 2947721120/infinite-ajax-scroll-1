无限的AJAX滚动

====================

一个jQuery插件让你的分页页面进入无限滚动页面轻松。

下载，文档和演示可在: http://infiniteajaxscroll.com/

[![Build Status](https://travis-ci.org/webcreate/infinite-ajax-scroll.png?branch=master)](https://travis-ci.org/webcreate/infinite-ajax-scroll)

## Licensing

Infinite AJAX Scroll may be used in commercial projects and applications with the one-time purchase of a commercial license.

http://infiniteajaxscroll.com/docs/license.html

For non-commercial, personal, or open source projects and applications, you may use Infinite AJAX Scroll under the terms of the MIT License. You may use Infinite AJAX Scroll for free.

## Contributing

To contribute to Infinite AJAX Scroll please follow these instructions:

* Fork the project and create a new feature branch
* Install the development tools
* Write the feature/bugfix
* Write tests for the feature/bugfix
* Run tests
* Submit your Pull Request

###安装开发工具

1. 安装 bower components

    ``` sh
    $ bower install
    ```

2. 安装 npm modules

    ``` sh
    $ npm install
    ```

### 运行测试

测试完成[Busterjs](https://github.com/busterjs/buster) and [Grunt](https://github.com/gruntjs/grunt).

1. 开始一个克星服务器：

    ``` sh
    $ grunt buster::server:block
    ```

2.推出一些浏览器和连接 `http://localhost:1111` 捕捉它们。

3. 运行测试：

    ``` sh
    $ grunt buster::test
    ```
