# SmartCV – Analisador Inteligente de Currículos com IA

## Descrição do Projeto

O **SmartCV** é um sistema inteligente desenvolvido para automatizar a análise de currículos em processos de recrutamento e seleção. Utilizando técnicas de **Inteligência Artificial** e **Processamento de Linguagem Natural (NLP)**, o sistema é capaz de ler currículos em formato PDF, extrair habilidades técnicas, comparar com os requisitos de uma vaga e gerar um **score de compatibilidade**, além de um **ranking automático de candidatos**.

O principal diferencial do projeto é a **explicabilidade**, ou seja, o sistema informa claramente os motivos que levaram à pontuação atribuída a cada candidato, promovendo maior transparência no processo seletivo.

---

## Objetivos

### Objetivo Geral
Desenvolver um sistema inteligente capaz de analisar currículos automaticamente e classificá-los conforme os requisitos de uma vaga.

### Objetivos Específicos
- Realizar upload e leitura de currículos em PDF  
- Extrair texto e identificar habilidades técnicas  
- Comparar currículo × vaga  
- Gerar score de compatibilidade  
- Criar ranking automático de candidatos  
- Explicar os critérios utilizados na avaliação  

---

## Tecnologias Utilizadas

### Backend e IA
- **Python**
- **FastAPI**
- **SpaCy / NLTK**
- **Transformers (opcional)**

### Processamento de Arquivos
- **PyPDF2** ou **pdfplumber**

### Banco de Dados
- **SQLite** (desenvolvimento)
- **PostgreSQL** (produção)

### Frontend
- HTML5
- CSS3
- Bootstrap
- Jinja2

---

## Arquitetura do Sistema

Usuário
↓
Interface Web
↓
API FastAPI
↓
Extração de Texto (PDF)
↓
NLP / IA
↓
Score + Explicação
↓
Banco de Dados
↓
Ranking de Candidatos


---

## Estrutura do Projeto

smartcv/
├── app/
│ ├── main.py
│ ├── api/
│ ├── core/
│ ├── models/
│ ├── schemas/
│ ├── services/
│ ├── db/
│ ├── templates/
│ ├── static/
│ └── utils/
│
├── tests/
├── requirements.txt
├── README.md
└── .env


---

## ⚙️ Funcionalidades

- Upload de currículos em PDF  
-  Extração automática de habilidades  
-  Cálculo de score de compatibilidade  
-  Ranking automático de candidatos  
-  Explicação detalhada da pontuação  
-  Interface web simples e intuitiva  

---

## Como Executar o Projeto

### 1° Clonar o repositório
```bash
git clone https://github.com/seu-usuario/smartcv.git
cd smartcv

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

pip install -r requirements.txt
uvicorn app.main:app --reload
```
http://127.0.0.1:8000


