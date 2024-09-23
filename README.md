# animalPose

### 1. **Heatmap da Distribuição dos Pontos-Chave nas Imagens de Vacas**

**Descrição**: O heatmap apresenta a distribuição dos pontos-chave ao longo das imagens das vacas. Cada ponto vermelho no gráfico representa a posição de um ponto-chave em uma imagem de vaca. As áreas mais quentes (em amarelo) indicam regiões com maior concentração de pontos-chave.

**Análise dos Resultados**:
- O heatmap demonstra uma maior densidade de pontos-chave na região superior da imagem, sugerindo que as anotações de pontos-chave estão mais concentradas nas partes do corpo superior das vacas, como a cabeça e o tronco.
- Isso pode ser explicado pelo fato de que, para a estimativa de pose, é importante capturar os principais movimentos dessas áreas, como a articulação do pescoço e das patas dianteiras.

### 2. **Frequência de Visibilidade por Ponto-Chave (Vacas)**

**Descrição**: Este gráfico de barras mostra a frequência com que cada ponto-chave é visível nas imagens de vacas. O eixo X representa os IDs dos pontos-chave (1 a 20), enquanto o eixo Y indica quantas vezes cada ponto foi anotado como visível.

**Análise dos Resultados**:
- Os pontos-chave com IDs 2, 3, 4, 18 e 19 são os mais frequentemente anotados. Esses pontos podem corresponder a articulações importantes, como as pernas e a cabeça.
- Pontos-chave como o 7, 8 e 9 têm menos visibilidade, o que pode indicar que são mais difíceis de identificar em certas poses ou que estão frequentemente obstruídos.

### 3. **Boxplot das Áreas das Caixas Delimitadoras (Vacas)**

**Descrição**: O boxplot mostra a distribuição das áreas das caixas delimitadoras que contêm as vacas. A área de cada caixa delimitadora é calculada multiplicando a largura pela altura da caixa.

**Análise dos Resultados**:
- A mediana da área das caixas delimitadoras está em torno de 100.000 pixels quadrados.
- O gráfico também apresenta alguns **outliers**, que indicam imagens com vacas particularmente grandes ou pequenas. Isso sugere uma variação considerável no tamanho das vacas dentro das imagens, o que pode ser útil para treinar um modelo robusto.
