## Deploy on pythonanywhere

CSS not work follow the following steps:

- STATIC_URL = '/static/'
- STATIC_URL = '/static/'
- STATIC_ROOT=os.path.join(BASE_DIR,'static')
- MEDIA_ROOT=os.path.join(BASE_DIR,'media')
- MEDIA_URL='/media/'

- You can check out [Need help ](https://help.pythonanywhere.com/pages/DeployExistingDjangoProject)

## Most Important

- collect static files using bash console

  - python manage.py collectstatic

- github
  - git init
  - git add .
  - git commit -m "first commit"
  - git branch -M main
  - git remote add origin https://github.com/ciwzakir/django-backend.git
  - git push -u origin main
