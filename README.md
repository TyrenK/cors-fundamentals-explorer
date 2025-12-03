# 📘 CORS Fundamentals Explorer

## 🚀 Projeto
Este projeto demonstra como funciona o CORS utilizando um **Backend (Node.js + Express)** na porta **8080** e um **Frontend (HTML/JS)** na porta **3000** usando o pacote `serve`.

---

## 📂 Estrutura do Projeto

```
/backend
    server.js

/frontend
    index.html

README.md
```

---

## 🖥️ 1. Como rodar o Backend (porta 8080)

### 📌 Pré-requisitos
- Node.js instalado

### ▶️ Rodar o backend
No terminal:

```bash
cd backend
node server.js
```

Se tudo estiver certo, aparecerá:

```
API Backend rodando em: http://localhost:8080
AGORA PERMITINDO acesso de: http://localhost:3000
```

---

## 🌐 2. Como rodar o Frontend (porta 3000)

O frontend usa o pacote `serve` para criar um servidor estático.

### 📌 Instalar o serve (se necessário)
```bash
npm install -g serve
```

Ou sem instalar globalmente:

```bash
npx serve -l 3000
```

### ▶️ Rodar o frontend
```bash
cd frontend
serve -l 3000
```

Você verá algo como:

```
Serving! Local: http://localhost:3000
```

---

## 🔍 3. Testando o Funcionamento

1. Abra o navegador em **http://localhost:3000**
2. Aperte **F12** e abra o **Console**
3. Clique no botão **Acessar API**
4. Você verá a resposta ou um erro de CORS

---

## ✔️ Resposta Esperada da API

```json
{
  "data": "Mensagem secreta da API em 8080 - COM PERMISSÃO CORS!"
}
```

---

## 🛠️ Tecnologias utilizadas
- Node.js  
- Express  
- CORS  
- HTML + JavaScript  
- serve (para o frontend)

---

## 📄 Licença
Projeto criado para fins educacionais.
