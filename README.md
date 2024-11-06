# ZangoFramework

book_management_project/
├── workspaces/
│   └── book_app/
│       ├── migrations/
│       ├── release/
│       ├── book/
│       │   ├── forms.py
│       │   ├── models.py
│       │   ├── policies.json
│       │   ├── tables.py
│       │   ├── urls.py
│       │   ├── views.py
│       │   ├── workflow.py
│       ├── manifest.json
│       └── settings.json
├── book_management_project/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls_public.py
│   ├── urls_tenants.py
│   ├── urls.py
│   └── wsgi.py
├── docker-compose.yml
├── docker-compose.prod.yml
├── dev.dockerfile
├── prod.dockerfile
└── manage.py


Book Management Endpoints
/book/all/

Method: GET
/book/add/

Method: POST
/book/<book_id>/edit/

Methods: GET, POST
/book/<book_id>/delete/

Method: DELETE
/book/<book_id>/status/

Method: POST
