# aula-3
const readline = require ('readline');
const1 = readline.createInterFace({
  input: Process.stdin,
  output:  Process.stdout
});

r1.question('Qual é o seu nome ?' , (nome) => {
   console.log (`Olá, $ {nome}! Bem-vindo ao Node.js`);
   r1.close();
}) 
