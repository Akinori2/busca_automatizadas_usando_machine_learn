## Aplicando conhecimentos Heuristicos em Python usando o colab  

**Intuito do codigo:** Combina machine learning para classificação de imagens e uma busca automatizada no Google para exibir imagens de cachorros com base em descrições fornecidas pelo usuário, neste caso a de cachorros.  

---

## Principais bibliotecas
- **tensorflow:** open-source de machine learning e inteligência artificial usado para criar e treinar modelos de aprendizado profundo
- **keras:** API para construção e treinamento de modelos de deep learning, que roda sobre o TensorFlow
- **requests:** Biblioteca para fazer requisições HTTP, facilitando a comunicação com APIs e a obtenção de dados de sites
- **beautifulsoup4:** Biblioteca para fazer parsing de HTML e XML, usada para extrair dados de páginas web
- **google-api-python-client:** Utilizado para interagir com diversos serviços do Google

---

## Carregamento de modelo pré-treinado 
Importa o modelo **MobileNetV2**
- modelo de classificação de imagens pré-treinado na base de dados ImageNet um "danco de dados virtual" com milhoes de imagens

---

## Classificação de imagens
Função chamada classify_dog processa uma imagem, faz a predição com o modelo MobileNetV2 e exibe a classe prevista (como "cachorro") com a pontuação de confiança

---

## Busca automática no Google
API de busca personalizada do Google para procurar imagens de cães com base no input

---

## Heurística para refinar buscas
A biblioteca spacy para processar o texto da pesquisa do usuário, remover stopwords e adicionar sinônimos aleatórios para melhorar a busca de imagens

---

## Busca e exibição de imagem
Realiza uma busca de imagens usando o Google Custom Search API com base na raça de cachorro fornecida pelo usuário e exibe a imagem resultante
