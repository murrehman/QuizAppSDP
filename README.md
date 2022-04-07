# QuizzApp
Group Project - SDP


# Nothing to see here

Initialization: node ./bin/www


## To create a new migration file use the following command:

npx sequelize-cli migration:create --name added-candidate-associations

## To run the pending migration files:

npx sequelize-cli db:migrate


## To generate a new Model with its own migration (example):

npx sequelize-cli model:generate --name Question --attributes quizId:int,questionType:string,questionText:text,points:decimal,useQuestionPoints:boolean,answersData:json,questionData:json
