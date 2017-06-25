.. _topics-index:

==============================
Scrapy |版本| 文档
==============================

这篇文档里有你所需要的关于Scrapy的一切知识。
获得帮助
============

有问题? 我们来帮你!

* 尝试用 :doc:`FAQ <faq>` -- 使用指令获得常见问题的回答.
* 查看具体信息? 尝试用 :ref:`genindex` 或者 :ref:`modindex`.
* 使用 `StackOverflow using the scrapy tag`_搜索或提问问题.
* 使用 `Scrapy subreddit`_搜索或提问问题.
* 在Google论坛提问`scrapy-users mailing list`_.
* 在 `#scrapy IRC channel`_提问问题,
* 反应 Scrapy的BUG到`issue tracker`_.

.. _scrapy-users mailing list: https://groups.google.com/forum/#!forum/scrapy-users
.. _Scrapy subreddit: https://www.reddit.com/r/scrapy/
.. _StackOverflow using the scrapy tag: https://stackoverflow.com/tags/scrapy
.. _#scrapy IRC channel: irc://irc.freenode.net/scrapy
.. _issue tracker: https://github.com/scrapy/scrapy/issues


第一步
===========

.. toctree::
   :caption: First steps
   :hidden:

   intro/overview
   intro/install
   intro/tutorial
   intro/examples

:doc:`intro/overview`
    Understand what Scrapy is and how it can help you.

:doc:`intro/install`
    Get Scrapy installed on your computer.

:doc:`intro/tutorial`
    Write your first Scrapy project.

:doc:`intro/examples`
    Learn more by playing with a pre-made Scrapy project.

.. _section-basics:

基本概念
==============

.. toctree::
   :caption: 基本概念
   :hidden:

   topics/commands
   topics/spiders
   topics/selectors
   topics/items
   topics/loaders
   topics/shell
   topics/item-pipeline
   topics/feed-exports
   topics/request-response
   topics/link-extractors
   topics/settings
   topics/exceptions


:doc:`topics/commands`
    学习使用命令行工具来管理您的Scrapy脚本.
    Learn about the command-line tool used to manage your Scrapy project.

:doc:`topics/spiders`
    写一些规则来爬取您的网站.
    Write the rules to crawl your websites.

:doc:`topics/selectors`
    使用XPath从web页面中提取数据.
    Extract the data from web pages using XPath.

:doc:`topics/shell`
    在交互环境中测试您的代码.
    Test your extraction code in an interactive environment.

:doc:`topics/items`
    定义你想要抓取的数据.
    Define the data you want to scrape.

:doc:`topics/loaders`
    用提取的数据填入您的Item.
    Populate your items with the extracted data.

:doc:`topics/item-pipeline`
    用管道处理和存储您的数据.
    Post-process and store your scraped data.

:doc:`topics/feed-exports`
    使用不同的格式和存储来输出您的抓取的数据.
    Output your scraped data using different formats and storages.

:doc:`topics/request-response`
    理解用于表示HTTP请求和响应的类.
    Understand the classes used to represent HTTP requests and responses.

:doc:`topics/link-extractors`
    使用从页面中提取链接的类
    Convenient classes to extract links to follow from pages.

:doc:`topics/settings`
    学习如何配置Scrapy,全部内容 :ref:`可用设置 <topics-settings-ref>`.
    Learn how to configure Scrapy and see all :ref:`available settings <topics-settings-ref>`.

:doc:`topics/exceptions`
    了解所有可用的异常及其含义.
    See all available exceptions and their meaning.


内建功能
=================

.. toctree::
   :caption: 内建功能
   :hidden:

   topics/logging
   topics/stats
   topics/email
   topics/telnetconsole
   topics/webservice

:doc:`topics/logging`
    Learn how to use Python's builtin logging on Scrapy.

:doc:`topics/stats`
    Collect statistics about your scraping crawler.

:doc:`topics/email`
    Send email notifications when certain events occur.

:doc:`topics/telnetconsole`
    Inspect a running crawler using a built-in Python console.

:doc:`topics/webservice`
    Monitor and control a crawler using a web service.


Solving specific problems
=========================

.. toctree::
   :caption: Solving specific problems
   :hidden:

   faq
   topics/debug
   topics/contracts
   topics/practices
   topics/broad-crawls
   topics/firefox
   topics/firebug
   topics/leaks
   topics/media-pipeline
   topics/deploy
   topics/autothrottle
   topics/benchmarking
   topics/jobs

:doc:`faq`
    Get answers to most frequently asked questions.

:doc:`topics/debug`
    Learn how to debug common problems of your scrapy spider.

:doc:`topics/contracts`
    Learn how to use contracts for testing your spiders.

:doc:`topics/practices`
    Get familiar with some Scrapy common practices.

:doc:`topics/broad-crawls`
    Tune Scrapy for crawling a lot domains in parallel.

:doc:`topics/firefox`
    Learn how to scrape with Firefox and some useful add-ons.

:doc:`topics/firebug`
    Learn how to scrape efficiently using Firebug.

:doc:`topics/leaks`
    Learn how to find and get rid of memory leaks in your crawler.

:doc:`topics/media-pipeline`
    Download files and/or images associated with your scraped items.

:doc:`topics/deploy`
    Deploying your Scrapy spiders and run them in a remote server.

:doc:`topics/autothrottle`
    Adjust crawl rate dynamically based on load.

:doc:`topics/benchmarking`
    Check how Scrapy performs on your hardware.

:doc:`topics/jobs`
    Learn how to pause and resume crawls for large spiders.

.. _extending-scrapy:

Extending Scrapy
================

.. toctree::
   :caption: Extending Scrapy
   :hidden:

   topics/architecture
   topics/downloader-middleware
   topics/spider-middleware
   topics/extensions
   topics/api
   topics/signals
   topics/exporters


:doc:`topics/architecture`
    Understand the Scrapy architecture.

:doc:`topics/downloader-middleware`
    Customize how pages get requested and downloaded.

:doc:`topics/spider-middleware`
    Customize the input and output of your spiders.

:doc:`topics/extensions`
    Extend Scrapy with your custom functionality

:doc:`topics/api`
    Use it on extensions and middlewares to extend Scrapy functionality

:doc:`topics/signals`
    See all available signals and how to work with them.

:doc:`topics/exporters`
    Quickly export your scraped items to a file (XML, CSV, etc).


剩余部分
============

.. toctree::
   :caption: 剩余部分
   :hidden:

   news
   contributing
   versioning

:doc:`news`
    See what has changed in recent Scrapy versions.

:doc:`contributing`
    Learn how to contribute to the Scrapy project.

:doc:`versioning`
    Understand Scrapy versioning and API stability.
