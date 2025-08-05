# Tech Challenge - Fase 2

Repositório da **Fase 2** do **Tech Challenge** da **Pós tech em Frontend Engineering** - **FIAP**.

Acesso ao vídeo de demonstração e entrega do tech challenge: [Link para o vídeo no Youtube](https://youtu.be/E3U1MUqCzGA)

Desenvolvido por Alexsander Chagas Dambros | [LinkedIn](https://www.linkedin.com/in/alexsandercdambros/)

---

## Instruções para baixar e rodar a aplicação

Essa aplicação usará o docker para rodar de forma mais rápida, portanto é importante instalar e configurar ele corretamente. Para saber mais acesse o [site oficial do Docker](https://www.docker.com/).

Caso você prefira não utilizar o docker e rodar manualmente, precisará instalar o Node, preferencialmente na versão 22.17.1. Faça o download através do [site oficial do node](https://nodejs.org/pt).

### Clonagem do projeto
    
Para começar clone esse repositório e os repositórios das demais aplicações em sua máquina.

#### 1. Clonagem o repositório principal:

- Repositório principal - https://github.com/AlexsanderCDambros/tech-challenge-fase-dois.git
  - `git clone https://github.com/AlexsanderCDambros/tech-challenge-fase-dois.git`

#### 2. Clonagem dos demais repositórios:

Para o docker compose funcionar, é necessário que você clone os demais repositórios dentro do principal, por isso, abra um terminal dentro da pasta **tech-challenge-fase-dois**, ou no mesmo terminal que você fez o git clone, navegue para a pasta do projeto com o comando:

`cd tech-challenge-fase-dois`

Depois disso, continue com os comandos abaixo para clonar todos os repositórios:

- Chassi - https://github.com/AlexsanderCDambros/TC2-chassi
  - `git clone https://github.com/AlexsanderCDambros/TC2-chassi.git`
- Login - https://github.com/AlexsanderCDambros/TC2-login
  - `git clone https://github.com/AlexsanderCDambros/TC2-login.git`
- Menu - https://github.com/AlexsanderCDambros/TC2-menu
  - `git clone https://github.com/AlexsanderCDambros/TC2-menu.git`
- Início - https://github.com/AlexsanderCDambros/TC2-inicio
  - `git clone https://github.com/AlexsanderCDambros/TC2-inicio.git`
- Transações - https://github.com/AlexsanderCDambros/TC2-transacoes
  - `git clone https://github.com/AlexsanderCDambros/TC2-transacoes.git`
- Cópia API - https://github.com/AlexsanderCDambros/TC2-Copia-API
  - `git clone https://github.com/AlexsanderCDambros/TC2-Copia-API`

---

### Instalação utilizando o docker

Se optar pela utilização do docker, no mesmo terminal da clonagem, ou em um novo que esteja na pasta **tech-challenge-fase-dois**, execute o comando:

`docker-compose up --build`

Esse processo pode demorar um bom tempo, pois são muitas imagens que o docker terá que criar e executar.

#### Abrir a aplicação em um navegador

Quando o processo terminar, para abrir a aplicação, basta ir em um navegador e abrir o endereço:

`http://127.0.0.1:9000/` ou `http://localhost:9000/`

---

### Instalação manual sem o docker

#### Instalação das dependências 

Depois de ter os arquivos em sua máquina, entre em cada uma das pastas dos projetos através de um terminal (cmd, git Bash, etc), e rode o seguinte comando para instalar as dependências do projeto:

`npm install`

Esse processo deve demorar alguns minutos.

#### Rodar o projeto em desenvolvimento

Quando o processo de instalação terminar será necessário para rodar as aplicações.

- Chassi
  - `npm start`
- Demais aplicações
  - `npm run dev`

#### Abrir a aplicação em um navegador

Para abrir a aplicação, basta ir em um navegador e abrir o endereço:

`http://127.0.0.1:9000/` ou `http://localhost:9000/`
