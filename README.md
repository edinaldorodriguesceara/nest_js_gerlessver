# nest_js_gerlessver

[![CircleCI](https://dl.circleci.com/status-badge/img/gh/edinaldorodriguesceara/nest_js_gerlessver/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/edinaldorodriguesceara/nest_js_gerlessver/tree/master)


<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>


https://github.com/juniormesquitadandao/gerlessver

```bash
git clone git@github.com:edinaldorodriguesceara/nest_js_gerlessver.git
cd nest_js_gerlessver
  
  ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose config
  ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose build
  docker compose up -d
  docker compose exec app bash
    cat /etc/hosts | grep dockerhost

    npm install
    npm run test
    npm run start:dev
    # Brower: http://localhost:3000
    # Press: CTRL+C
    git status
    git add .
    git commit -m 'update'
    git push
    exit
  docker compose down
