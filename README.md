Instalação do Valet no Linux

```
sudo apt update
```

```
sudo apt install curl git unzip
```

```
sudo apt install nginx
```

```
sudo apt install net-tools
```

```
ifconfig
```
Pegar ip na segunda linha e abrir no broser, para testar o nginx

```
sudo apt php-fpm
```

```
sudo apt install php-mbstring php-xml php-zip php-curl
```

```
sudo apt install php-cli php
```

```
sudo apt install composer
```

```
sudo chmod -R 777 .config/composer/
```

```
composer global require cpriego/valet-linux
```

Abra o arquivo:
```
nano ~/.profile
```

* vá na ultima linha, pule uma linha, e cole isso:
```
PATH="$HOME/.config/composer/vendor/bin:$PATH"
```
* aperte ctrl + o, para salvar o arquivo
* aperte enter, para confirmar
* aperte ctrl + x, para sair

```
source .profile
```

```
sudo apt install network-manager libnss3-tools jq xsel
```

```
valet install
```

Na pasta que será o destino dos projetos:
```
valet park
```

Teste:
vá no braser escreva o nome da pasta do petoje + .test
se abrir o seu projeto ele já está funcionando.