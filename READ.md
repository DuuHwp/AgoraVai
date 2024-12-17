#Trabalho Projeto Integrador 2024

##***Apresentação Breve***

Uma aplicação web desenvolvida em Python, HTML e CSS. Feita para ajudar o usuário a descobrir os requisitos mínimos e recomendados de um jogo e saber se roda ou não em seu computador. Além disso, fornece um canal de ajuda para comunicação com o usuário via e-mail.

##***Objetivo***

Evitar que o usuário adquira um jogo no qual o computador dele não tenha o hardware necessário para rodá-lo.

##***Funcionalidades***

Escolha um jogo da lista no menu principal.

Descubra as requisitões mínimas e recomendadas do jogo escolhido.

Envie uma mensagem via e-mail para tirar suas dúvidas.

##***Tecnologias Utilizadas***

***Linguagens:*** Python, CSS, HTML e um arquivo JSON.
***Programas:*** Git, Visual Code, NodeJS, Vercel, GitHub e Prompt de comando.

##***Passo a Passo para Rodar a Aplicação***

Abra seu Git e crie uma pasta:
```bash
mkdir <nome da sua pasta>
```
Navegue até a pasta criada:
```bash
cd <nome da sua pasta>
```
Clone o repositório:
```bash
git clone https://github.com/DuuHwp/AgoraVai.git
```
Crie uma conta no Vercel e vincule ao GitHub:
https://vercel.com/

Volte ao Git e crie um repositório no GitHub. Commite a pasta clonada:

Configure seu usuário:
```bash
git config --global user.name "Seu Nome"
```
```bash
git config --global user.email "seu-email@exemplo.com"
```
Inicialize o repositório:
```bash
git init
```
```bash
git remote add origin <seu link remoto>
```
Adicione e commite os arquivos:
```bash
git add .
```
```bash
git commit -m "Sua mensagem"
```
```bash
git push -u origin master
```
Obs.: Caso o branch seja main, use:
```bash
git push -u origin main
```
Instale o NodeJS:
[Download NodeJS](https://nodejs.org/en/download/prebuilt-installer)

Abra o CMD na pasta do projeto (onde está o app.py) e execute os seguintes comandos:

Instale o Vercel:
```bash
npm i -g vercel
```
Crie e ative um ambiente virtual:
```bash
python -m venv venv
```
```bash
venv\scripts\activate
```
Instale o Flask e dependências:
```bash
pip install flask
```
```bash
pip install -r requirements.txt
```
Se houver erro no pip, atualize com:
```bash
python.exe -m pip install --upgrade pip
```
Execute o Vercel para deploy:
```bash
vercel
```
Realize login pelo GitHub.

Após isso, voltando para o 'cmd', estará a mensagem de 'Set up and deploy <a pasta do projeto>' Você digitará 'y' e aperte 'Enter'

Agora aparecerá o nome que você cadastrou no Vercel, não tem como alterar pelo cmd, então apenas aperte 'Enter'

Agora irá perguntar se existe link no projeto, pode digitar 'n' e apertar 'Enter'

E agora ele irá perguntar qual será o nome do projeto. Lembrando que não pode letras maiúsculas, então darei um nome de recomendação:
```bash
projeto-pi-match-games
```
Copie esse nome para o nome do projeto, se for de seu agrado.

Depois disso irá perguntar em qual diretório está localizado, como já estamos trabalhando na pasta, basta apertar 'Enter'

Agora ele irá perguntar se precisa fazer algumas modificações em alguns comandos, pode digitar 'n' e apertar 'Enter'

Agora basta esperar ele fazer o deploy e o building da aplicação, que irá disponibilizar o link para você:

Pelo link Inspect, clique em Visit ou na miniatura da aplicação para acessá-la.

Pelo link Production ou Preview, você entrará direto na aplicação.

Obs.: Caso ocorra erro 500, certifique-se de que o banco de dados PostgreSQL esteja ligado.

##***Conclusão***

Pronto! A aplicação está configurada. Agora você pode:

Escolher um jogo para verificar suas especificações mínimas e recomendadas.

Clicar no ponto de interrogação no canto inferior direito para preencher o canal de comunicação via e-mail.

Projeto Integrador 2024 - Sistema desenvolvido para facilitar a vida dos gamers!

Desenvolvido por: Eduardo Ternoski de Camargo, Murilo Henrique do Nascimento e César Andrade 
