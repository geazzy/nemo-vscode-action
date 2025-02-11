# Nemo VS Code Action



Este repositório contém uma ação personalizada para o gerenciador de arquivos Nemo, permitindo abrir a pasta atual no Visual Studio Code.

### Descrição

No Nemo, ao selecionar com o botão direito um arquivo ou uma pasta, a opção 'Open in VS Code' será exibida. Ao selecioná-la, o VS Code abrirá o arquivo ou a pasta selecionada.

### Instalação

1. Copie o arquivo `vscode.nemo_action` para o diretório `~/.local/share/nemo/actions/` ou `/usr/share/nemo/actions/`.
2. Certifique-se de que o comando `code` do VS Code está disponível no seu PATH.
3. Reinicie o Nemo com:
   ```bash
   nemo -q

---
# Nemo VS Code Action

This repository contains a custom action for the Nemo file manager, allowing you to open the current folder in Visual Studio Code.

### Description

In Nemo, when you right-click on a file or folder, the "Open in VS Code" option will be displayed. When selected, VS Code will open the chosen file or folder.

### Installation

1. Copy the `vscode.nemo_action` file to the `~/.local/share/nemo/actions/` or `/usr/share/nemo/actions/` directory.
2. Ensure that the VS Code `code` command is available in your PATH.
3. Restart Nemo with:
   ```bash
   nemo -q
