# learning_log
学习笔记

# 部署启动

```shell
python3 -m venv ll_env
source ll_env/bin/activate
python manage.py makemigrations learning_logs
python manage.py migrate
python manage.py runserver
```

# 调试

```shell
source ll_env/bin/activate
python manage.py shell
``
