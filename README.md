Descrição do Conjunto de Dados
Este conjunto de dados foi coletado de postagens feitas no Reddit sobre a Doença de Crohn. O objetivo principal do conjunto de dados é fornecer uma base para análise de sentimentos e extração de tópicos a partir das postagens feitas pelos usuários. 
O conjunto contém informações como o título, texto completo da postagem, data e hora de publicação, e as classificações de sentimento atribuídas pelos modelos VADER e RoBERTa.

Estrutura do Conjunto de Dados
O conjunto de dados contém as seguintes variáveis:

titulo: O título original da postagem feita no Reddit.

texto: O texto completo da postagem (conteúdo bruto).

data: Data e hora em que a postagem foi publicada.

contagem_palavras: Número total de palavras presentes na postagem.

texto_limpo: Texto pré-processado, removendo pontuação, stopwords, emoticons etc.

sentimento_vader: Classificação de sentimento atribuída pelo modelo VADER (positivo, negativo, neutro).

compound_vader: Escore numérico de sentimento atribuído pelo modelo VADER.

sentimento_roberta: Classificação de sentimento atribuída pelo modelo RoBERTa.

--------------------------------------------------------------------------------------
Dataset Description
This dataset was collected from posts made on Reddit about Crohn's Disease. The primary objective of the dataset is to provide a basis for sentiment analysis and topic extraction from posts made by users. 
The dataset contains information such as the title, full text of the post, date and time of publication, and sentiment classifications assigned by the VADER and RoBERTa models.

Dataset Structure
The dataset contains the following variables:

title: The original title of the post made on Reddit.

text: The full text of the post (raw content).

date: The date and time when the post was published.

word_count: The total number of words in the post.

clean_text: Pre-processed text, with punctuation, stopwords, emoticons, etc., removed.

vader_sentiment: Sentiment classification assigned by the VADER model (positive, negative, neutral).

compound_vader: Sentiment score assigned by the VADER model.

roberta_sentiment: Sentiment classification assigned by the RoBERTa model.
