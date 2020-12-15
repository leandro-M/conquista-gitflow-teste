# Comandos Git Flow
- Iniciar: `git flow init`
- Versão: x.y.z
    - x -> altera com mudança brusca de código
    - y -> altera a cada release
    - z -> altera a cada bugfix

- Sugestão de padrão de commits:
    - Feature: feature(nome_da_feature): descricão do commit
    - Bugfix: bugFix(nome_do_bug): descrição do commit
    - HotFix: hotFix(nome_do_bug): descrição do commit

- Comandos Git Flow
    - Nova feature: `git flow feature nome_da_feature`
    - Publicar a feature: `git flow feature finish MYFEATURE`
    - Criar uma nova versão: `git flow release start RELEASE`
    - Push da versão: `git flow release publish RELEASE`
    - Publicar uma versão: `git flow release finish RELEASE`

