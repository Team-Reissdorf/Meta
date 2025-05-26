# Meta
guideline tracker repo

## Guideliens
- english language
- main - only merge after PO approval
- dev - development branch, pushing only allowed after one peer approval 
- [REST - api spec](https://restfulapi.net/)
- [SemVer 2.0.0](https://semver.org/)

### Backend
- [go - lang](https://go.dev/)
- [gin-gonic - framework](https://gin-gonic.com/)
- [gorm - db](https://gorm.io/)

### Frontend
- [nginx - webserver](https://nginx.org/en/)
- [bootstrapjs - framework]([https://vuejs.org/](https://getbootstrap.com/))
- Vanilla Javascript
- [Axios - API calls](https://axios-http.com/docs/intro)

## testing full setup

0. clone repo: `git clone --recurse-submodule https://github.com/Team-Reissdorf/Meta.git`
1. update submodules (if you already have a copy): `git submodules update --init --recursive`
2. build and run:

| podman                       | docker                                         |
|------------------------------|------------------------------------------------|
|  `podman-compose up --build` |  `docker compose build && docker compose up` |
