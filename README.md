# e
e店挂机
# py_elearning
### requirements.
  - lxml
  - arrow
  - pycrypto
  - requests
  - xmltodict

### 安装依赖库

```sh
$ pip install -r requirements.txt
```


### 使用

```python
>>> user = User(usr, pwd)  # 实例化E学用户
>>> user.do_login()  # 登录E学
>>> user.get_course_list()  # 取得当前未学课程状态
>>> user.get_lesson()  # 取得一号课程详细列表
>>> user.start_course()  # 开始学第一课
>>> user.save_course()  # 保存进度
```


   [国寿E学]: <http://wwww.elearning.clic>
