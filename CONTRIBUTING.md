# Como o repositório é mantido

O Study Hub é um repositório individual. Este documento descreve o fluxo de trabalho usado nele, para que o processo seja repetível.

## Fluxo de trabalho

1. Criar uma branch a partir da `main`, com nome curto e descritivo (`docs/readme-oac`, `feat/pagina-projetos`).
2. Fazer commits pequenos, com mensagem no imperativo explicando o que mudou e por quê.
3. Abrir um pull request para a `main` e revisar o diff antes de mesclar.
4. Mesclar e apagar a branch.

A `main` aceita apenas commits novos: force-push e exclusão estão bloqueados pelo ruleset do repositório.

## Estrutura

Siga o padrão número + snake_case descrito no [README](README.md). Cada disciplina em `02_Disciplinas_Atuais/` tem as subpastas `Atividades_e_Entregas/` e `Anotacoes_e_Resumos/`.

## Sugestões e correções

Abra uma issue descrevendo o problema ou a sugestão. Para falhas de segurança, veja o [SECURITY.md](SECURITY.md).
