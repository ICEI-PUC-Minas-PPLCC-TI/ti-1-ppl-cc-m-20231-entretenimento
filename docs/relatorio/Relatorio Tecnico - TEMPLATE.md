# Informações do Projeto
`Aprimoramento da revenda de ingressos`  

`Ciência da Computação` 

## Participantes

 Os membros do grupo são: 
- Henrique Resende Lara
- Guilherme Tavares Nogueira de Abreu
- Lucas Nascimento Gomes
- Sofia Melo do Prado Rocha Duque
- Tarcísio Ferraz Justa Silva

# Estrutura do Documento

- [Informações do Projeto](#informações-do-projeto)
  - [Participantes](#participantes)
- [Estrutura do Documento](#estrutura-do-documento)
- [Introdução](#introdução)
  - [Problema](#problema)
  - [Objetivos](#objetivos)
  - [Justificativa](#justificativa)
  - [Público-Alvo](#público-alvo)
- [Especificações do Projeto](#especificações-do-projeto)
  - [Personas, Empatia e Proposta de Valor](#personas-empatia-e-proposta-de-valor)
  - [Histórias de Usuários](#histórias-de-usuários)
  - [Requisitos](#requisitos)
    - [Requisitos Funcionais](#requisitos-funcionais)
    - [Requisitos não Funcionais](#requisitos-não-funcionais)
  - [Restrições](#restrições)
- [Projeto de Interface](#projeto-de-interface)
  - [User Flow](#user-flow)
  - [Wireframes](#wireframes)
- [Metodologia](#metodologia)
  - [Divisão de Papéis](#divisão-de-papéis)
  - [Ferramentas](#ferramentas)
  - [Controle de Versão](#controle-de-versão)
- [**############## SPRINT 1 ACABA AQUI #############**](#-sprint-1-acaba-aqui-)
- [Projeto da Solução](#projeto-da-solução)
  - [Tecnologias Utilizadas](#tecnologias-utilizadas)
  - [Arquitetura da solução](#arquitetura-da-solução)
- [Avaliação da Aplicação](#avaliação-da-aplicação)
  - [Plano de Testes](#plano-de-testes)
  - [Ferramentas de Testes (Opcional)](#ferramentas-de-testes-opcional)
  - [Registros de Testes](#registros-de-testes)
- [Referências](#referências)


# Introdução

No contexto da compra e revenda de ingressos, é notável a crescente demanda por informações precisas e imparciais, especialmente diante dos desafios e incertezas enfrentados por compradores e revendedores neste mercado. A obtenção de informações atualizadas e confiáveis sobre eventos, preços, disponibilidade de ingressos e políticas de venda é fundamental para uma tomada de decisão informada.  

No entanto, assim como em outros setores, a disseminação de notícias falsas e a falta de transparência têm se tornado obstáculos significativos na compra e revenda de ingressos. A proliferação de sites e aplicativos de revenda, muitas vezes operando de forma obscura e sem regulamentação adequada, tem gerado preocupações sobre a autenticidade dos ingressos, preços inflacionados, fraudes e a exploração de consumidores desavisados.

Além disso, a concorrência acirrada e a demanda por ingressos para eventos populares têm levado a práticas de revenda questionáveis, como o uso de bots para comprar grandes quantidades de ingressos em questão de segundos, deixando muitos compradores legítimos sem acesso aos ingressos desejados.

Diante desses desafios, torna-se essencial a existência de canais de informação confiáveis e imparciais que forneçam aos compradores e revendedores de ingressos acesso a informações atualizadas e precisas, promovendo a transparência e a equidade no mercado de compra e revenda de ingressos.

## Problema

De acordo com o que está exposto na introdução, o problema que procuramos solucionar são falta de transparência no mercado de compra e revenda de ingressos, a proliferação de sites e aplicativos de revenda sem regulamentação adequada, a autenticidade dos ingressos, preços inflacionados, fraudes e a exploração de consumidores desavisados. 

## Objetivos

O objetivo geral deste trabalho é criar um portal de notícias que ofereça informações imparciais, atualizadas e confiáveis sobre o mercado de compra e revenda de ingressos, com o intuito de fornecer aos usuários ferramentas de fácil uso para tomar decisões informadas e enfrentar os desafios desse mercado.

Como objetivos específicos, destacam-se:

Fornecer informações detalhadas sobre eventos, preços, disponibilidade de ingressos e políticas de venda, de forma imparcial e transparente.
Integrar com fontes confiáveis de informações sobre o mercado de ingressos, como organizadores de eventos, promotores, e órgãos reguladores.
Oferecer funcionalidades que permitam aos usuários interagir por meio de comentários, compartilhamento de informações e avaliação de vendedores, promovendo a transparência e a troca de informações entre os usuários.


## Justificativa

No mercado de compra e revenda de ingressos, os desafios enfrentados pelos compradores e revendedores são evidentes, com práticas questionáveis, falta de transparência e disseminação de informações falsas. A ausência de fontes confiáveis de informações imparciais tem impactado negativamente a experiência dos usuários nesse mercado, resultando em compras equivocadas, preços inflacionados e fraudes.

Diante dessa realidade, a criação de um portal de notícias dedicado ao mercado de ingressos é justificada pela necessidade de fornecer aos usuários informações confiáveis, atualizadas e imparciais, que os auxiliem na tomada de decisões informadas e na superação dos desafios enfrentados nesse mercado.


## Público-Alvo

O público-alvo desta solução são os indivíduos que estão envolvidos na compra e revenda de ingressos para eventos, como shows, esportes, teatro, entre outros. Isso inclui tanto os compradores, que buscam ingressos para eventos específicos, quanto os revendedores, que compram e revendem ingressos com o objetivo de obter lucro.
Em particular, o público-alvo são pessoas com idade entre 18 e 40 anos, que têm interesse em eventos culturais e esportivos, e que utilizam plataformas online para comprar ou vender ingressos. Eles podem ter experiência prévia na compra e revenda de ingressos ou estar iniciando nesse mercado. Eles buscam informações atualizadas e confiáveis sobre os eventos, preços, disponibilidade de ingressos, tendências de mercado, estratégias de compra e venda, entre outros aspectos relacionados à compra e revenda de ingressos. Essas pessoas são ativas nas redes sociais e utilizam a internet como principal fonte de informações e transações para a compra e revenda de ingressos
 
# Especificações do Projeto

Por meio de respostas obtidas com as personas e histórias de usuários abaixo, conseguimos identificar os principais impasses a serem solucionados, bem como as aplicações posteriores que a plataforma virá a oferecer.

## Personas e Proposta de Valor

![image](https://user-images.githubusercontent.com/130320809/232338388-c87ed8e2-7b20-4ca6-9376-ce632c9d3a01.png)

![image](https://user-images.githubusercontent.com/130320809/232334211-3b0b958d-3ad7-4ae9-bd61-6a0c7da4a87a.png)

![image](https://user-images.githubusercontent.com/130320809/232334234-724d7dad-9398-48ce-b5b5-d1a295fd4139.png)

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Rafael Silva | ingressos confiáveis e de preço justo     | não cair em golpes perdendo seu dinheiro           |
|Rafael Silva      | Plataforma para achar tickets de eventos que já foram esgotados             | para poder comprar shows e eventos de artistas em que não tem acesso aos ingressos|
|Marina Castro| menor custo na compra de ingressos| reduzir os gastos de sua família        |
|Marina Castro| encontrar uma maneira de reunir festividades que condizem com seu gosto peculiar  | diminuir sua dificuldade em encontrar eventos do seu estilo      |
|Teresa Costa | encontrar eventos de seu interesse e que reúna as pessoas | Para se conectar com as pessoas com que se relaciona.  |
|Teresa Costa | achar eventos perto de sua localidade  | para sua maior acessibilidade na hora de se lo   |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve fornecer a capacidade de postar tickets.  | ALTA | 
|RF-002| O site deve fornecer a capacidade de comprar tickets.  | ALTA |
|RF-003| O site deve fornecer a capacidade de postar eventos  | ALTA | 
|RF-004| O site deve fornecer a capacidade de avaliar a compra do ticket  | MÉDIA |
|RF-005| O site deve mostrar uma interface de eventos e dar a opção de categorizá-los.  | ALTA | 
|RF-006| O site deve mostrar uma interface com os tickets que estão à venda e permitir categorizá-los.  | ALTA |
|RF-007| O site deve marcar no perfil as datas dos eventos para os quais você comprou ingresso em um calendário.  | ALTA | 
|RF-008| O site deve marcar no perfil as datas dos eventos para os quais você comprou ingresso em um calendário. | BAIXA |
|RF-008| O site deve fornecer informações postadas de cada evento.  | MÉDIA |
|RF-009| O site deve fornecer a capacidade de comentar em cada evento.  | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser publicado em um ambiente acessível publicamente na Internet (Repl.it, GitHub Pages, Heroku) | ALTA | 
|RNF-002| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada | ALTA | 
|RNF-003| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge) | ALTA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 02/07/2023 |
|02| O aplicativo deve se restringir às tecnologias básicas da Web no Frontend  |
|03| A equipe não pode subcontratar o desenvolvimento do trabalho. |

# Projeto de Interface

## User Flow

![image](https://user-images.githubusercontent.com/130320809/232335242-75ee22be-6dec-42b8-a92e-3a6e85dc0f5d.png)

## Wireframes

### Cabeçalho

![image](https://user-images.githubusercontent.com/130320809/232334661-5e9136e4-055a-402e-b9fd-9304551feb32.png)

O cabeçalho trará a opção de entrar em outras 5 páginas em ordem:PÁGINA DE POSTS DE EVENTOS,POST DE TICKET,CADASTRO DE TICKET,CADASTRO DE EVENTO,PERFIL.

### Página de posts de eventos

![image](https://user-images.githubusercontent.com/130320809/232334619-47742d68-2af3-4abb-9682-fe6b83c3a33b.png)

Nessa página será mostrado os eventos que foram cadastrados no nosso site através de uma imagem e uma descrição do evento além de um carrossel com imagens em destaques.Ao clicar em um evento você será levado à PÁGINA DE AVALIAÇÃO DE EVENTOS.

### Cadastro de Ticket

![image](https://user-images.githubusercontent.com/130320809/232334811-b4023ccf-5119-494a-81b5-abc17056056d.png)

Nessa página serão cadastrados as informações do ticket como a quantidade que será vendida o evento e o local do evento e checar a validade do QR code. 

### Página de avaliação de eventos

![image](https://user-images.githubusercontent.com/130320809/232334882-f86551d1-979b-4daf-b951-49d307f20eb8.png)

Ao clicar em um evento uma página com um carrossel com as imagens do evento será fornecida juntamente com sua avaliação e oportunidade de avaliar o evento.Juntamente com uma página de comentários onde outros comentários podem ser mostrados e adicionados.Ao clicar em ingressos você será levado a página POST DE TICKET.

### Post de tickets

![image](https://user-images.githubusercontent.com/130320809/232334943-9b565857-eb4c-4384-9a43-adcac50a674c.png)

Nessa página será mostrada uma lista com todos os tickets que foram cadastrados anteriormente no site. ao clicar em um ticket você será levado a página COMPRA DE TICKET

### Perfil

![image](https://user-images.githubusercontent.com/130320809/232335000-a260f35f-c29a-4b4a-a338-aace91468c66.png)

A página de perfil mostrará uma foto de perfil e uma foto escolhida pelo usuário um calendário com as datas de validação dos tickets e acesso a uma carteira de tickets 

### Login e cadastro

![image](https://user-images.githubusercontent.com/130320809/232335077-bb023b80-f66f-4e96-be10-bf61b057cb04.png)

A página inicial do site ao entrar nela você terá a opção de logar ou se cadastrar clicando no botão de cadastro, na página de cadastro você pode criar sua conta com as seguintes informações:email,login,senha e o tipo de conta que podem ser normal ou de revendedor. 

### Cadastro de evento

![image](https://user-images.githubusercontent.com/130320809/232335143-107b9aa0-53fb-4c64-a1de-b4bd2ef1db63.png)

Ao entrar na página de cadastrar um evento você poderá fornecer as seguintes informações: nome, local, imagens e uma breve descrição do evento. Ao clicar em postar vc será levado à PÁGINA DE AVALIAÇÃO DE EVENTOS com  as informações cadastradas.

# Metodologia

De maneira geral utilizamos o WhatsApp como meio de comunicação para informações gerais, e estabelecimento de datas e horários para próximas reuniões, como também para cumprir prazos de tarefas. O processo de design thinking foi feito através da plataforma miro por todo o grupo ao longo de nossos encontros pelo discord. Além disso, utilizamos o Discord como plataforma para a colaboração na elaboração das partes essenciais do projeto, tais como o wireframe e a documentação do projeto.

## Divisão de Papéis

| Integrante    | Função        |
| ------------- | ------------- |
| Guilherme Tavares Nogueira de Abreu | Scrum Master, design thinking |
| Henrique Resende Lara| design thinking, github, documentação |
| Lucas Nascimento Gomes | documentação, design thinking |
| Sofia Melo do Prado Rocha Duque | powerpoint, design thinking, documentação |
| Tarcísio Ferraz Justa Silva |  design thinking, documentação |

## Ferramentas

| Ambiente  | Plataforma              |Link de Acesso |
|-----------|-------------------------|---------------|
|Processo de Design Thinkgin  | Miro | https://miro.com/app/board/uXjVMYDTrpA=/ | 
|Repositório de código | GitHub | https://github.com/XXXXXXX | 
|Hospedagem do site | Heroku |  https://XXXXXXX.herokuapp.com | 
|Protótipo Interativo | Figma | https://www.figma.com/file/4rDtleiNgVzUK7wOKfE82H/WIREFRAMES?node-id=0-1&t=xHmltHmbzUoRnnGK-0 | 
|Hospedagem temporária de documentos | Google Drive | https://docs.google.com/document/d/1JUIOHRdbjs2d59r4ngUYuaxaczFcojqCgKUmMU4-bUU/edit?usp=sharing | 

## Controle de Versão

A configuração do projeto inicia-se com a criação de um repositório no github. Uma vez criado, é possível criar branches para trabalhar em diferentes recursos ou tarefas em paralelo.  A gerência de commits é feita para registrar as alterações realizadas em um branch. (Um branch, em Git, é uma cópia do código-fonte do projeto) Um commit é uma imagem instantânea do estado do código em um determinado momento. A gerência de merges é importante para combinar alterações de diferentes branches em uma única versão do código. Já as tags são marcadores que indicam um ponto específico na história do código. Elas são úteis para marcar lançamentos importantes ou pontos de referência no desenvolvimento do projeto. A gerência de issues é realizada por meio da criação de problemas ou bugs no sistema de rastreamento de problemas.

# **############## SPRINT 1 ACABA AQUI #############**


# Projeto da Solução

## Tecnologias Utilizadas

HTML, CSS e JavaScript, que são três tecnologias fundamentais para o desenvolvimento de páginas web interativas, foram utilizadas, além de uma API para gerar QR Codes.
> Descreva aqui qual(is) tecnologias você vai usar para resolver o seu
> problema, ou seja, implementar a sua solução. Liste todas as
> tecnologias envolvidas, linguagens a serem utilizadas, serviços web,
> frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.
> Apresente também uma figura explicando como as tecnologias estão
> relacionadas ou como uma interação do usuário com o sistema vai ser
> conduzida, por onde ela passa até retornar uma resposta ao usuário.

![image](https://github.com/ICEI-PUC-Minas-PPLCC-TI/ti-1-ppl-cc-m-20231-entretenimento/assets/104558625/82d71f44-3748-48db-8622-994882980c89)


> Inclua os diagramas de User Flow, esboços criados pelo grupo
> (stoyboards), além dos protótipos de telas (wireframes). Descreva cada
> item textualmente comentando e complementando o que está apresentado
> nas imagens.

## Arquitetura da solução

......  COLOQUE AQUI O SEU TEXTO E O DIAGRAMA DE ARQUITETURA .......

> Inclua um diagrama da solução e descreva os módulos e as tecnologias
> que fazem parte da solução. Discorra sobre o diagrama.
> 
> **Exemplo do diagrama de Arquitetura**:
> 
> ![Exemplo de Arquitetura](images/arquitetura-exemplo.png)


# Avaliação da Aplicação

......  COLOQUE AQUI O SEU TEXTO ......

> Apresente os cenários de testes utilizados na realização dos testes da
> sua aplicação. Escolha cenários de testes que demonstrem os requisitos
> sendo satisfeitos.

## Plano de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Enumere quais cenários de testes foram selecionados para teste. Neste
> tópico o grupo deve detalhar quais funcionalidades avaliadas, o grupo
> de usuários que foi escolhido para participar do teste e as
> ferramentas utilizadas.
> 
> **Links Úteis**:
> - [IBM - Criação e Geração de Planos de Teste](https://www.ibm.com/developerworks/br/local/rational/criacao_geracao_planos_testes_software/index.html)
> - [Práticas e Técnicas de Testes Ágeis](http://assiste.serpro.gov.br/serproagil/Apresenta/slides.pdf)
> -  [Teste de Software: Conceitos e tipos de testes](https://blog.onedaytesting.com.br/teste-de-software/)

## Ferramentas de Testes (Opcional)

......  COLOQUE AQUI O SEU TEXTO ......

> Comente sobre as ferramentas de testes utilizadas.
> 
> **Links Úteis**:
> - [Ferramentas de Test para Java Script](https://geekflare.com/javascript-unit-testing/)
> - [UX Tools](https://uxdesign.cc/ux-user-research-and-user-testing-tools-2d339d379dc7)

## Registros de Testes

......  COLOQUE AQUI O SEU TEXTO ......

> Discorra sobre os resultados do teste. Ressaltando pontos fortes e
> fracos identificados na solução. Comente como o grupo pretende atacar
> esses pontos nas próximas iterações. Apresente as falhas detectadas e
> as melhorias geradas a partir dos resultados obtidos nos testes.


# Referências

......  COLOQUE AQUI O SEU TEXTO ......

> Inclua todas as referências (livros, artigos, sites, etc) utilizados
> no desenvolvimento do trabalho.
> 
> **Links Úteis**:
> - [Formato ABNT](https://www.normastecnicas.com/abnt/trabalhos-academicos/referencias/)
> - [Referências Bibliográficas da ABNT](https://comunidade.rockcontent.com/referencia-bibliografica-abnt/)
