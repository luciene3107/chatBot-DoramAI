# 🎭 DoramAI

**DoramAI** é um chatbot especializado em doramas, desenvolvido como parte de um projeto da Pós-Graduação em Inteligência Artificial. O objetivo é criar uma experiência conversacional capaz de auxiliar fãs de dramas asiáticos com recomendações, informações sobre séries, elenco, gêneros, sinopses e curiosidades.

> ⚠️ Este projeto ainda está em desenvolvimento e novas funcionalidades serão adicionadas ao longo da evolução dos estudos e da especialização.

## 🌟 Sobre o Projeto

O DoramAI foi criado para atuar como um assistente virtual para dorameiros, oferecendo suporte na busca por informações sobre:

- 🇰🇷 K-Dramas (Coreia do Sul)
- 🇯🇵 J-Dramas (Japão)
- 🇨🇳 C-Dramas (China)

O chatbot combina Inteligência Artificial Generativa com dados obtidos por meio de APIs externas para fornecer respostas relevantes e contextualizadas.

## ✨ Funcionalidades Atuais

- 🔍 Busca de informações sobre doramas.
- 🎬 Consulta de sinopses.
- 👥 Informações sobre elenco.
- ❤️ Recomendações de doramas.
- 💬 Interação em linguagem natural.
- ⭐ Sugestões de títulos populares.

## 🛠️ Tecnologias Utilizadas

- Python
- Google Colab
- API do Groq (LLM)
- API do TMDB (The Movie Database)


## 🔌 Integrações

### Groq API

Utilizada para processamento de linguagem natural e geração de respostas inteligentes, permitindo uma interação mais natural com o usuário.

### TMDB API

Utilizada para consulta de informações sobre séries e doramas através do endpoint:

`https://api.themoviedb.org/3/search/tv`

Com ela é possível obter informações como:

- Nome do dorama
- Sinopse
- Data de lançamento
- Popularidade
- Avaliação dos usuários
- Imagens e pôsteres

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/doramai.git
```

2. Acesse a pasta do projeto:

```bash
cd doramai
```

3. Instale as dependências:

```bash
pip install -r requirements.txt
```

4. Configure as chaves de acesso das APIs utilizadas.

5. Execute o notebook principal no Google Colab ou em seu ambiente local.
   
## 💬 Exemplos de Perguntas

- Qual a sinopse de Goblin?
- Me recomende um dorama de romance.
- Quem faz parte do elenco de Queen of Tears?
- Quais são os doramas mais populares atualmente?
- Me indique um dorama parecido com Business Proposal?

## 🎯 Próximas Melhorias

- Implementação de banco de dados próprio.
- Ampliação da base de conhecimento.
- Recomendações personalizadas.
- Busca semântica utilizando embeddings.
- Interface web para interação com usuários.
- Histórico de conversas.

## 🎓 Contexto Acadêmico

Este projeto foi desenvolvido como parte das atividades práticas da Pós-Graduação em Inteligência Artificial, com foco na aplicação de:

- Inteligência Artificial Generativa
- Engenharia de Prompt
- Consumo de APIs
- Processamento de Linguagem Natural (NLP)
- Desenvolvimento de Chatbots

## 📌 Status do Projeto

🚧 **Versão MVP (Minimum Viable Product)**

O DoramAI encontra-se em desenvolvimento como projeto acadêmico da Pós-Graduação em Inteligência Artificial. Atualmente, o chatbot já realiza consultas a APIs externas e responde perguntas sobre doramas, mas novas funcionalidades estão previstas para as próximas versões.

## 📜 Licença

Projeto desenvolvido para fins educacionais e de aprendizado.


## 🙏 Créditos

Este projeto utiliza tecnologias e serviços de terceiros que tornaram o desenvolvimento do DoramAI possível:

- **Groq API** – Utilizada para processamento de linguagem natural e geração de respostas do chatbot.
  - https://groq.com/

- **The Movie Database (TMDB)** – Utilizada para consulta de informações sobre séries e doramas.
  - https://www.themoviedb.org/

- **TMDB API**
  - https://developer.themoviedb.org/

## ⚠️ Aviso

Este produto utiliza a API do TMDB, mas não é endossado nem certificado pelo TMDB.

## 👩‍💻 Autora

Desenvolvido por Luciene Borges como projeto de estudos da Pós-Graduação em Inteligência Artificial.


