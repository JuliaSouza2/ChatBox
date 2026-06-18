# 🤖 HR Buddy – Chatbot Inteligente de Recursos Humanos

Projeto desenvolvido durante a **Imersão de Agentes de IA** da **Oracle Next Education (ONE)** em parceria com a **Alura**.

O HR Buddy é um chatbot inteligente criado no **n8n** para responder dúvidas frequentes de Recursos Humanos. O agente utiliza IA generativa, consulta uma base de conhecimento e acessa informações dos colaboradores armazenadas em um banco de dados MySQL.

## 🚀 Funcionalidades

* 💬 Atendimento automatizado em português.
* 🤖 Agente de IA para responder dúvidas de RH.
* 📚 Consulta a uma base de conhecimento (Vector Store).
* 🗄️ Consulta de informações de funcionários no MySQL.
* 🧠 Memória de contexto durante a conversa.
* 🌐 Arquitetura baseada em workflows do n8n.

## 🛠️ Tecnologias

* n8n
* IA Generativa
* Cohere
* MySQL
* Vector Store
* AI Agent

## 📂 Estrutura do projeto

```text
ChatBox/
│
├── workflows/
│   └── hr-buddy-workflow.json
├── README.md
└── .gitignore
```

## ⚙️ Como utilizar

1. Clone este repositório.
2. Importe o workflow no n8n.
3. Configure as credenciais do Cohere.
4. Configure a conexão com o banco MySQL.
5. Adicione os documentos da base de conhecimento ao Vector Store.
6. Execute o workflow e interaja com o chatbot.

## 📌 Observações

As credenciais de acesso ao Cohere e ao MySQL não são compartilhadas neste repositório por questões de segurança. Após importar o workflow, é necessário configurar suas próprias credenciais no n8n.

## 👩‍💻 Desenvolvido por

**Julia Souza**

Projeto desenvolvido como atividade prática da Imersão de Agentes de IA – Oracle Next Education (ONE) + Alura.
