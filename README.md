# SMART HOME
Aplicação feita com o uso de websockets, criando uma casa interativa com sala, cozinha e quarto 

## Instalação

Siga os passos abaixo para configurar o ambiente e executar o projeto em sua máquina local.

### Passos para instalar caso utilize o Docker

1. Clone o repositório:
   ```bash
   git clone https://github.com/eooheitor/smart-home.git
2. Instale os pacotes no frontend:
   ```bash
   cd frontend && npm install
4. Instalar os pacotes no backend e iniciar o servidor:
   ```bash
   cd .. && cd backend && npm install && npm install nodemon -g && npm run start
5. Inicie o servidor no frontend
   ```bash
   cd .. && cd frontend && npm run dev
