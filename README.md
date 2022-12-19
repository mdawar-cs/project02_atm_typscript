# TypeScript CLI ATM
 Simple Command Line ATM using TypeScipt, Node.js and Inquirer.

Please make sure Node and Typscript is already installed.

Initailize Json Package by following command:
        `npm init -y`

Initailize TypeScript Project by following command:
        `tsc --init`

Goto packge.json and add  "type": "module"
Goto tsconfig.json change target to "target": "ES2022" , "module": "NodeNext" and "moduleResolution": "NodeNext"

To add node types dependency by following command:
        `npm i @types/node -D`

To Install Inquirer dependency by following command:
        `npm i inquirer`

To Install types Inquirer dependency by following command:
        `npm i --save-dev @types/inquirer`

To Install chalk dependency by following command:
        `npm i chalk chalk-animation`

To Install types Inquirer dependency by following command:
        `npm i -D @types/chalk @types/chalk-animation`

To Install all packages at once define in package.json:
        `npm i`

For only running this ATM:
        `npx project02_atm_typscript`
