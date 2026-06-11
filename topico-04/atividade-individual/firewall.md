# Firewall

## Estado observado

A firewall UFW encontra-se ativa.

## Regras recomendadas

Permitir HTTP:

```bash
sudo ufw allow 80/tcp
```

Permitir SSH:

```bash
sudo ufw allow 22/tcp
```

Ativar firewall:

```bash
sudo ufw enable
```

## Comando utilizado:

``` bash
sudo ufw status
```
## Resultado observado:

-Porta 22 (SSH) permitida.
-Porta 80 (HTTP) permitida.
-Firewall ativa.

## Objetivo

Permitir apenas os serviços necessários ao funcionamento do servidor e reduzir a superfície de ataque.

## Observação

A firewall foi configurada para permitir apenas os serviços essenciais à administração e publicação do serviço web. Esta abordagem segue o princípio da minimização da superfície de ataque, permitindo apenas as portas necessárias ao funcionamento do sistema.