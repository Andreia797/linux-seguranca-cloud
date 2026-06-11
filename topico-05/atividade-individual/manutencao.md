# Manutenção Preventiva

## Objetivo

Garantir a disponibilidade e estabilidade do sistema através de ações regulares de manutenção.

## Atividades recomendadas

- Verificar utilização de memória.
- Verificar espaço disponível em disco.
- Consultar logs do sistema.
- Confirmar estado dos serviços.
- Atualizar pacotes do sistema.

## Comandos úteis

```bash
uptime
free -h
df -h
systemctl status nginx
journalctl -n 20
```

## Benefícios

A manutenção preventiva reduz falhas inesperadas e melhora a disponibilidade dos serviços.