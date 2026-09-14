# SPTech Super-App Hub

O **SPTech Super-App Hub** é uma plataforma centralizada de microsserviços desenvolvida para executar múltiplos **Mini-Apps** utilitários. O hub funciona como um painel central que organiza várias ferramentas independentes em um só lugar, facilitando o acesso do usuário.
---

## 🧠 Abordagem Arquitetural

O site foi feito de forma modular. Em vez de criar uma única página gigante e pesada, cada calculadora funciona separadamente. Ao clicar, o módulo abre em uma nova aba do navegador (target="_blank"), deixando o sistema muito mais rápido e organizado.

Os mini-apps estão divididos de acordo com a regra de lógica que cada um utiliza:

### Módulos baseados em Lógica AND (`&&`)
Aplicações que usam lógica de **validação condicional restritiva**. O sistema só aprova o resultado se **todas** as condições forem verdadeiras ao mesmo tempo.

### Módulos baseados em Lógica OR (`||`)
Aplicações que usam a lógica de **fluxos decisão alternativa**. O sistema aprova o resultado se **pelo menos uma** das condições for verdadeira.
---

## 🛠️ Tecnologias Utilizadas

- **HTML5 Semântico:** Estruturação robusta da árvore do DOM utilizando tags nativas de organização estrutural.
- **CSS3 Avançado:** Camada de estilização desacoplada via folha de estilo externa (`css/style.css`), aplicando conceitos modernos de layout responsivo (Flexbox/Grid).
- **JavaScript (ES6+):** Processamento lógico local descentralizado dentro de cada mini-app e motores analíticos de manipulação de DOM para gestão dinâmica dos indicadores globais.

---

## Instituição
São Paulo Tech School
Curso de Tecnologia da Informação / Análise e Desenvolvimento de Sistemas