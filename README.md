# Sprint 3 - API de Filmes 🎬🚀

## Visão Geral

Bem-vindo ao repositório da **Sprint 3** do nosso grupo de estudo! Nesta sprint, vamos aprender os conceitos básicos de **Backend** utilizando **Express.js**, **Prisma** e **Neon DB**. O objetivo é desenvolver uma API para filmes onde o usuário poderá **criar**, **editar** e **deletar** reviews para um filme. 💡✨

---

## 📚 Materiais e Tutoriais

Aqui você encontrará links e referências para facilitar o aprendizado:
- **Express.js**: [Tutorial do Express.js](#) 🎥
- **Prisma**: [Tutorial do Prisma](#) 🎥
- **Neon DB**: [Documentação do Neon DB](#) 📖

*Obs: Substitua os links pelos URLs corretos conforme necessário.*

---

## 🚀 Descrição da Sprint

### Objetivo
Desenvolver uma API que permita ao usuário:
- Listar filmes 📜
- Criar novas reviews 🎯
- Editar reviews existentes ✏️
- Deletar reviews indesejadas 🗑️

### Funcionalidades Principais
- **CRUD** para reviews de filmes
- Validação de dados com **middlewares**
- Integração com **Neon DB** utilizando **Prisma**

---

## 📺 Vídeos

- [RESTful APIs in 100 Seconds // Build an API from Scratch with Node.js Express](https://www.youtube.com/watch?v=-MTSQjw5DrM&t=260s&ab_channel=Fireship)

---

# Verbos HTTP (Métodos HTTP)  
Os verbos HTTP definem a ação que um cliente deseja executar em um recurso específico (identificado por uma URL). São essenciais para comunicação web e operações **CRUD** (*Create, Read, Update, Delete*) em APIs RESTful.

---

## Principais Verbos HTTP  

### **GET**  
- **Função**: Solicitar dados de um recurso (apenas leitura).  
- **Características**:  
  - Não altera o estado do servidor.  
  - Dados enviados via URL (parâmetros de query).  
  - Cacheável e seguro (sem efeitos colaterais).  

### **POST**  
- **Função**: Criar um novo recurso ou enviar dados para processamento.  
- **Características**:  
  - Modifica o estado do servidor.  
  - Dados enviados no corpo da requisição (*body*).  

### **PUT**  
- **Função**: Atualizar **totalmente** um recurso existente.  
- **Características**:  
  - Substitui todos os dados do recurso.  
  - Requer envio de todos os campos, mesmo não alterados.  

### **PATCH**  
- **Função**: Atualizar **parcialmente** um recurso.  
- **Características**:  
  - Modifica apenas os campos especificados.  

### **DELETE**  
- **Função**: Remover um recurso permanentemente.  

---

## Respostas HTTP  
O servidor responde com os seguintes componentes:  

### **Status Code**  
Código de 3 dígitos que indica o resultado da requisição:  

| Categoria          | Exemplos                   | Descrição                          |  
|---------------------|----------------------------|------------------------------------|  
| **2xx (Sucesso)**   | `200 OK`, `201 Created`    | Requisição bem-sucedida.           |  
| **3xx (Redirecionamento)** | `301 Moved Permanently` | Indica redirecionamento de URL.    |  
| **4xx (Erro do cliente)** | `404 Not Found`, `400 Bad Request` | Erros causados pelo cliente. |  
| **5xx (Erro do servidor)** | `500 Internal Server Error` | Falhas no lado do servidor.    |  

---

---

## 🛠️ Tecnologias Utilizadas

- **Node.js** com **Express.js**
- **Prisma ORM**
- **Neon DB**
- **JavaScript** (ou **TypeScript**, se preferir)

---

## 📝 Instruções para Configuração do Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. **Instale as dependências:**
   ```bash
   npm install
   ```
3. **Configure as variáveis de ambiente:**
   - Crie um arquivo `.env` com as configurações do banco de dados e demais chaves.
4. **Execute as migrations do Prisma:**
   ```bash
   npx prisma migrate dev
   ```
5. **Inicie o servidor:**
   ```bash
   npm run dev
   ```

---

## 🎯 Próximos Passos

- Adicionar testes unitários 🧪
- Implementar autenticação e autorização 🔒
- Melhorar a documentação da API 📖

---

Divirta-se codando e bons estudos! 🚀✨

--------------------------------------------------