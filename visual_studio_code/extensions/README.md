## Export

`$ code --list-extensions | tee extensions.txt`

## Import

1. Copy the previously exported extensions.txt file to the new machine.
2. Open Visual Studio Code on the new machine and open a terminal.
3. In the terminal, navigate to the directory where the extensions.txt file is located.
4. Paste and execute the following command in the terminal:
   `cat extensions.txt | xargs -L 1 code --install-extension`
