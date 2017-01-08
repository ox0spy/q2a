## Python 入门

### IDE

- vim
 + [k-vim](https://github.com/wklken/k-vim)
- pycharm

### 入门资料

- [Beginner's Guide to Python](https://wiki.python.org/moin/BeginnersGuide)
- [The Python Tutorial](https://docs.python.org/3/tutorial/index.html)
 + [Python tutorial中文](http://python.usyiyi.cn/translate/python_352/tutorial/index.html)
- [A Byte of Python](https://python.swaroopch.com/)
- [Google's Python Class](https://developers.google.com/edu/python/)
- [Python教程by廖雪峰](http://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000)
- [Learn Python The Hard Way](https://learnpythonthehardway.org/)
- Python基础教程 或 Python核心编程3

需要掌握：

- 数据类型、变量、流程控制、函数、文件操作、基本数据类型的遍历及操作
- 特性：切片、迭代、列表生成式、生成器、迭代器
- map、reduce、filter、sorted、装饰器
- 模块
- 面向对象编程
- 错误、异常、调试
- 多进程、多线程、正则表达式
- 协程：Gevent
- async/await
- 常用模块: this, os, sys, time, datetime, base64, hashlib, struct, re, requests, threading, multiprocessing, logging, json

### 编码风格

- [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
- [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html)

### 最佳实践

- [The Hitchhiker’s Guide to Python!](http://docs.python-guide.org/en/latest/)

### FAQ

- [Python Frequently Asked Questions](https://docs.python.org/3/faq/)

## Python Web开发入门

### Web Framwork

选一个框架，基于该框架学习web开发。

- [Flask](http://flask.pocoo.org/)
- [Django](https://www.djangoproject.com/)
- [Bottle](http://bottlepy.org/docs/dev/)
- [Tornado](https://github.com/tornadoweb/tornado)
- [Python's Web Framework Benchmarks](http://klen.github.io/py-frameworks-bench/)
- [更多python web framework](https://wiki.python.org/moin/WebFrameworks)

注：Flask和Bottle都是很容易学习的web框架，个人更推荐Flask；Django应该在Python Web开发领域占有半壁河山；追求高性能就用Tornado。

需要掌握：

- 理解后端MVC并学会在对应web框架中使用
- 模板(template)
- 错误处理
- debug
- 配置文件
- 请求(request)Header、params、body解析
- 响应(response)的Header、body设置
- 部署
 + nginx + gunicorn/uwsgi
 + suprvisor/runit

### RDS

- [PEP 249 -- Python Database API Specification v2.0](https://www.python.org/dev/peps/pep-0249/)
- SQLite
 + [sqlite3](https://docs.python.org/2/library/sqlite3.html)
- MySQL driver
 + [PyMySQL](https://github.com/PyMySQL/PyMySQL)
 + [mysql-connector-python](https://pypi.python.org/pypi/mysql-connector-python/2.0.4)
- ORM
 + [SQLAlchemy](http://www.sqlalchemy.org/)
 + [更多](https://www.fullstackpython.com/object-relational-mappers-orms.html)

需要掌握：

- Python操作MySQL、SQLite3

### NoSQL

- Redis
 + [redis-py](https://github.com/andymccurdy/redis-py)
 + [aioredis](https://github.com/aio-libs/aioredis)

### MQ

- [Queue](https://docs.python.org/2/library/queue.html)
- [RQ](http://python-rq.org/)
- [Celery](http://www.celeryproject.org/)
- [RabbitMQ](https://www.rabbitmq.com/)

### Web

- HTTP
 + [HTTP权威指南](https://book.douban.com/subject/10746113/)
- web server
 + nginx
 + apache
- Web前端，请参考web-frontend.md

## 参考

- [啄木鸟Python社区](http://wiki.woodpecker.org.cn/moin/)
- [Python For Beginners](https://www.python.org/about/gettingstarted/)
- [知道创宇研发技能表v3.1](http://blog.knownsec.com/Knownsec_RD_Checklist/index.html)
