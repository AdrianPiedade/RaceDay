# RaceDay
Atividade simples usando JS

Race Day

A corrida anual do Senai está chegando! Este ano, temos muitos
participantes. Você foi contratado para escrever um programa que registrará
corredores para a corrida e dará instruções no dia da corrida. Eis como funciona
o nosso registro. Existem corredores adultos (com mais de 18 anos) e jovens (com
menos de 18 anos). Eles podem se registrar cedo ou tarde. Os corredores são
designados um número de corrida e horário de início com base na idade e
registro.
Número da corrida:
• Adultos que se registram cedo recebem um número de corrida igual ou
acima de 1000.
• Todos os outros recebem um número abaixo de 1000.
Horário de início:
• Os adultos registados correm às 9h30 ou às 11h00.
o Adultos que se registram cedo correm às 9h30.
o Adultos que se registram tarde correm às 11h00.
• Os jovens registados correm às 12h30 (independentemente do registro).
Mas não planejamos para corredores que têm exatamente 18 anos!
Vamos resolver isso no final do projeto.

1-Os números de corrida são atribuídos aleatoriamente. Fornecemos o
código necessário no topo do arquivo. Verifique esta tarefa após ler essa linha.
Você pode ler a dica se quiser aprender como funciona!
let raceNumber = Math.floor(Math.random() * 1000);

2-Crie uma variável que indique se um corredor se registrou cedo ou não.
Defina-a como um valor booleano. Você mudará isso mais tarde ao testar
diferentes condições de corredor.

3-Crie uma variável para a idade do corredor e defina-a como um número.
Você mudará isso mais tarde ao testar diferentes condições de corredor.
4-Crie uma instrução de fluxo de controle que verifica se o corredor é
adulto E se registrou cedo. Adicione 1000 ao número de corrida se isso for
verdade.
5-Crie uma instrução de fluxo de controle separada abaixo da primeira
(começando com "if" novamente). Esta instrução verificará a idade e o tempo de
registro para determinar o horário da corrida. Para corredores com mais de 18
anos que se registraram cedo, registre uma declaração no console informando
que eles correrão às 9h30. Inclua o número de corrida deles.
6-“Adultos que se registram tarde correm às 11h00" Já que já verificamos
os adultos que se registram cedo, podemos escrever uma declaração assim:
senão se o corredor tem mais de 18 anos E não se registrou cedo, eles correrão
às 11h00. Escreva a correspondente declaração else if. Dentro disso, registre uma
string no console informando que eles correrão às 11h00. Inclua o número de
corrida deles.
7-“Jovens registados correm às 12h30 (independentemente do registro)"
Para pessoas com menos de 18 anos, registre uma declaração no console
informando que elas correrão às 12h30. Inclua o número de corrida delas.
8-Insira diferentes combinações de valores para as duas variáveis que você
criou e execute seu código várias vezes. Verifique se as declarações corretas estão
sendo impressas no console! Você pode verificar seu trabalho usando os
exemplos fornecidos na dica.
9-Não se esqueça dos corredores com exatamente 18 anos de idade!
Adicione uma declaração else que registre uma declaração no console
informando ao corredor para ver a mesa de registro.
