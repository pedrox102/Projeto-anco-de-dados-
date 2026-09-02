# Direção visual — Cálculo Relacional Explorer

## Três possibilidades iniciais

### 1. Caderno de Consulta
**Muito breve:** Uma estação de estudo editorial que transforma fórmulas e relações em páginas de caderno técnico, com azul de tinta, papel quente e pequenos acentos coral. O sentimento é de pesquisa rigorosa, mas convidativa.  
**Probabilidade:** 0.04

### 2. Arquivo Lógico
**Muito breve:** Um arquivo universitário de alto contraste, com fichas catalográficas, separadores e nomenclatura de laboratório. O tom é sóbrio, histórico e preciso.  
**Probabilidade:** 0.08

### 3. Malha de Predicados
**Muito breve:** Um ambiente escuro de visualização de grafos e conectores, inspirado em diagramas de redes de dados. O foco é energia técnica e densidade visual.  
**Probabilidade:** 0.02

---

## Abordagem escolhida: Caderno de Consulta

### Movimento de design
**Editorial técnico contemporâneo**, inspirado em cadernos de laboratório, livros acadêmicos anotados e sinalização de uma biblioteca de pesquisa. A página não deve parecer um dashboard genérico: é uma leitura guiada por margens, índices, blocos de anotação e uma visualização ativa da consulta.

### Princípios centrais
1. **Conhecimento em camadas:** introduzir a ideia geral antes de expor notações formais e, só então, vincular a fórmula à execução em SQL.
2. **Assimetria legível:** usar uma faixa lateral de navegação e contexto como contraponto a um corpo principal amplo, evitando centralização monótona.
3. **Lógica visível:** evidenciar relações, predicados, quantificadores e resultados por conectores, tags e blocos monoespaçados com contraste claro.
4. **Rigor acessível:** manter linguagem, espaçamento e interação acolhedores para estudantes, sem perder precisão técnica.

### Filosofia de cores
O fundo será um **papel mineral quente** (`#F6F2E9`) para remeter à pesquisa anotada e reduzir fadiga de leitura. O **azul cobalto de tinta** (`#123B63`) dá autoridade às estruturas e títulos; o **coral de sinalização** (`#E85D42`) assinala predicados e chamadas de atenção; tons de sálvia reforçam estados de resposta e segurança. A cor de assinatura é o **Coral de Predicado** (`#E85D42`): reservada para condições, relações ativas e ações principais.

### Paradigma de layout
Em desktop, a página funciona como uma **prancheta de investigação**: coluna lateral estreita e aderente para seções e fontes, conteúdo principal assimétrico e uma área de “laboratório” que amplia horizontalmente as consultas e gráficos. Em telas menores, a ordem passa a ser narrativa, com o índice em uma faixa rolável no topo e os laboratórios em cartões de largura integral.

### Elementos de assinatura
1. **Marcadores de margem numerados:** pequenos discos com índice de seção, criando o ritmo de um caderno de referências.
2. **Linhas de relacionamento:** conectores e pontilhados discretos entre relações, predicados e saídas.
3. **Rótulos de notação:** etiquetas compactas em caixa alta para `TRC`, `DRC`, `SQL`, `PREDICADO` e `SEGURO`.

### Filosofia de interação
As interações devem fazer o conteúdo parecer examinável. O visitante seleciona exemplos de consultas, percorre os resultados do conjunto didático e alterna entre TRC, DRC e SQL. As respostas aparecem como uma leitura do predicado — não como um efeito decorativo. Hovers oferecem microexplicações; ações do teclado recebem resposta imediata.

### Animação
Movimento limitado a 180–260 ms com curva `cubic-bezier(0.23, 1, 0.32, 1)`. Filtros e abas devem mudar por opacidade e leve translação horizontal de 6–10 px; linhas de relação podem ser desenhadas uma vez ao entrar no laboratório. Sem animações contínuas, sem escalas desde zero e com suporte a `prefers-reduced-motion`.

### Sistema tipográfico
**Fraunces** será a fonte de exibição, em pesos 600–700, para capítulos e chamadas; **IBM Plex Sans** será usada no texto e interface por sua leitura técnica; **IBM Plex Mono** será reservada à notação, SQL e metadados. Títulos terão espaçamento levemente negativo, corpo com entrelinha generosa e códigos sempre com tamanho fixo maior que 13 px.

### Essência da marca
**Uma pesquisa interativa sobre Cálculo Relacional para estudantes que desejam transformar fórmulas formais em consultas compreensíveis e verificáveis.**  
Personalidade: **metódica, clara, investigativa**.

### Voz da marca
As manchetes são assertivas e didáticas; CTAs convidam à exploração concreta; microcopy explica a próxima relação lógica em vez de usar expressões genéricas.  
Exemplos: “Formule a condição. Observe as tuplas responderem.” e “Uma consulta segura limita a resposta ao que a base conhece.”

### Wordmark e logo
O wordmark combina “Cálculo” em Fraunces com “RELACIONAL” em IBM Plex Mono espaçado. O símbolo é uma **chave de conjunto aberta** que envolve três nós conectados — uma referência visual à forma `{ t | P(t) }`, sem texto dentro do ícone. Ele aparece amplo no cabeçalho e como favicon.

## Style Decisions

- A chave de conjunto aberta com três nós é o motivo estrutural recorrente: aparece no logotipo, em anotações do laboratório, nos marcos de comparação, no rodapé de referências e nas placas de consulta.
- O laboratório cobalto é uma placa de pesquisa inserida no caderno, com etiquetas monoespaçadas, relação visível entre predicado e resposta e uma anotação em papel mineral; ele não deve assumir linguagem visual de painel genérico.
- Coral `#E85D42` indica predicado ativo, consulta selecionada, ação de exploração principal, citação e alerta marginal. Azul cobalto estrutura a página; coral nunca serve como enfeite genérico.
