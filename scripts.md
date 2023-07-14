npm run start:dev 

- apaga a pasta dist e roda a aplicação de novo
rm -rf dist; npm run start:dev

- no poweshell
Remove-Item -Recurse -Force dist; npm run start:dev

- criando o modulo do todo com cli 
nest g module app/todo

- criando controllers com a cli
nest g controller app/todo

- criando service com a cli
nest g service app/todo