# 💬 Realtime Chat Web

Interface do chat em tempo real desenvolvida em **React.js** + **SignalR**.

## 🚀 Tecnologias Utilizadas
- **React.js + TypeScript**
- **Chakra UI** (UI moderna e responsiva)
- **SignalR Client** (WebSockets)
- **React Query** (Gerenciamento de estado)
- **Zustand** (Gerenciamento de estado global)
- **Axios** (Requisições HTTP)

## 📀 Funcionalidades Principais
✅ **Registro e Login com JWT**  
✅ **Lista de contatos online e offline**  
✅ **Chat em tempo real com WebSockets**  
✅ **Mensagens privadas e em grupo**  
✅ **Histórico de conversas salvo no banco**  
✅ **Indicação de mensagens não lidas**  
✅ **Confirmação de leitura de mensagens**  
✅ **Notificações sonoras e visuais**  
✅ **Tema claro/escuro**  

## 📚 Estrutura do Projeto
```
/realtime-chat-web
  ├── src/
  │   ├── components/   # Componentes reutilizáveis
  │   ├── pages/        # Páginas da aplicação
  │   ├── services/     # Comunicação com backend (API e WebSockets)
  │   ├── store/        # Gerenciamento de estado (Zustand)
  │   ├── App.tsx       # Configuração do React
  │   └── index.tsx     # Inicialização do app
```

## ⚙️ Configuração e Execução

### 1️⃣ Clonar o Repositório
```sh
git clone https://github.com/seu-usuario/realtime-chat-web.git
cd realtime-chat-web
```

### 2️⃣ Instalar Dependências
```sh
npm install
```

### 3️⃣ Configurar a URL do Backend  
No arquivo `src/services/api.ts`, altere a **URL do servidor**.

### 4️⃣ Executar o Projeto
```sh
npm run dev
```

A aplicação estará rodando em `http://localhost:5173`.

---

## 🛠️ WebSockets (SignalR)

### **Eventos do Servidor**
| Evento            | Descrição                                  |
|------------------|------------------------------------------|
| `ReceiveMessage` | Mensagem recebida do backend            |
| `UserConnected`  | Usuário entrou no chat                  |
| `UserDisconnected` | Usuário saiu do chat                   |

### **Eventos do Cliente**
| Evento         | Descrição                                  |
|---------------|------------------------------------------|
| `SendMessage` | Enviar uma nova mensagem ao backend      |
| `JoinRoom`    | Entrar em uma sala específica            |


