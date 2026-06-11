# Superfície de Ataque

## Serviço identificado

Nginx

## Serviços observados

- Nginx
- SSH (quando disponível)

## Portas observadas

- Porta 80 (HTTP)
- Porta 22 (SSH)

## Portas necessárias

- 80 para acesso ao website
- 22 para administração remota segura

## Riscos identificados

1. Exposição desnecessária de serviços.
2. Utilização de permissões incorretas nos ficheiros.
3. Falta de firewall configurada.
4. Atualizações não aplicadas.
5. Exposição acidental de ficheiros sensíveis.

## Medidas iniciais

- Manter apenas serviços necessários ativos.
- Atualizar regularmente o sistema.
- Rever permissões dos ficheiros.
- Utilizar firewall.
- Restringir acessos administrativos.