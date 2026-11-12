# Estudo Flexbox

O Flexbox serve para:
- Criar layouts mais flexíveis e responsivos.
- Tratar do posicionamento e alinhamento dos elementos em uma página.
- Facilitar a distribuição de espaços de forma proporcional.
- Organizar layouts de forma eficiente, principalmente em sites responsivos, adaptando os elementos nos diferentes dispositivos.

#### Conceitos básicos:
- **Flex container:** é o elemento que usa "display:flex", que abrange os itens que serão organizados.  
- **Flex itens:** são os elementos dentro do container, que são organizados pelo flexbox.
- **Eixo principal:** direção na qual os itens flex serão distribuídos, usado para justificar os itens. Formato padrão: horizontal, da esquerda para a direita.
- **Eixo perpendicular:** direção perpendicular ao eixo principal (90°), usado para alinhar os itens. Formato padrão: vertical, de cima para baixo.

#### Propriedade justify-content pode assumir os valores:
- flex-start (padrão): Os itens são inseridos no início do eixo principal.
- flex-end: Os itens são inseridos no final do eixo principal.
- center: Os itens ficam centralizados ao longo do eixo principal.
- space-between: Os itens são distribuídos de forma igual, o primeiro e o último item fica grudado na lateral da tela, respectivamente no início e no final, e o espaço livre sobra apenas entre eles.
- space-around: Os itens são distribuídos com espaços iguais ao redor de cada um (o espaço nas pontas é metade do espaço entre dois itens).
- space-evenly: O espaço livre é dividido em partes perfeitamente iguais entre os itens e nas duas extremidades.

#### Propriedade align-items pode ter os valores:
- stretch (padrão): Os itens são esticados para preencher toda a altura (ou largura) do contêiner no eixo transversal.
- flex-start / start: Alinha os itens no início do eixo transversal (no topo, por padrão, em flexbox horizontal).
- flex-end / end: Alinha os itens no final do eixo transversal (na parte inferior, por padrão, em flexbox horizontal).
- center: Centraliza os itens no meio do eixo transversal.
- baseline: Alinha os itens com base na linha de base (baseline) do texto de cada um.
 