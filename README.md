# How to generate a Julia Project

This is a test project for Julia

- In package mode of Julia, type

    ```julia
    generate PROJECT_NAME
    ```

- For local use, `cd PROJECT_NAME` and `] activate .`
  
  - Try `import TestProg; TestProg.greet() ` for a test run.
  
- For global use, upload to github
    - In package mode of Julia, type
        ```julia
        add git@github.com:luzk-emory/PROJECT_NAME.git
        ```
        Note: must configure SSH for Git first. Reference link [here](https://docs.github.com/en/github/getting-started-with-github/caching-your-github-credentials-in-git)
    
    - Try `import TestProg; TestProg.greet() ` for a test run.

