- Shell: [Fish](https://fishshell.com/)
    ```sh
    clear &&
    sudo apt-add-repository ppa:fish-shell/release-3 &&
    sudo apt update &&
    sudo apt install fish
    ```
- Manager: [Fisher](https://github.com/jorgebucaran/fisher)
    ```sh
    clear &&
    curl -sL https://raw.githubusercontent.com/jorgebucaran/fisher/main/functions/fisher.fish | source &&
    fisher install jorgebucaran/fisher
    ```
- Theme: [Tide](https://github.com/IlanCosman/tide)
    ```sh
    clear &&
    fisher install IlanCosman/tide@v6
    ```
- Plugins:
    - [Async prompt](https://github.com/acomagu/fish-async-prompt)
    - [z](https://github.com/jethrokuan/z)
