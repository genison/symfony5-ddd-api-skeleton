### Installation

For the installation of the project it is necessary to follow the following steps.

--- 

Cloning the project.

```sh
$ git clone https://gitlab.com/thomas.matheus60/sf4-ddd-skeleton.git
```

---

Install the dependencies 

```sh
$ cd sf4-ddd-skeleton
$ composer install
```

---

Start server for dev.

```sh
$ php bin/console server:run
```

Verify the deployment by navigating to your server address in your preferred browser.

```sh
http://127.0.0.1:8000/api/doc 
```

--- 

This project follows the following DDD structure.

```bash
├── assets
│   └── ...
├── bin
│   └── ...
├── config
│   ├── application
│   │   └── services.yaml
│   ├── infrastructure
│   │   ├── doctrine
│   │   │   └── **/*.xml
│   │   ├── serializer
│   │   │   └── **/*.yaml
│   │   ├── validator
│   │   │   └── **/*.yaml
│   │   └── services.yaml
│   └── ... 
├── public
│   └── ...
├── src
│   ├── Domain   
│   │   ├── Model
│   │   └── ...
│   ├── Infrastructure
│   │   ├── Repository
│   │   │   └── **/*.php
│   │   ├── Services
│   │   │   └── **/*.yaml
│   │   └── ...
│   ├── Presentation
│   │   ├── Controller
│   │   │   └── ...
│   │   └── ...
├── templates
│   └── ...
├── tests
│   └── ...
├── translations
│   └── ...
├── var
│   └── ...
├── .env
├── .env.dist
├── composer.json
├── composer.lock
├── symfony.lock
├── phpunit.xml.dist
└── .gitignore
```
