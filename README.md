## 🧠 Sobre o projeto de análise de reclamações de clientes

Este projeto utiliza uma base de reclamações de clientes extraída do [Kaggle](https://www.kaggle.com/) para realizar **análises quantitativas e qualitativas**, combinando técnicas de **Data Analysis com Pandas** e **Inteligência Artificial com LangChain e modelos da OpenAI**.

Este projeto une o poder da análise de dados com inteligência artificial para simular uma abordagem automatizada e estratégica no tratamento de reclamações, algo  aplicável em áreas como **Customer Service**, **Análise de Sentimentos** e **Prevenção de Churn**.

---

### 📊 Etapas da Análise de Dados

- Leitura e tratamento dos dados com **Pandas**
- Contagem de **reclamações por empresa**
- Verificação de **quantas reclamações foram respondidas**
- Filtragem para considerar apenas empresas com mais de **400 reclamações**

---

### 🤖 Aplicação de IA com LangChain + OpenAI

Utilizando **LangChain** e modelos da **OpenAI**, cada reclamação passa por uma análise automatizada que entrega:

- **Resumo automático** da reclamação  
- **Análise de sentimento** do cliente  
- **Avaliação do risco de churn** com base na reclamação  
- **Plano de ação personalizado** para mitigar a dor do cliente e reverter a insatisfação

Essa abordagem simula um pipeline de atendimento inteligente que pode ser adotado por áreas de **Customer Experience** ou **Ouvidoria**.

---

### ⚙️ Como executar o projeto

1. Instale as dependências:

```
pip install -r requirements.txt
```

2. Crie um arquivo .env na raiz do projeto com sua chave da API da OpenAI:

```
OPENAI_API_KEY=your_key_here
```

3. Baixe o dataset original seguindo o link disponível no ```README.md``` dentro da pasta ```/data.```

---

### 🎯 Habilidades e tecnologias utilizadas


- Análise de dados com Pandas  
- Engenharia de dados com filtros e agregações personalizadas  
- Utilização de LLMs (Large Language Models) para insights interpretativos  
- Framework LangChain para orquestração das chamadas à IA  
- Engenharia de prompts e pipeline de análise automatizada  
- Criação de planos de ação com IA generativa  


