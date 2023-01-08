## :vulcan_salute: Saudações
Olá! David Camargo aqui. Nos últimos anos tenho desenvolvido um projeto que foi muito além das expectativas iniciais e se tornou um hobby. Compartilho aqui um pouco do que tenho aprendido, espero que possa ser útil e inspire você em seus projetos pessoais :)

## :computer: Desenvolvimento
Workflow surgiu da necessidade de agilizar processos e automatizar tarefas repetitivas. Seu desenvolvimento está organizado em ciclos:

```
♦──────── 2021 ────────♦──────── 2022 ────────♦────────┤ 2023 ├────────♦>
```
### 2021
Inicialmente escrito para o legado Prompt de Comando, o desenvolvimento de Workflow tem início no segundo semestre de 2021 com o que é considerado o _Ciclo Lento de Desenvolvimento_ devido às necessidades de aprendizagem da linguagem shell script, construção do núcleo do software e execução dos primeiros testes. Posteriormente portado para PowerShell 5.1, o algoritmo ganhou um vasto horizonte de possibilidades e compatibilidade.

O universo de Tron criado por Steven Lisberger foi uma clara inspiração na construção do projeto desde as primeiras linhas de código. Há diversos easter eggs espalhados pelo algoritmo e interface das versões iniciais, no entanto elas nunca foram publicadas.

Ao longo do ano a cadência no lançamento de novas versões trouxe funcionalidades e avanços significativos ao software como o suporte ao PowerShell 7.0 e à codificação de caracteres [UTF8NoBom](https://docs.microsoft.com/pt-br/powershell/module/microsoft.powershell.core/about/about_character_encoding), atualização de elementos da interface, alteração para o formato de versionamento [CalVer](https://calver.org/) a fim de simplificar o controle de versões, suporte ao 7-Zip para a compactação de dados, e a escolha de uma licença de software livre.

```
                 21.1.1-001                                             21.001.1
SemVer ───────────┬─┬─┬──┬                             CalVer ──────────┬──┬──┬
                  │ │ │  └┤ Build                                       │  │  └─┤ Build
                  │ │ └───┤ Correções                                   │  └────┤ Dia absoluto do ano
                  │ └─────┤ Alterações                                  └───────┤ Ano
                  └───────┤ Recursos
```

### 2022
Após seis meses de desenvolvimento, Workflow deixou de ser um software restrito e ganhou um repositório no GitHub, sendo publicado sob a GPL-3.0.

A partir de então iniciou-se um importante período de transição e implementação conhecido como _Ciclo Rápido de Desenvolvimento_, onde a refatoração constante do código possibilitado pelo lançamento de novas versões com o intervalo de apenas dez dias aplicou os conceitos da filosofia [Clean Code](https://blog.betrybe.com/tecnologia/clean-code/) e da metodologia ágil [Extreme Programming](https://www.devmedia.com.br/extreme-programming-conceitos-e-praticas/1498) para aprimorar a qualidade do algoritmo e introduzir novos recursos, entre eles o Registro de Eventos, Instalação e Atualização automáticas a partir do repositório, e a Verificação de Integridade que detecta e corrige alterações ilegais de algoritmo, recursos estes que permitem maior controle, segurança, velocidade e confiabilidade na entrega atualizações.

A interface recebeu refinamentos através de duas grandes versões que atualizaram os elementos existentes e adicionaram temas. Os fundamentos instituídos pelas Diretrizes de Interface determinaramm intuitividade, unidade e minimalismo como alguns dos requisitos da experiência do usuário. Tendo em mente que uma [CLI](https://blog.betrybe.com/tecnologia/tudo-sobre-cli/) está limitada às possiblidades do terminal que a executa, é importante criar seus próprios elementos, fluxos e estudar a palheta de cores legível pelo terminal a fim de criar um layout consistente e agradável. "_Design não é apenas aparência, design é sobre como as coisas funcionam._" - Steve Jobs.

Para elevar o nível do projeto, o arquivo Readme no formato TXT presente no pacote de software foi substituído por uma versão interativa no formato HTML/CSS com links, layout e palheta de cores compatível com a do software.

### 2023
Neste ano, Workflow receberá aprimoramentos nos elementos, fluxos e conceitos já introduzidos, e expandirá a disponibilidade de recursos mantendo sua arquitetura [monolítica-modular](https://youtu.be/CsrHHHPHKwE). Monólitos são convenientes por facilitar a sobrecarga cognitiva de gerenciamento de código e favorecer a velocidade de desenvolvimento, depuração, teste, implementação e execução.

O que está por vir:
- Porte do código-fonte para EN-US
- Simplificação da habilitação de recursos
- Overview da rotina de backup
- Simplificação dos módulos de backup
- Replicação de dados de backup
- Configuração da taxa de compressão de dados
- Criação de fluxos complexos
- Importação e exportação de configurações

Para saber mais sobre a evolução de Workflow [aqui](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md).

## :zap: Ferramentas
- [PowerShell](https://github.com/powershell/powershell)
- [Terminal](https://github.com/microsoft/terminal)
- [VS Code](https://github.com/microsoft/vscode)
- [7-Zip](https://7-zip.org)
- [LibreOffice](https://libreoffice.org)
- [GIMP](https://gimp.org)
- [Unsplash](https://unsplash.com)
