# TypeScript Ready Environment
to start TypeScript Projects really fast :)

## Setup
- **Step1:** make sure nodejs and TypeScript are installed.
- **Step2:** create the project directory
- **Step3:** inside the project directory -> `git clone https://github.com/abdelrahman146/newTS`
- **Step4:** `npm install`

## Project Structure
`/src/` is the development folder (all TypeScript files should be here)
`/dist/` is the output folder (the compiled javascript)

## Usefull Scripts
`npm run build` to build the dist folder.
`npm run dev` run a development server where the code can be tested without the need of compiling.
`npm run serve` build the app and run it.

## Configuration
- to change the name or change the directory of the production folder. go to `tsconfig.json` and change `"outDir": "./dist",` to the desired location or name.

- to change the name or change the directory of the source code folder. go to `tsconfig.json` and change `"baseUrl": "./src",` to the desired location or name.
