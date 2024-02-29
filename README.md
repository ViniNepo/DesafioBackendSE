# DesafioBackendSE

Olá senhores, sou o Vinicius Nepomuceno, um dos desafiados a criar o projeto para gerar o link de pagamento de um app de comida que nomeei Cantinho do Italiano.

Nesse projeto o objetivo foi desenvolver uma forma dos usuarios a poderem rachar a conta de acordo com os items que cada um escolheu com um frontend mínimo para interação. Porém como desafio tentei desenhar algo mais 
próximo a um frontend real criando ele com Angular e utilizando o framework ElectronJs para simular que um aplicativo. Como a intenção não era criar o frontend em si, criei o mínimo navegavél, porém é possível pegar 
algumas inconsistências, mas nada que comprometa nesse momento para a avaliação.

Como requisito mínimo precisamos ter o NodeJs na versão 20 (utilizada no projeto). Além disso ao fazer o pull do github será preciso rodar o `npm install` e o cli do Angular `npm install -g @angular/cli`.

Feito isso o frontend está pronto para rodar usando o ElectronJs com o comando `npm run electron .`. Importante que o terminal esteja na pasta por o `.` irá buscar o electron dentro do diretório atual.

Para o backend precisamos ter o Java na sua versão 17 (versão utilizada no projeto). Para rodar o projeto basta rodar o arquivo raiz que se encontra dentro do módulo `infrastructure`. Além disso, também tem uma collection
do Postman na raiz do projeto.

### Links dos repositórios git:

Frontend: https://github.com/ViniNepo/frontend-challenge

Backend: https://github.com/ViniNepo/backend-challenge

### Teste

Link do video de teste do sistema se econtra nesse link do drive: https://drive.google.com/drive/folders/16LqA-t30uy9Qoaeh6XpZZ8yHZ04lv4Pq?usp=sharing

Como foi o teste é feio em ambiente sandbox do PayPal deixei configurado por padrão hardcoded o clientID e secret para que seja feita a requisição com sucesso. Outro ponto importante é que para abrir o link
e ser possível ver o valor a pagar é preciso ter uma conta, porém criei uma conta secundária e coloquei como o email que irá fazer o pagamento.

Obs: Para isso vai ser preciso informar a senha que vocês podem pegar entrando em contato comigo pelo LinkedIn ou então criando uma conta sandbox própria e alterando o email no código.