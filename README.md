# aws-serverless-lambda-nestjs-holamundo
This is a boiler plate to start developing aws serverless lambda integrated with apigateway locally using the pluging serverless-offline and serverless-plugin-typescript to write your lambda code in typescript code.

Remember before you run the any serverless (sls) command be sure to have installed globally the plugin serverless npm i serverless -g

# plugins needed for this boiler plate

https://www.npmjs.com/package/serverless
https://www.npmjs.com/package/serverless-offline
https://www.npmjs.com/package/typescript
https://www.npmjs.com/package/serverless-plugin-typescript
https://www.npmjs.com/package/@types/aws-lambda

# how to run this boiler plate

open git bash and type npm i to install all dependencies and dev dependencies before typing sls offline that runs the aws serverless aplication locally. Check the console and access the url given corresponding with the function declared on the serverless.yml usually is http://localhost:3000/dev/greetings.