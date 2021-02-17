# Typescript GUI Template
This is a template repository for new projects. When you create a new repository from this template, follow these instructions:

1. Make sure the `.gitignore` file is appropriate for your project
2. Update package.json properties to describe the package:
   - `name`
   - `version`
   - `description`
3. Setup `@nengo/commitlint-config-nengo`
   - Instructions [here](https://github.com/nengo/commitlint-config-nengo#setup)
4. Install dependecies with `npm install`
5. Setup testing:
   1. Remove the `--passWithNoTests` flag from `test-coverage` script in `package.json`
   2. The project defaults to checking for tests in the `/utils` folder. You can modify the folders to check for tests in `package.json`
   ```json
   "jest":{
      "collectCoverageFrom": [
         "<rootDir>/src/utils/**/*.ts",
         ...
      ]
   }
   ```
6. Replace the text in `README.md` with text for the new repository.