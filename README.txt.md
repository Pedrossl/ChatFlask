0# Chat em Tempo Real com Flask e Socket.IO

Este é um projeto simples de chat em tempo real, inspirado no WhatsApp, desenvolvido com Flask no backend e Socket.IO para comunicação em tempo real.

## Funcionalidades

- Comunicação em tempo real entre usuários.
- Mensagens diferenciadas para o remetente e destinatários.
- Formulário fixado na parte inferior da página.
- Design inspirado em aplicativos de mensagens modernas.

## Tecnologias Utilizadas

- **Flask**: Framework web leve para Python.
- **Flask-SocketIO**: Extensão para comunicação em tempo real via WebSocket.
- **HTML5 e CSS3**: Estrutura e estilização da página.
- **JavaScript**: Lógica do cliente para comunicação via Socket.IO.

## Pré-requisitos

- Python 3.7 ou superior.
- Gerenciador de pacotes `pip`.

## Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/chat-flask-socketio.git
   cd chat-flask-socketio
Crie um ambiente virtual:

bash
Copiar código
python -m venv venv
Ative o ambiente virtual:

No Linux/macOS:
bash
Copiar código
source venv/bin/activate
No Windows:
bash
Copiar código
venv\Scripts\activate
Instale as dependências do projeto:

bash
Copiar código
pip install flask flask-socketio
Inicie o servidor Flask:

bash
Copiar código
python app.py
Acesse o projeto no navegador:

Abra o navegador e acesse: http://127.0.0.1:5000
Estrutura do Projeto
plaintext
Copiar código
chat-flask-socketio/
├── static/
│   ├── styles.css    # Arquivo CSS para estilização
├── templates/
│   ├── index.html    # Arquivo HTML principal
├── app.py            # Código do backend com Flask e Socket.IO
├── README.md         # Documentação do projeto