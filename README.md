## Link do deploy: https://capitani.vercel.app/

## Web

![](https://github.com/pedropbazzo/Capitani/blob/master/src/assets/web.PNG)

## Responsivo - Iphone

![](https://github.com/pedropbazzo/Capitani/blob/master/src/assets/iphone.PNG)

## Responsivo - Ipad

![](https://github.com/pedropbazzo/Capitani/blob/master/src/assets/ipad.PNG)

## Instalar o aplicativo.

  - A verificação da instalação do nodeJS é o node -v.
  - npm install
  - npm start

# Usando Docker

 três etapas de métodos usando docker.
 
 1. docker local as próximas etapas
  - npm run build ou ng build --prod
  - construção de imagem docker -t capitani.
  - docker run -p 3000: 80 --rm capitani
 
esta etapa dois é a criação de referência e a geração do nome do contêiner capitani. A terceira etapa é executar a máquina localhost é a porta 3000 exemplo localhost: 3000




## Servidor de desenvolvimento
Execute `npm start` para um servidor de desenvolvimento. Navegue até `http: // localhost: 4200 /`. O aplicativo será recarregado automaticamente se você alterar qualquer um dos arquivos de origem.

## Code scaffolding

Execute `ng generate component-name` para gerar um novo componente. Você também pode usar `ng generate diretiva / pipe / serviço / classe`.

## Construir

Execute `ng build` para construir o projeto. Os artefatos de construção serão armazenados no diretório `dist /`. Use o sinalizador `-prod` para uma construção de produção.

## Executando testes de unidade

Execute `ng test` para executar os testes de unidade via [Karma] (https://karma-runner.github.io).

## Executando testes ponta a ponta

Execute `ng e2e` para executar os testes de ponta a ponta via [Protractor] (http://www.protractortest.org/).
Antes de executar os testes, certifique-se de servir o aplicativo via `ng serve`.

## Implantando em páginas do Github

Execute `ng github-pages: deploy` para implantar no Github Pages.


