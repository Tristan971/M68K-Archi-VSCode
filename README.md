# M68K-Archi-VSCode
Sample configuration files for the M68K class of Architecture at EPITA

## Installation instructions
- Put the "68000" folder in your $HOME (~) directory. Or anywhere, but that is subject to making bugs appear as it was designed to stay there.

- Intall Visual Studio Code from https://code.visualstudio.com/

- Enable syntax highlighting and file recognition with the extension m68k from here https://marketplace.visualstudio.com/items?itemName=steventattersall.m68k
- create a .vscode folder at the root of any assembly project you might have, put the tasks.json from the dot_vscode directory in it

- Now you can :
    - build with :
      - `Cmd/Ctrl+Shift+B`
      - `Cmd/Ctrl+Shift+P -> Run Build Task`
      - `Cmd/Ctrl+Shift+P` and then `Run Task -> Assembly`
    - debug with :
      - `Cmd/Ctrl+Shift+P -> Run Test Task`
      - `Cmd/Ctrl+Shift+P` and then `Run Task -> Debug`
      
      
      
## Copyright
- Extension from: https://github.com/stevenjs/M68k-Assembly
- Debugger from David Bouchet ( http://debug-pro.com/epita/s3/en/ )
