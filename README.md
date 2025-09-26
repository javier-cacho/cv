# Javier Cacho CV

Para generar el CV es necesario instalar la herramienta [`hackmyresume`](https://github.com/hacksalot/HackMyResume):

1. hackmyresume -o su fork FluentCV, requieren node 20

    ```sh
    nvm install 20
    nvm use 20
    ```

2. Luego ya se puede instalar el package

    ```sh
    npm install hackmyresume -g
    ```

3. Y para usarlo

    ```sh
    npx hackmyresume build .\javier-cacho_cv_fresh.json TO .\out\javier-cacho_cv.all --theme positive
    ```
