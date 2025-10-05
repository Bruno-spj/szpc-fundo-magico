# 🎨 Fundo Mágico

O **Fundo Mágico** é uma aplicação web interativa que **gera automaticamente backgrounds personalizados**, criando **código HTML e CSS** de forma dinâmica a partir de uma simples descrição do usuário.  
O projeto integra **JavaScript**, **automação com N8N** e uma interface intuitiva para visualizar os resultados em tempo real.  

---

## 🚀 Tecnologias Utilizadas

- **HTML5** – Estrutura da aplicação.  
- **CSS3** – Estilização dinâmica dos backgrounds gerados.  
- **JavaScript (ES6+)** – Manipulação do DOM e integração com a automação.  
- **N8N (Automação)** – Fluxo automatizado para processar descrições e retornar o código do fundo gerado.  

---

## 🧠 Como Funciona

1. O usuário descreve o tipo de background desejado (ex: *“um fundo degradê com estrelas cintilando”*).  
2. Ao clicar em **Gerar Background Mágico**, o sistema:
   - Envia a descrição via **fetch** para um **Webhook do N8N**.  
   - O N8N processa essa entrada (possivelmente com IA ou lógica customizada).  
   - Retorna o **código HTML e CSS** correspondente.  
3. O front-end atualiza automaticamente:
   - A pré-visualização do fundo.  
   - Os blocos de código com HTML e CSS gerados.  

---

## 🧑‍💻 Autor

Bruno da Silva 

💼 Projeto desenvolvido durante a imersão de programação web com Dev em Dobro, explorando HTML, CSS, JavaScript e automação com N8N.

