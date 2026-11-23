# Contrato de trabalho do repositório `.github`

Este repositório é público e controla o perfil visível da organização e os
arquivos que o GitHub pode herdar nativamente.

- Trate todo conteúdo como publicação externa.
- Não cite repositório privado, incidente, infraestrutura interna, pessoa,
  credencial ou dado operacional sem autorização explícita.
- Templates e padrões herdáveis devem ser compatíveis com toda a organização.
- Governança executável e inteligência interna pertencem aos repositórios
  privados apropriados; aqui fica somente o que precisa ser público ou herdado
  pelo GitHub.

## Specs e ADRs antes de começar (obrigatório)

Este repositório é **público** e seus arquivos de comunidade e o perfil valem para **todos os repositórios** da organização que não têm o próprio. Por isso:

- **Mudança em arquivo herdável** (o perfil em `profile/` e qualquer arquivo de comunidade ou template que for acrescentado aqui) começa por **spec**, e por **ADR** quando há alternativas reais, antes de qualquer edição. A spec e o ADR ficam no repositório privado de governança da organização, não aqui, porque a escrita pode citar repositórios, pessoas ou incidentes internos. Este repositório não recebe `docs/specs/` nem `docs/adr/`.
- **Antes de alterar, confira o efeito:** um arquivo herdado chega a repositórios que têm o próprio e a repositórios que não têm. Diga no PR quais perfis de repositório mudam de comportamento.
- **O PR não pode citar** repositório privado, issue interna, incidente ou pessoa. Descreva o motivo em termos públicos.
- **Reaproveitar antes de criar** e **cor só por token** não se aplicam: este repositório não tem código de interface.
- **Issue e PR** seguem o padrão da organização: começam pelo **ELI5**, entram no Project 1 e procuram issue existente (abertas e fechadas) antes de abrir outra.
- **Specs e ADRs numerados** não existem aqui. Se aparecerem, não renomeie sem corrigir todas as referências no mesmo PR.
