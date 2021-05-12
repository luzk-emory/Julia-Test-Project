# How to generate a Julia Project

This is a test project for Julia

- In package mode of Julia, type

    ```julia
    generate PROJECT_NAME
    ```

- For local use, `cd PROJECT_NAME` and `] activate .`
  
- Try `import TestProg; TestProg.greet() ` to test.
  
- For global use, upload to github
    - In package mode of Julia, type

    ```julia
    add git@github.com:luzk-emory/PROJECT_NAME.git
    ```

    - Try `import TestProg; TestProg.greet() ` to test.
    - Note: have to configure SSH for Git first.
