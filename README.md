# 🚀 Santander Dev Week 2025 | Pipeline ETL com IA Generativa

- Este projeto foi desenvolvido como parte do Santander Dev Week 2025. O objetivo central é a construção de um pipeline ETL (Extract, Transform, Load) robusto, utilizando Python e Inteligência Artificial Generativa para automatizar a comunicação com clientes.

---

## 📋 Contexto do Projeto

- Como Cientista de Dados no Santander, o desafio proposto foi engajar os clientes de maneira mais assertiva e personalizada. A missão é transcender o marketing genérico, utilizando o poder da IA para entender o perfil de cada cliente e criar mensagens únicas, aumentando a relevância da comunicação bancária.

---

## O Fluxo ETL

**1. Extract (Extração)**: Coleta de dados dos clientes (IDs, nomes, comportamento financeiro) a partir de uma fonte de dados (CSV/API).

**2. Transform (Transformação)**: Utilização de IA Generativa via API do Groq para criar mensagens de marketing personalizadas baseadas nos dados extraídos.

**3. Load (Carregamento)**: Atualização dos dados no sistema com as novas mensagens geradas, prontas para envio.


---

## 🧠 Modelo de IA utilizado: ``llama-4-maverick-17b-128e-instruct``

A escolha deste modelo reflete o estado da arte da tecnologia em 2025:

- **Superioridade Lógica**: Testes indicam que a versão Maverick supera versões legadas em raciocínio lógico e precisão contextual.

- **Custo-Eficiência com Groq**: A infraestrutura da Groq (LPU™ Inference Engine) foi selecionada por oferecer inferência quase instantânea e acesso gratuito a modelos de alta performance, tornando-se uma alternativa economicamente viável e tecnicamente superior para este caso de uso.

---

## 🛠️ Tecnologias e Ferramentas

1. **Linguagem**: Python
2. **API de IA**: Groq Cloud
3. **Bibliotecas Principais**:
    3.1 **pandas** (Manipulação de dados)
    3.2 **groq** (Cliente oficial para interação com a LLM)


---

#### Autor: Lucca de Sena Barbosa
