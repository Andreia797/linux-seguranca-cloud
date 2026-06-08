# Publicação do site

## Nível escolhido
Nível 2 - Intermédio

## Rota escolhida
Nginx

## Ficheiros criados

- index.html
- sobre.html
- style.css

## Local de publicação

/var/www/html/topico-03/

## Comandos principais utilizados

```bash
sudo apt install nginx -y
sudo systemctl start nginx
cp index.html /var/www/html/topico-03/
cp sobre.html /var/www/html/topico-03/
cp style.css /var/www/html/topico-03/
```

## Resultado obtido

O site foi publicado com sucesso através do servidor web Nginx e ficou acessível através do navegador.

## Limitações encontradas

Foram encontradas pequenas dificuldades iniciais na configuração do ambiente Linux.