# Chat em Tempo Real com Flask e Socket.IO

Este é um projeto simples de chat em tempo real, inspirado em grupos WhatsApp, desenvolvido com Flask no backend e Socket.IO para comunicação em tempo real.

## Informações Acadêmicas:
### Unidade curricular: Automação e Programabilidade em Redes
#### Professor: Wagner Loch
#### Integrantes do Grupo:
- Pedro Lobato
- Thor Lima Galli

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

## Exemplo de tela
![image](https://github.com/user-attachments/assets/5969b3d6-98d1-466c-a48c-1503c615f906)

## Pré-requisitos

- Python 3.7 ou superior.
- Gerenciador de pacotes `pip`.

## Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/chat-flask-socketio.git
   cd chat-flask-socketio
   ```

2. **Crie um ambiente virtual:**
   ```bash
   python -m venv venv
   ```

3. **Ative o ambiente virtual:**

   No Linux/macOS:
   ```bash
   source venv/bin/activate
   ```

   No Windows:
   ```bash
   venv\Scripts\activate
   ```

4. **Instale as dependências do projeto:**
   ```bash
   pip install flask flask-socketio
   ```

5. **Inicie o servidor Flask:**
   ```bash
   python app.py
   ```

6. **Acesse o projeto no navegador:**

   Abra o navegador e acesse: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## Estrutura do Projeto

```plaintext
chat-flask-socketio/
├── static/
│   ├── styles.css    # Arquivo CSS para estilização
├── templates/
│   ├── index.html    # Arquivo HTML principal
├── app.py            # Código do backend com Flask e Socket.IO
├── README.md         # Documentação do projeto
