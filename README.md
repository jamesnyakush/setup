# Development Tools

- [Development Tools](#development-tools)
  - [IDES](#ides)
    - [Toolbox](#toolbox)
    - [Android Studio](#android-studio)
      - [Plugins](#plugins)
      - [Compilers](#compilers)
    - [Goland](#goland)
      - [Install Latest Go](#install-latest-go)
    - [Visual Studio](#visual-studio)
      - [Themes](#themes)
      - [Plugins](#plugins-1)
    - [Postman](#postman)
    - [Docker](#docker)
    - [Postgress](#postgress)
  - [Compilers etc](#compilers-etc)
    - [NPM](#npm)
- [Productivity Tools](#productivity-tools)
  - [Browser](#browser)
    - [Chrome](#chrome)
    - [Firefox](#firefox)

  - [Browser](#browser)
    - [Chrome](#chrome)
    - [Firefox](#firefox)

<!-- These  are integrated  development  -->

## IDES

### Toolbox

1.  [Toolbox](https://www.jetbrains.com/toolbox-app/)

### Android Studio

#### Plugins

1.  Material theme
2.  JSON to kotlin class
3.  Key promoter X
4.  Grahpql

#### Compilers

```console
$ sudo apt update
$ sudo apt install openjdk-8-jdk openjdk-8-jre
$ java -version

$ sudo snap install kotlin --classic
```

### Goland

#### Install Latest Go

### Visual Studio

```console
$ sudo snap install --classic code
```

#### Themes

    1. Material

#### Plugins

    1. Laravel
    2. Php intelliphase
    3. vue
    4. Docker

### Postman

```console
$ sudo snap install postman
```

### Docker

```console
// Update
$ sudo apt update
$ sudo apt install apt-transport-https ca-certificates curl software-properties-common
$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
$ sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"

// Update
$ sudo apt update

$ apt-cache policy docker-ce

// Installing Docker
$ sudo apt install docker-ce

// Checking status
$ sudo systemctl status docker

// Running as Super Admin
$ sudo usermod -aG docker ${USER}
$ su - ${USER}
$ id -nG
```

### Postgress

[Digital oceans way](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-18-04)

```console

$ sudo apt update
$ sudo apt install postgresql postgresql-contrib
$ sudo -u postgres psql
$ sudo -u postgres createuser --interactive

```

<!--  -->

## Compilers etc

- Vue cli

### NPM

```console
$ curl -sL https://deb.nodesource.com/setup_14.x -o nodesource_setup.sh
$ nano nodesource_setup.sh
$ sudo bash nodesource_setup.sh
$ sudo apt install nodejs
$ node -v
```

- zip
- Zeal

<!--  -->

# Productivity Tools

## Browser

### Chrome

### Firefox
