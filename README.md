# Blockchain-репозиторий закладных

> Конкурсный проект для хакатона "Блокчейн - новая нефть России", Казань, 27-29 августа 2017

![](https://github.com/BankEx/Blockchain-Hackathon-Kazan/blob/master/Images/BankEx.jpg?raw=true)

![](https://github.com/BankEx/Blockchain-Hackathon-Kazan/blob/master/Images/BankEx-2.jpg?raw=true)

## Онлайн демо
[https://hackathon.bankexlab.com](https://hackathon.bankexlab.com)

## Контракты

```bash
cd contracts/
```

## Веб приложение

```bash
сd webapp/
```
### Запуск через Node.JS

#### Предварительная подготовка

* Установка node/NPM https://github.com/creationix/nvm

#### Запуск

```bash
npm install
npm start
```

Веб приложение будет доступно по адресу ```http://localhost:3000```

### Запуск через Docker

#### Предварительная подготовка

* Установка Docker https://www.digitalocean.com/community/tutorials/docker-ubuntu-16-04-ru
* Установка Docker Compose https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-16-04

#### Запуск

```bash
docker-compose up -d
```

Веб приложение будет доступно по адресу ```http://localhost:3000```

#### Остановка

```bash
docker-compose down
```