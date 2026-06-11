# Continuidade Operacional

## Serviço crítico

Nginx

## Ficheiros importantes

- index.html
- ficheiros do website
- configurações do Nginx

## Logs importantes

- journalctl
- logs do Nginx

## Periodicidade de backup

Backup semanal.

## Procedimento de recuperação

1. Restaurar backup.
2. Verificar integridade dos ficheiros.
3. Reiniciar o serviço Nginx.
4. Testar acesso ao website.

## Critérios de validação

- Serviço ativo.
- Ficheiros restaurados.
- Website acessível.
- Ausência de erros nos logs.