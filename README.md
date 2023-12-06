## :vulcan_salute: Saudações
Olá! Nos últimos anos tenho desenvolvido um projeto que foi muito além das expectativas iniciais e se tornou um hobby. Compartilho aqui um pouco do que tenho aprendido, espero que possa ser útil e inspire você em seus projetos pessoais :)

## :computer: Desenvolvimento
Workflow surgiu da necessidade de agilizar processos e automatizar tarefas repetitivas. Seu desenvolvimento está organizado em ciclos:

|2021|2022|2023|2024|
|:---:|:---:|:---:|:---:|
|Alpha|Beta|Gama|Delta|

<details>
<summary>Ciclo Alpha</summary>

Inicialmente escrito para o legado Prompt de Comando, o desenvolvimento de Workflow tem início no segundo semestre de 2021 com o _Ciclo Alpha_, período de aprendizagem da linguagem shell script, construção do núcleo do software e execução dos primeiros testes. Posteriormente portado para PowerShell 5.1, o algoritmo ganhou em complexidade e compatibilidade.

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

</details>

<details>
<summary>Ciclo Beta</summary>

Após seis meses de desenvolvimento, Workflow deixou de ser um software restrito e ganhou um repositório no GitHub, sendo publicado sob a GPL-3.0.

A partir de então iniciou-se um importante período de transição e implementação conhecido como _Ciclo Beta_, onde a refatoração constante do código possibilitado pelo lançamento de novas versões com o intervalo de apenas dez dias aplicou os conceitos da filosofia [Clean Code](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md) e da metodologia ágil [Extreme Programming](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md) para aprimorar a qualidade do algoritmo e introduzir novos recursos, entre eles o Registro de Eventos, instalação e atualização automáticas a partir do repositório, e a Verificação de Integridade que detecta e corrige alterações ilegais de algoritmo, recursos estes que permitem maior controle, segurança, velocidade e confiabilidade na entrega atualizações.

A interface recebeu refinamentos através de duas grandes versões que atualizaram os elementos existentes e adicionaram temas. Os fundamentos instituídos pelas Diretrizes de Interface determinam intuitividade, unidade e minimalismo como alguns dos requisitos da experiência do usuário. Tendo em mente que uma [CLI](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md) está limitada às possiblidades do terminal que a executa, é importante criar seus próprios elementos, fluxos e estudar a palheta de cores legível pelo terminal a fim de criar um layout consistente e agradável. "_Design não é apenas aparência, design é sobre como as coisas funcionam._" - Steve Jobs.

Para elevar o nível do projeto, o arquivo Readme no formato TXT presente no pacote de software foi substituído pelo formato HTML/CSS com links, layout e palheta de cores compatível com a do software.

</details>

### Ciclo Gama
Gama foi um importante ciclo de amadurecimento de software, quando dezenas de novos recursos conduziram Workflow à um nível de qualidade nunca antes visto, potencializado pela adocação da metodologia ágil [Scrum](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md) que proporcionou um intervalo de planejamento maior e atualizações ainda mais sólidas. Algumas das principais alterações incluem:

- Geral
    - Porte do código-fonte para EN-US
    - Carregamento do software a partir da home do usuário

- Backup
    - Unificação das rotinas de backup
    - Overview da rotina de backup
    - Estimativa do tamanho do backup
    - Suporte ao Google Drive
    - Suporte ao iCloud Drive
    - Suporte ao Dropbox
    - Suporte a multidispositivos
    - Suporte a multiusuários
    - Configuração do período de retenção
    - Verificação da saúde do drive de backup
    - Suporte à tabela de partições GPT no drive de backup
    - Suporte ao sistema de arquivos NTFS no drive de backup
    - Suporte à clusters de 64KB no drive de backup
    - Exibe o tempo total de execução

- Réplica
    - Replicação do backup de dados
    - Verificação da saúde do drive de réplica
    - Suporte à tabela de partições GPT no drive de réplica
    - Suporte ao sistema de arquivos NTFS no drive de réplica
    - Suporte à clusters de 64KB no drive de réplica
    - Exibe o tempo total de execução

- Compressão
    - Configuração da taxa de compressão de dados
    - Configuração do uso de memória
    - Suporte ao modo sólido
    - Suporte ao processamento multithread

- Configurações
    - Gerenciamento inteligente de configurações
    - Importação e exportação de configurações
    - Bloqueio e reinstalação de software em caso de comprometimento de integridade

<details>
<summary>Ciclo Delta</summary>

No _Ciclo Delta_ Workflow receberá aprimoramentos nos elementos, fluxos e conceitos já introduzidos, e expandirá a disponibilidade de recursos enquanto mantém sua [Arquitetura Monolítica](https://github.com/2uj1m28ohz/2uj1m28ohz/blob/main/Topics.md). De forma geral, monólitos são convenientes por facilitar a sobrecarga cognitiva de gerenciamento de código e favorecer a velocidade de todas as etapas do software, do desenvolvimento à execução.

Os ciclos anteriores foram fundamentais na construção de um software robusto e inteligente. Não será diferente em 2024. Saiba mais sobre a [evolução](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md) de Workflow.

</details>

## :zap: Tecnologias
- [PowerShell](https://github.com/powershell/powershell)
- [Terminal](https://github.com/microsoft/terminal)
- [VS Code](https://github.com/microsoft/vscode)
- [7-Zip](https://7-zip.org)
- [LibreOffice](https://libreoffice.org)
- [GIMP](https://gimp.org)
- [Unsplash](https://unsplash.com)
- [ChatGPT](https://chat.openai.com)
