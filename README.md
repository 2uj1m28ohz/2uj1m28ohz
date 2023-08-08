## :vulcan_salute: Saudações
Olá! Nos últimos anos tenho desenvolvido um projeto que foi muito além das expectativas iniciais e se tornou um hobby. Compartilho aqui um pouco do que tenho aprendido, espero que possa ser útil e inspire você em seus projetos pessoais :)

## :computer: Desenvolvimento
Workflow surgiu da necessidade de agilizar processos e automatizar tarefas repetitivas. Seu desenvolvimento está organizado em ciclos:

```
2021 ──────────── › 2022 ──────────── › 2023 ─ ─ ─ ────── ›
```
### 2021
Inicialmente escrito para o legado Prompt de Comando, o desenvolvimento de Workflow tem início no segundo semestre de 2021 com o _Ciclo Lento de Desenvolvimento_, período de aprendizagem da linguagem shell script, construção do núcleo do software e execução dos primeiros testes. Posteriormente portado para PowerShell 5.1, o algoritmo ganhou em complexidade e compatibilidade.

O universo de Tron criado por Steven Lisberger foi uma clara inspiração na construção do projeto desde as primeiras linhas de código. Há diversos easter eggs espalhados pelo algoritmo e interface das versões iniciais, no entanto elas nunca foram publicadas.

Ao longo do ano, a cadência no lançamento de novas versões trouxe funcionalidades e avanços significativos ao software como o suporte ao PowerShell 7.0 e a codificação de caracteres [UTF8NoBom](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md), atualização de elementos da interface, migração para o formato de versionamento [CalVer](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md), suporte à compressão de dados, e a escolha de uma licença de software livre.

```
                           21.1.1-001                                      21.001.1
────────── SemVer ──────────┬─┬─┬──┬──────────────────── › CalVer ──────────┬──┬──┬──────────────────── ›
                            │ │ │  └─┤ Revisão                              │  │  └─┤ Revisão
                            │ │ └────┤ Correções                            │  └────┤ Dia absoluto do ano
                            │ └──────┤ Alterações                           └───────┤ Ano
                            └────────┤ Recursos
```

### 2022
Após seis meses de desenvolvimento, Workflow deixou de ser um software restrito e ganhou um repositório no GitHub, sendo publicado sob a GPL-3.0.

A partir de então iniciou-se um importante período de transição e implementação conhecido como _Ciclo Rápido de Desenvolvimento_, onde a refatoração constante do código possibilitado pelo lançamento de novas versões com o intervalo de apenas dez dias aplicou os conceitos da filosofia [Clean Code](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md) e da metodologia ágil [Extreme Programming](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md) para aprimorar a qualidade do algoritmo e introduzir novos recursos, entre eles o Registro de Eventos, instalação e atualização automáticas a partir do repositório, e a Verificação de Integridade que detecta e corrige alterações ilegais de algoritmo, recursos estes que permitem maior controle, segurança, velocidade e confiabilidade na entrega atualizações.

A interface recebeu refinamentos através de duas grandes versões que atualizaram os elementos existentes e adicionaram temas. Os fundamentos instituídos pelas Diretrizes de Interface determinam intuitividade, unidade e minimalismo como alguns dos requisitos da experiência do usuário. Tendo em mente que uma [CLI](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md) está limitada às possiblidades do terminal que a executa, é importante criar seus próprios elementos, fluxos e estudar a palheta de cores legível pelo terminal a fim de criar um layout consistente e agradável. "_Design não é apenas aparência, design é sobre como as coisas funcionam._" - Steve Jobs.

Para elevar o nível do projeto, o arquivo Readme no formato TXT presente no pacote de software foi substituído pelo formato HTML/CSS com links, layout e palheta de cores compatível com a do software.

### 2023
No _Ciclo Estável de Desenvolvimento_ Workflow receberá aprimoramentos nos elementos, fluxos e conceitos já introduzidos, e expandirá a disponibilidade de recursos enquanto mantém sua [Arquitetura Monolítica](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md). De forma geral, monólitos são convenientes por facilitar a sobrecarga cognitiva de gerenciamento de código e favorecer a velocidade de todas as etapas do software, do desenvolvimento à execução. Esse ano estabelece ainda o [Scrum](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md) como o novo método ágil utilizado para o desenvolvimento das futuras versões, permitindo um intervalo de planejamento maior e atualizações ainda mais sólidas.

Nos últimos anos, foi realizado um trabalho importante e fundamental que nos permitiu chegar até aqui: um software robusto e inteligente. Abaixo, o roadmap desse ano:

|Status|Tópico|Alteração|
|:---:|:---|:---|
|:green_circle:|Geral|Porte do código-fonte para EN-US|
|:green_circle:|Geral|Carregamento do software a partir da home do usuário|
|:green_circle:|Backup|Overview da rotina de backup|
|:black_circle:|Backup|Notificação de incompatibilidade|
|:green_circle:|Backup|Unificação de funcionalidades|
|:green_circle:|Backup|Suporte ao Google Drive|
|:yellow_circle:|Backup|Suporte ao iCloud Drive|
|:green_circle:|Backup|Suporte a multidispositivos|
|:green_circle:|Backup|Suporte a multiusuários|
|:green_circle:|Backup|Período de retenção|
|:yellow_circle:|Backup|Replicação de dados|
|:green_circle:|Backup|Verificação da saúde do drive de backup|
|:green_circle:|Backup|Suporte à tabela de partições GPT no drive de backup|
|:green_circle:|Backup|Suporte ao sistema de arquivos NTFS no drive de backup|
|:green_circle:|Backup|Suporte à clusters de 64KB no drive de backup|
|:green_circle:|Compressão|Configuração da taxa de compressão de dados|
|:orange_circle:|Compressão|Redução do uso de memória|
|:green_circle:|Compressão|Configuração do uso de memória|
|:green_circle:|Compressão|Suporte ao modo sólido|
|:green_circle:|Compressão|Suporte ao processamento multithread|
|:green_circle:|Compressão|Exportação do log de compressão de dados|
||Manutenção|Gerenciamento de Pontos de Restauração|
||Fluxos|Execução de funcionalidades em fluxos automáticos e configuráveis|
|:green_circle:|Configurações|Gerenciamento inteligente de recursos|
|:green_circle:|Configurações|Importação e exportação de configurações|
|:green_circle:|Segurança|Bloqueio de software em caso de comprometimento de integridade|

> - :green_circle: Recurso habilitado
> - :yellow_circle: Recurso em desenvolvimento
> - :orange_circle: Recurso substituído
> - :red_circle: Recurso cancelado
> - :purple_circle: Recurso postergado
> - :large_blue_circle: Recurso desabilitado
> - :black_circle: Recurso removido

Saiba mais sobre a evolução de Workflow [aqui](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md).

## :zap: Ferramentas
- [PowerShell](https://github.com/powershell/powershell)
- [Terminal](https://github.com/microsoft/terminal)
- [VS Code](https://github.com/microsoft/vscode)
- [7-Zip](https://7-zip.org)
- [LibreOffice](https://libreoffice.org)
- [GIMP](https://gimp.org)
- [Unsplash](https://unsplash.com)
- [ChatGPT](https://chat.openai.com)
