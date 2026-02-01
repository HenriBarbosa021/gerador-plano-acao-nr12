# Gerador de Plano de Ação – NR-12

🧪 **Status:** Versão Alpha  
📄 **Uso:** Interno (código público para fins educacionais e de portfólio)

---

## 📌 Descrição

Este projeto automatiza a geração de **planos de ação** a partir de **relatórios de apreciação de risco em PDF**, conforme a **NR-12** e a **NBR ISO 12100**.

A aplicação realiza a leitura de arquivos PDF, extrai informações relevantes como **Não Conformidades (NC)** e **indicadores de risco**, e gera automaticamente **planilhas Excel estruturadas**, reduzindo tempo, retrabalho e erros manuais.

O projeto foi desenvolvido com foco em **usuários com pouco conhecimento de TI**, oferecendo uma interface simples e objetiva.

---

## 🎯 Problema

Em processos industriais, a transformação de relatórios técnicos em planos de ação é frequentemente:

- Manual
- Repetitiva
- Suscetível a erros
- Demorada

Este projeto surgiu para **automatizar essa etapa**, mantendo o caráter técnico e sem substituir a análise de engenharia.

---

## ⚙️ Funcionalidades

- Leitura automática de PDFs
- Extração de Não Conformidades (NC)
- Identificação de:
  - Categoria de Risco
  - PLr
- Geração de planilhas Excel
- Suporte a múltiplos PDFs (em lotes)
- Interface gráfica simples (Tkinter)
- Arquitetura modular e extensível

---

## ❌ O que o projeto NÃO faz

- Não interpreta decisões técnicas
- Não valida conformidade legal
- Não substitui análise de engenharia
- Não executa cálculos normativos

---

## 🛠️ Tecnologias Utilizadas

- Python 3.11
- PyMuPDF (fitz)
- openpyxl
- Regex
- Tkinter

---

## 📂 Estrutura do Projeto

