````
# six error
pip3 install six
pip3 install --upgrade django-cors-headers 
pip install django-utils-six

# Pillow
python3 -m pip install --upgrade pip
python3 -m pip install --upgrade Pillow
pip install wheel
pip install mysqlclient
````


数据库

```
python manage.py makemigrations

python manage.py migrate
```

表的关系:

* users
    * UserProfile用户信息
    * EmailVerifyRecord 邮箱验证码
    * Banner轮播图
* course
    * Course课程
    * Lesson章节
    * Video 视频
    * CourseResource课程资源
* organization
    * CourseOrg课程机构
    * CityDict 城市
    * Teacher
* operation
    * UserAsk 用户咨询
    * CourseComment 课程评论
    * UserFavorite 用户收藏
    * UserMessage 用户消息
    * UserCourse 用户课程