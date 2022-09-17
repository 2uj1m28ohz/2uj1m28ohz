## :vulcan_salute: Saudações
Olá, me chamo David Camargo e nos últimos 12 meses dei vida a um projeto pessoal que tem estimulado meu aprendizado em diversas ferramentas e temas. Compartilho aqui o que tenho aprendido recentemente. Espero que isso possa ser útil e inspire outros em seus projetos pessoais :)

## :computer: Desenvolvimento
Workflow surgiu da necessidade de agilizar processos e automatizar tarefas repetitivas do cotidiano. Seu desenvolvimento está divido em quatro ciclos:

```
├─ SystemMaintenance ─ Tron ─┬─ Autopilot ─┬─ Workflow >
                             ├─ Launchpad ─┤
                             └─ FlySafe ───┘
```

### Ciclo 1
Inicialmente nomeado como `SystemMaintenance` e escrito para o legado Prompt de Comando, o projeto tem início com o que é considerado o *Ciclo Lento de Desenvolvimento* devido às necessidades de compreensão da linguagem shell script, construção do núcleo do software e testes extensos. Posteriormente SystemMaintenance foi portado para PowerShell 5.1 e as versões legadas foram descartadas.

### Ciclo 2
Você deve ter percebido que durante o segundo ciclo, Workflow foi nomeado como `Tron`. O universo criado por Steven Lisberger foi uma clara inspiração para este projeto desde as primeiras linhas de código. Há diversos easter eggs espalhados pelo algoritmo e interface das versões criadas durante os dois primeiros ciclos de desenvolvimento, no entanto elas nunca foram publicadas.

Este ciclo manteve a cadência na implementação de novas funcionalidades e trouxe avanços significativos ao software como o suporte ao PowerShell 7.0 e à codificação de caracteres [UTF8NoBom](https://docs.microsoft.com/pt-br/powershell/module/microsoft.powershell.core/about/about_character_encoding), atualização de elementos da interface, alteração para o formato de versionamento [CalVer](https://calver.org/) para simplificar o controle de versões, suporte ao 7-Zip para a compactação de dados, e a escolha de uma licença de software livre.

```
22.100.1
─┬ ─┬─ ┬
 │  │  └─┤ Build
 │  └────┤ Dia do Ano
 └───────┤ Ano
```

### Ciclo 3
O terceiro ciclo foi um importante período de transição para o lançamento do então renomeado `Autopilot` junto de um arquivo README interativo no formato HTML/CSS e da GPL-3.0. Dois novos softwares derivaram de Autopilot: Launchpad e FlySafe. O primeiro escrito para empacotar softwares, e o segundo exclusivo para gerenciar o backup de EVE Online. Sim, todos tiveram nomes inspirados na temática espacial. *Elon Musk, estou olhando pra você!*

Progressivamente o desenvolvimento de Launchpad e FlySafe foi reduzido até ambos serem descontinuados e suas funcionalidades absorvidas por Autopilot. Aqui tem início o que é considerado o *Ciclo Rápido de Desenvolvimento*, quando a refatoração do código era constante e novas versões lançadas com o intervalo de apenas dez dias trouxeram novos recursos, aplicando os conceitos da filosofia [Clean Code](https://blog.betrybe.com/tecnologia/clean-code/) e da metodologia ágil [Extreme Programming](https://www.devmedia.com.br/extreme-programming-conceitos-e-praticas/1498).

Funcionalidades como o Registro de Eventos e os módulos de Instalação e Atualização automáticas foram introduzidos no núcleo de Autopilot para permitir maior controle, velocidade e confiabilidade na entrega de correções, otimizações e novos recursos, além de aumentar gradualmente os requisitos de sistema para garantir a compatibilidade e a segurança do algoritmo.

Os fundamentos instituídos pelas Diretrizes de Interface determinam intuitividade, unidade e minimalismo como alguns dos requisitos da experiência do usuário. Uma [CLI](https://blog.betrybe.com/tecnologia/tudo-sobre-cli/) está limitada às possiblidades do terminal que a executa, por isso é importante criar seus próprios elementos, fluxos e estudar a palheta de cores legível pelo terminal a fim de criar um layout consistente e agradável. "*Design não é apenas aparência, design é sobre como as coisas funcionam.*" - Steve Jobs.

### Ciclo 4
No ciclo atual `Workflow` tem o objetivo de aprimorar elementos, fluxos e conceitos já introduzidos, e expandir a disponibilidade de recursos mantendo sua arquitetura [monolítica-modular](https://youtu.be/CsrHHHPHKwE). Os monólitos são convenientes por facilitar a sobrecarga cognitiva de gerenciamento de código e favorecer a velocidade de desenvolvimento, depuração, teste, implementação e execução.

Você pode saber mais sobre a evolução de Workflow [aqui](https://github.com/2uj1m28ohz/workflow/blob/main/Evolution.md).

## :gem: Softwares[^1]
|Nome|Desenvolvimento|Suporte|Estado|
|:---:|:---:|:---:|:---:|
|[Workflow](https://github.com/2uj1m28ohz/workflow)|Ativo|Ativo|Evoluindo|
|[Launchpad](https://github.com/2uj1m28ohz/launchpad)|Encerrado|Encerrado|Legado|
|[Autopilot](https://github.com/2uj1m28ohz/autopilot)|Encerrado|Encerrado|Legado|
|[FlySafe](https://github.com/2uj1m28ohz/flysafe)|Encerrado|Encerrado|Legado|
> **NOTA:** Verifique a Política de Suporte disponível nos repositórios.

## :rocket: Aplicativos e Sites
Aplicativos e sites utilizados no processo de desenvolvimento:
- [PowerShell](https://github.com/powershell/powershell)
- [Terminal](https://github.com/microsoft/terminal)
- [VS Code](https://github.com/microsoft/vscode)
- [7-Zip](https://7-zip.org)
- [LibreOffice](https://libreoffice.org)
- [GIMP](https://gimp.org)
- [Unsplash](https://unsplash.com)[^2]

[^1]:Desenvolvidos com :purple_heart: por David Camargo
[^2]:Imagem por [Chong Wei](https://unsplash.com/photos/oMcTmNHclZI)
