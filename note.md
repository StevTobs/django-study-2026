# Note

**Run server:**
```bash
python manage.py runserver
```
**List commands:**
```bash
django-admin 
```
**Start a new project:**
```bash
django-admin startproject <project_name>
```

## Buiding an new app:
```bash
python manage.py startapp <project_name>
```


ทุกครั้งที่สร้าง app จะต้องไป define ใน setting.py
```bash
INSTALLED_APPS = [

    '<App_name>.apps.ProjectsConfig'
]
# 'ProjectsConfig' คือชื่อ class ใน apps.py ของแอพที่เจนมาใหม่
```


## Extension
- One Dark Pro
- Auto Rename Tag
- Prettier - Code formatter
- VSCode Terminal
