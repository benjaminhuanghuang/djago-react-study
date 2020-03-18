## Preparing React code for Django project

- Create FRONTEND_ROOT in settings.py
```
  FRONTEND_ROOT = os.path.abspath(os.path.join(BASE_DIR, '..', 'frontend', 'build'))
```

- Add url handling in urls.py
```
  from django.conf.urls.static import static, serve
  
  re_path(r'^(?P<path>.*)$', serve, { 'document_root': settings.FRONTEND_ROOT}),
```