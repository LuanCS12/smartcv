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

