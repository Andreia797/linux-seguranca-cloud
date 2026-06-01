# Permissões aplicadas

## Ambiente utilizado
Linux no browser

## Utilizador e grupos
(Adicionar output dos comandos whoami, id e groups)

## Ficheiros criados
- publico.txt: ficheiro de acesso geral
- restrito.txt: ficheiro com acesso limitado
- script.sh: script executável

## Permissões aplicadas

| Ficheiro | Permissão | Justificação |
|---|---|---|
| publico.txt | 644 | permite leitura geral e edição pelo utilizador |
| restrito.txt | 640 | limita acesso apenas ao utilizador e grupo |
| script.sh | u+x | permite execução do script |

## Relação com o princípio do menor privilégio
As permissões foram definidas para garantir que cada utilizador tem apenas o acesso necessário, evitando permissões excessivas e aumentando a segurança do sistema.