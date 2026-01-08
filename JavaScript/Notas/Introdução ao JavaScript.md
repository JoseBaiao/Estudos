---
tags:
  - JavaScript/Estudo/Introdução
  - Estudo/Conhecimento
status: ✅ Concluído
---
---
# Introdução ao JavaScript

> [!question] O que é JavaScript?
> O **JavaScript** é a linguagem fundamental da web, sendo responsável por fazer correr a lógica atrás de praticamente todos os sites que conhecemos. Como especialista, posso dizer-te que ele é o que **dá vida às páginas web**, transformando documentos estáticos (HTML) em aplicações interativas e dinâmicas que respondem às ações do utilizador em tempo real.
> - **Origem:** Foi desenvolvido por Brendan Eich na Netscape, originalmente chamado de "LiveScript".
>- **Nome:** O nome foi alterado para JavaScript por uma questão de marketing, para aproveitar a popularidade da *linguagem Java*, embora sejam linguagens distintas com arquiteturas diferentes.
>- **Padronização:** É padronizado pelo <strong>ECMAScript</strong>, o que garante consistência entre diferentes navegadores e ambientes.

>[!question] Onde o JavaScript executa?
>Originalmente, o JavaScript foi criado para ser executado apenas nos **navegadores** (como Chrome, Safari ou Edge), que possuem um motor (engine) interno para processar este código. No entanto, com o surgimento do **Node.js**, a linguagem expandiu-se para o **lado do servidor (backend)**, permitindo construir aplicações completas fora do browser. A principal diferença é que no navegador temos acesso a ferramentas para interagir com elementos do ecrã, cookies e o histórico, enquanto no servidor focamos na lógica de dados.
##  Para que serve? (Versatilidade)
- A. Lado do Cliente (*Frontend*)-É utilizado para manipular a estrutura (**HTML**) e o estilo (**CSS**) de uma página. 

> [!example] Exemplos incluem:
> - **Validação de formulários:** Verificar erros em tempo real antes de enviar os dados para o servidor.
> - **Galerias interativas:** Trocar imagens ou abrir visualizadores em ecrã total.
> - **Carregamento dinâmico:** Adicionar novos conteúdos (como artigos ou posts) sem sair da página atual.

B. Lado do Servidor (*Backend*) -Com a criação do **Node.js**, o JavaScript passou a poder ser executado fora do browser. 

> [!example] Isto permite:
> - Criar serviços de backend e APIs.
> - Desenvolver aplicações em tempo real, como chats (Slack, WhatsApp Web).
> -  Criar ferramentas de linha de comando (CLI) para automatizar tarefas.

C. Aplicações Móveis e Desktop

> [!example] 
> - **Mobile:** Através de frameworks como o React Native, é possível criar apps nativas para iOS e Android com uma única base de código.
> 
> -  **Desktop:** Ferramentas como o Electron permitem criar aplicações para computador (ex: VSCode, Discord, Slack) usando tecnologias web.

##  Por que é que o JavaScript é importante?

> [!important] A importância da linguagem reside em quatro pilares fundamentais:
> 
> - **Ubiquidade:** Corre em quase todo o lado — browsers, servidores, telemóveis e computadores.
> - **Versatilidade:** Permite o desenvolvimento **full-stack**, ou seja, um programador pode usar a mesma linguagem para o *frontend* e o *backend*, reduzindo a carga cognitiva.
> - . **Comunidade e Ecossistema:** Possui uma das maiores comunidades de programadores do mundo, resultando em vastos recursos, tutoriais e bibliotecas (como React, Angular e Vue) que aceleram o desenvolvimento.
> - **Natureza Assíncrona:** O JS é "non-blocking", o que significa que pode iniciar uma tarefa (como procurar dados num servidor) e continuar a executar outro código sem congelar a interface do utilizador.

## Como funciona (Visão Simplificada)

> [!info]
> Quando visitas um site, o browser descarrega os ficheiros JS e utiliza um **motor (engine)** (como o V8 no Chrome) para processar o código.
> 
> • **Interpretação JIT (Just-In-Time):** O código é traduzido e executado quase instantaneamente.
> • **DOM (Document Object Model):** O JS interage com o DOM (a representação estrutural da página) para modificar elementos e estilos dinamicamente.
> • **Manipulação de Eventos:** O JS fica "à escuta" de ações como cliques ou teclas premidas para executar comportamentos específicos
> 

## Como adicionar JavaScript a uma página HTML?

Bem existe, duas maneiras de adicionarmos Javascript a uma pagina html que são as seguintes:

> [!info] 1. **Injeção de código (Código interno)** - Podemos adicionar código JavaScript diretamente no teu ficheiro HTML utilizando a tag `<script>` 
> - Esta tag funciona como um contentor onde podes escrever as tuas instruções (como um `console.log`, por exemplo).
> - Normalmente, estas tags são colocadas dentro do corpo (`body`) do HTML, onde as outras tags de conteúdo residem.

No VS Code:
```hmtl5
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <h1>Hello World</h1>
  <p>This is a simple HTML document</p>
  <script>
    console.log("Hello World");
  </script>
</body>
</html>
```

Resultado na web:
![[Captura de ecrã 2026-01-08 154112.png]]

> [!info] 2. **Importação de um Ficheiro Externo** - A forma mais organizada e comum em projetos reais é manter o código JavaScript num ficheiro separado (com a extensão `.js`) e importá-lo para o HTML.
> - Para isto, utiliza-se a mesma tag `<script>`, mas adiciona-se o **atributo** **src** (source), indicando o caminho do ficheiro, como por exemplo: `<script src="script.js"></script>`.
> - Este método é muito semelhante à forma como se importam folhas de estilo CSS para uma página.

## Ferramentas essências

Bem, como um mecânico tem as ferramentas necessárias para poder arranjar um carro o programador de javascript também tem a suas ferramentas essências para poder trabalhar, que são as seguintes.
>[!note] Ferramentas essências do programador
> - Navegador (DevTools)
> - VS Code