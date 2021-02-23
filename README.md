# Typescript project template

This is a template repository for new Typescript projects.
When you create a new repository from this template, follow these instructions:

1. Make sure the `.gitignore` file is appropriate for your project.

2. Replace the TODO keys like `name` and `description` in `package.json`.

3. [Set up `@nengo/commitlint-config-nengo`.](https://github.com/nengo/commitlint-config-nengo#setup)

4. Install dependecies with `npm install`.

5. Set up testing in `package.json`:

   1. Remove the `--passWithNoTests` flag from the `test-coverage` script.

   2. Modify the test collection rules, if appropriate.

      ```json
      "jest": {
         "collectCoverageFrom": [
            "<rootDir>/src/utils/**/*.ts",
            ...
         ]
      }
      ```

6. Replace the text in `README.md` with text for the new repository.
