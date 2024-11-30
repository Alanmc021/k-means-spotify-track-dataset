# Spotify Music Clustering with K-Means

Este projeto utiliza o algoritmo **K-Means** para agrupar músicas com base em características musicais como `danceability`, `energy`, `loudness`, `tempo` e `valence`. Ele ajuda a identificar padrões e criar clusters significativos, como músicas dançantes, tristes, enérgicas, etc. O banco de dados utilizado foi extraído do Spotify, com todas as amostras já processadas e limpas.

---

## **Tabela de Conteúdo**
- [Sobre o Projeto](#sobre-o-projeto)
- [Algoritmos e Técnicas](#algoritmos-e-técnicas)
- [Pré-Requisitos](#pré-requisitos)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Resultados](#resultados)
- [Contribuição](#contribuição)
- [Licença](#licença)

---

## **Sobre o Projeto**
O objetivo principal deste projeto é utilizar aprendizado de máquina não supervisionado para:
1. Encontrar o número ideal de clusters (k) para agrupar músicas.
2. Explorar padrões musicais usando a curva do cotovelo e o diagrama de silhueta.
3. Organizar músicas de forma mais intuitiva e útil para aplicações reais, como criação de playlists.

---

## **Algoritmos e Técnicas**
1. **K-Means Clustering**:
   - Um dos algoritmos mais populares de aprendizado de máquina não supervisionado.
   - Divide os dados em k grupos com base na proximidade aos centróides.
   
2. **Curva do Cotovelo (Elbow Method)**:
   - Usada para encontrar o intervalo ideal para \(k\).
   
3. **Diagrama de Silhueta**:
   - Avalia a qualidade dos clusters formados.

4. **Normalização com StandardScaler**:
   - As características musicais possuem escalas diferentes; a normalização garante que todos os atributos tenham o mesmo peso.

---

## **Pré-Requisitos**
Certifique-se de ter os seguintes pacotes instalados antes de rodar o projeto:
- Python 3.7 ou superior
- Jupyter Notebook ou Google Colab
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

Você pode instalar os pacotes com o comando:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
