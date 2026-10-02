# Atividade 01

## Questão (1) Qual seria sua estratégia para identificar as versões? Justifique.

Seria seguindo a estratégia de Versionamento Semântico. Gera maior controle e gerenciamento quanto às diferentes atualizações e seus respectivos "pesos" na importância e individualização do projeto.

## Questão (2) Como nomearia a primeira versão para o público?

Utilizando o versionamento nominal. Utilizaria algum termo ou ideia que refletisse o caráter do produto. Também sendo possível adicionar um versionamento semântico simbólico, como: "1.0.0".

## Questão (3) Após liberado o projeto, uma nova funcionalidade foi requisitada e implementada. Como nomearia esta nova versão?

1.1.0, caso a funcionalidade se enquadrasse como uma "atualização de nível menor".

## Questão (4) Considerando a sequência anterior com o esquema de versionamento SemVer. Como ficaria o histórico de versões?

ficaria: <br>
    Versão 1: 1.0.0 <br>
    Versão 2: 1.1.0

## Questão (5) A partir da versão indicada antes, uma série de 3 correções, seguida por duas funcionalidades compatíveis com a versão atual e mais outras 2 correções foram publicadas em série. Qual seria a versão mais recente?

A versão mais recente seria a: 1.3.2

## Questão (6) Uma versão nova exigiu mudanças críticas na API, foi lançada e na sequências houveram três novas versões: uma com adição de funcionalidades, seguidas de 2 com correções de bugs. Como fica o histórico?

histórico (levando em consideração a versão anterior):<br>
    - Mudança crítica na API: 2.0.0 <br>
    - Adição de funcionalidades: 2.1.0 <br>
    - Correções de bugs: 2.1.1 e 2.1.2

## Questão (7) Pesquise exemplos representativos de versões reais de software considerando cada um dos termos apontados.

| Termo | Notação da aula | Exemplo real | O que mostra |
|---|---|---|---|
| Alpha | -a.X | Python 3.12.0a1; Bootstrap 5.0.0-alpha1 | Testes iniciais, ainda instável e feito perto da equipe |
| Beta | -b.X | Python 3.12.0b1; Bootstrap 5.0.0-beta1 | Funcionalidades fechadas, aberto a testes de usuários externos |
| Release Candidate | -rc | Python 3.12.0rc1; Bootstrap 5.0.0-rc1 | Candidata a versão final: só entram correções de bugs críticos |
| Release | sem letras | Python 3.12.0; Bootstrap 5.0.0 | Lançamento oficial ao público |
| Post-release fixes | sem letras, Patch > 0 | Python 3.12.1, 3.12.2; Node.js 20.11.1 | Correções publicadas depois do lançamento, mantendo a compatibilidade |
| LTS | sufixo "LTS" | Ubuntu 24.04 LTS; Node.js 20 (Iron); Java 17 e 21 | Suporte garantido por mais tempo que as versões regulares |