# 🤖 Agente de IA - OCI Generative AI & Python

<br>

## 🚀 Tecnologias Utilizadas
<div>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Oracle_Cloud_Infrastructure-FF0000?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/OCI_Generative_AI-FF6F00?style=for-the-badge&logo=oracle&logoColor=white" />
  <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white">
  <img src="https://img.shields.io/badge/Requests-478778?style=for-the-badge&logo=requests&logoColor=white">
</div>

<br>

## 🎯 Objetivo

Este projeto foi desenvolvido durante o curso **OCI Generative AI e Python: construa agentes inteligentes com IA generativa**.  
O objetivo é demonstrar como integrar a **Oracle Generative AI** em aplicações Python, construindo assistentes inteligentes e interfaces interativas.

O repositório contém exemplos práticos de:

- 🧠 **Integração com OCI Generative AI**  
  Realização de requisições para modelos de linguagem via API da OCI.  

- ⚙️ **Ajuste de parâmetros**  
  Experimentos com *temperature*, *top-k*, *top-p* e *max tokens* no Playground da OCI.  

- ✍️ **Prompt Engineering**  
  Técnicas para obter respostas mais relevantes e personalizadas.  

- 💻 **Interfaces com Streamlit**  
  Criação de aplicações web simples para interação com assistentes virtuais.  

- 🌐 **Integração com APIs externas**  
  Enriquecendo as respostas do agente com dados atualizados em tempo real.  

- 🔗 **LangChain**  
  Uso da biblioteca para estruturar fluxos de decisão e agentes inteligentes.  

<br/>

## 📊 Fluxo de Interação com o Assistente

| ![image](https://raw.githubusercontent.com/Brunex-Alado/OCI_genAI/refs/heads/main/img/oci_genai_fluxo.png) |

<br/>


| ![image](https://raw.githubusercontent.com/Brunex-Alado/OCI_genAI/refs/heads/main/img/langchain_fluxo.png) |

<br/>

## ⚡ Como Executar o Projeto

Antes de rodar o projeto, você precisará garantir que seu **ambiente OCI está configurado corretamente**.  
No código (versão 3), o cliente é inicializado a partir de um arquivo de configuração (`~/.oci/config` ou caminho definido em `CONFIG_PATH`).  

Esse arquivo deve conter os seguintes campos mínimos dentro de um perfil (exemplo: `DEFAULT`):

```ini
[DEFAULT]
user=ocid1.user.oc1..aaaaaaaa...
fingerprint=aa:bb:cc:dd:ee:ff:11:22:33:44:55:66:77:88:99:00
key_file=C:\Users\seu-usuario\.oci\oci_api_key.pem
tenancy=ocid1.tenancy.oc1..aaaaaaaa...
region=sa-saopaulo-1
