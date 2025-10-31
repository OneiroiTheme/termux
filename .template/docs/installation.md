## Installation

1. Clone this repository

    ```bash
    git clone "https://github.com/{{repository.publisher}}/{{repository.repo}}.git" ./termux
    cd ./termux
    ```

2. Remove old theme

    ```bash
    mv ~/.termux/colors.properties ~/.termux/color.properties.bak
    ```

3. Choose a theme to install (e.g. `oneiroi dream`)

    ```bash
    cp ./oneiroi-dream.properties ~/.termux/colors.properties
    ```

4. Restart Termux and enjoy.
