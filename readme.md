```
py -m venv venv
pip install -U djoser
py .\manage.py runserver 8088
```

https://djoser.readthedocs.io/en/latest/getting_started.html
https://github.com/sunscrapers/djoser?tab=readme-ov-file

```
#powershell test

#user create
curl.exe -X POST http://127.0.0.1:8088/auth/users/ --data 'username=djoser&password=alpine12'

#user login
curl.exe -X POST http://127.0.0.1:8088/auth/token/login/ --data 'username=djoser&password=alpine12'
```
