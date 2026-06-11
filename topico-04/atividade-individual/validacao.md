# Validação

## Testes realizados

### Serviço Nginx

```bash
systemctl status nginx
```

Resultado esperado:

Serviço ativo (active/running).

### Portas

```bash
ss -tuln
```

Resultado esperado:

Porta 80 visível.

### Firewall

```bash
ufw status
```

Resultado esperado:

Firewall identificada e respetivo estado documentado.

### Endereço IP

```bash
hostname -I
```

Resultado esperado:

IP do servidor apresentado.

### Teste HTTP

```bash
curl localhost
```

Resultado esperado:

Página padrão do Nginx contendo a mensagem:

Welcome to nginx!

## Conclusão

O serviço web manteve-se funcional após a análise e a identificação das medidas iniciais de segurança.