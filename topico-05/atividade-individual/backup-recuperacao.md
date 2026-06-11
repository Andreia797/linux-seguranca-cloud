# Backup e Recuperação

## Diretório identificado

site-teste

## Criação do backup

```bash
tar -czf backup-site.tar.gz site-teste
```

## Recuperação

```bash
tar -xzf backup-site.tar.gz -C recuperacao
```

## Resultado

Os ficheiros foram recuperados com sucesso na pasta de recuperação.

## Validação

Foi confirmada a existência dos ficheiros após a recuperação.