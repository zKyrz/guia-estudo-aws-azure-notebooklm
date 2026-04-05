# Miniguia de Estudos: Cloud Computing (AWS & Azure) ☁️

## 🎯 Contexto e Objetivos
Este projeto foi desenvolvido como parte de um desafio da DIO para explorar a Inteligência Artificial **NotebookLM** como ferramenta de aprendizagem ativa. 
O objetivo foi consolidar conhecimentos sobre **AWS** e **Azure**, comparando seus principais serviços e arquiteturas com foco nas certificações básicas (Cloud Practitioner e AZ-900).

## 📚 Curadoria de Fontes
Para alimentar a IA, utilizei as seguintes fontes:
* **PDFs Acadêmicos:** Materiais do curso de Cloud Computing da **FIAP**.
* [Material de Cloud Computing - Módulo 1](https://drive.google.com/file/d/1-F0u1KWIOpK18W2NhpR124K8MJWG6PwH/view?usp=drive_link)
* [Infraestrutura como Serviço (IaaS) e Conceitos](https://drive.google.com/file/d/1Ja1zVI8-Fhd4gqXuKL_iNqvhMfUsLj1l/view?usp=sharing)
* [Arquitetura de Nuvem e Escalabilidade](https://drive.google.com/file/d/1bdx4__LJPjhOvfbPrFe1msnsSSiiM_7V/view?usp=sharing)
 
* **Videoaulas:** Playlists selecionadas sobre Certificações Azure e AWS do YouTube.
* [Certificação AWS Cloud Practitioner](https://www.youtube.com/playlist?list=PL_yq9hmeKAk_rUvgo0KECZYI1bKzcyncC)
* [Treinamento Microsoft Azure Fundamentals (AZ-900)](https://www.youtube.com/playlist?list=PLz3hnOImntAMhFTvLpDdRROcHFF8D1Fuh)
* [Curso Prático de AWS](https://www.youtube.com/playlist?list=PLahhVEj9XNTcQ-rtUyuly3KpWFP9xzp7A)
* [Infraestrutura e Deploy em Cloud](https://www.youtube.com/playlist?list=PLahhVEj9XNTejs0fgXT6HXaj_a_qsUoKa)

## 🧠 Engenharia de Prompts
Durante o estudo, testei diferentes formas de extrair informação da IA. 

### Prompts Utilizados:
1. *"Compare o serviço S3 da AWS com o Blob Storage da Azure em termos de redundância."*
2. *"Resuma os conceitos de IaaS, PaaS e SaaS com exemplos práticos de ambas as nuvens."*

### Dificuldades e Aprendizados (Cicatrizes):
* **Desafio:** No início, a IA misturava os nomes dos serviços. 
* **Solução:** Precisei especificar no prompt: "Responda em formato de tabela separando as colunas por Provedor (AWS vs Azure)". Isso melhorou 100% a clareza.

## 🚀 Link do Projeto no NotebookLM
O caderno interativo com todos os cruzamentos de dados entre os PDFs da FIAP e as playlists de Cloud pode ser consultado aqui:

👉 [Aceder ao meu Caderno Temático (NotebookLM)](https://notebooklm.google.com/notebook/b9015f5c-27c2-4fc9-a58b-86de71d92c01)

## 📖 Resumo & Miniguia de Estudo 

### Resumo do Cenário Cloud 2026
Em 2026, a computação em nuvem consolidou-se como a espinha dorsal dos sistemas de software modernos, impulsionando desde startups até empresas globais. O mercado é dominado pela AWS (líder absoluta) e pelo Microsoft Azure, que mantém forte presença corporativa.

As principais tendências observadas nas fontes são:
* **Explosão da IA:** Surgiram novas certificações focadas em inteligência artificial generativa e liderança de transformação em IA, como a AI-900 e a AI Transformation Leader no Azure, e o AWS Certified AI Practitioner (AIF-C01).
* **Abordagem Role-Based:** As certificações não validam apenas o conhecimento do produto, mas a capacidade de desempenhar funções específicas (Administrador, Arquiteto, Engenheiro de Dados).
* **Virtualização e Contêineres:** A virtualização continua sendo o "coração" da nuvem, mas o Kubernetes e o Docker tornaram-se habilidades obrigatórias para orquestrar microsserviços em escala global.
* **Cultura DevOps:** A integração entre desenvolvimento e operações (DevOps) é essencial para entregas rápidas e seguras, utilizando automação e infraestrutura como código (IaC).

---

### Guia de Estudos Estruturado
Para dominar a nuvem, você deve seguir uma progressão lógica, do conceitual ao estratégico.

**Fase 1: Alfabetização em Nuvem (Fundamentals)**
* **Foco:** Entender modelos de serviço (IaaS, PaaS, SaaS), economia da nuvem (CapEx vs. OpEx) e responsabilidade compartilhada.
* **Certificações Sugeridas:** AZ-900 (Azure Fundamentals) ou CLF-C02 (AWS Cloud Practitioner).
* **Tempo:** 5 a 10 horas semanais por 2 a 4 semanas.
* **Ação:** Crie uma conta gratuita nos portais e explore o console básico.

**Fase 2: Imersão Técnica (Associate)**
* **Foco:** Implementação e gerenciamento prático. Aqui você aprende RBAC, redes virtuais (VNETs/VPCs), armazenamento e computação (EC2/VMs).
* **Certificações Sugeridas:** AZ-104 (Azure Administrator) ou SAA-C03 (AWS Solutions Architect Associate).
* **Tempo:** 10 a 15 horas semanais por 6 a 12 semanas.
* **Dica Prática:** Utilize o Azure Cloud Shell ou AWS CLI para aprender a automatizar recursos via linha de comando.

**Fase 3: Especialização e IA (Professional/Specialty)**
* **Foco:** Design de arquiteturas resilientes, segurança avançada e Machine Learning Ops (MLOps).
* **Certificações Sugeridas:** AZ-305 (Solutions Architect Expert) ou MLA-C01 (AWS Machine Learning Engineer Associate).
* **Projeto Âncora:** Construa um projeto de ponta a ponta (como o Cloud Resume Challenge), envolvendo Serverless, bancos de dados e CI/CD.

### Glossário
* **EC2 (AWS) / Virtual Machines (Azure):** Servidores virtuais na nuvem.
* **S3 (AWS) / Blob Storage (Azure):** Armazenamento de arquivos e dados não estruturados.
* **Região:** Local geográfico físico onde os data centers estão localizados.

---
Projeto desenvolvido para o desafio da [DIO](https://www.dio.me/).
