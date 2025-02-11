# Nemo VS Code Action



Este repositório contém uma ação personalizada para o gerenciador de arquivos Nemo, permitindo abrir a pasta atual no Visual Studio Code.

### Descrição

Ao clicar com o botão direito no fundo de uma pasta no Nemo ou ao selecionar um arquivo (ou pasta) com o botão direito, a ação **"Open in VS Code"** aparecerá e, ao selecioná-la, o VS Code será aberto com a pasta atual.

### Instalação

1. Copie o arquivo `vscode.nemo_action` para o diretório `~/.local/share/nemo/actions/` ou `/usr/share/nemo/actions/`.
2. Certifique-se de que o comando `code` do VS Code está disponível no seu PATH.
3. Reinicie o Nemo com:
   ```bash
   nemo -q


---
This repository contains a custom action for the Nemo file manager, allowing you to open the current folder in Visual Studio Code.

### Description
When you right-click on the background of a folder in Nemo or right-click on a selected file (or folder), the "Open in VS Code" action will appear, and selecting it will open VS Code with the current folder.

### Installation
1. Copy the vscode.nemo_action file to the directory ~/.local/share/nemo/actions/ or /usr/share/nemo/actions/.
2. Ensure that the VS Code code command is available in your PATH.
3. Restart Nemo with:
  ``` bash
  nemo -q
