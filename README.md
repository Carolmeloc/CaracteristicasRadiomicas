# CaracteristicasRadiomicas
Esse é o repositório de um projeto que busca explorar, modelar e avaliar algoritmos de machine learning para a classificação binária de câncer de mama e aplicar técnicas de clustering para análise não supervisionada dos mesmos dados.

# radiomic_data
Repositorio de onde tirei os dados contendo o dataset para o projeto além do pdf do TCC em que a base foi utilizada.

- Os dados foram obtidos utilizando a lib **pyradiomics** do python em imagens de regiões de interesse de mamografias, as features radiômicas são características extraídas quantitativamente de imagens. Elas são utilizadas para descrever propriedades como textura, intensidade e forma nas imagens.

 A **pyradiomics** permite a extração de um grande conjunto de features radiômicas, que podem ser categorizadas em diferentes grupos, como:

- **First-order statistics**: características baseadas na distribuição dos valores de pixel, como média, desvio padrão e entropia.
- **Shape-based features**: descrevem a forma e o tamanho da região segmentada, como esfericidade e volume.
- **Texture features**: analisam padrões na distribuição de intensidades, incluindo Matriz de Coocorrência de Níveis de Cinza (GLCM), Matriz de Dependência de Níveis de Cinza (GLDM), entre outras.

