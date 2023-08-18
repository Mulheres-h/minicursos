# Instalação do Visual Studio Code no Linux:

**Passo 1: Adicionar o Repositório do VSCode (Ubuntu)**

1. Abra o terminal.

2. Execute os seguintes comandos para importar a chave GPG do repositório Microsoft:

   ```bash
   curl -sSL https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > microsoft.gpg
   sudo mv microsoft.gpg /etc/apt/trusted.gpg.d/microsoft.gpg
   ```

3. Adicione o repositório do VSCode às fontes do apt:

   Para Ubuntu 20.04:

   ```bash
   sudo sh -c 'echo "deb [arch=amd64] https://packages.microsoft.com/repos/code stable main" > /etc/apt/sources.list.d/vscode.list'
   ```

   Para outras versões do Ubuntu, verifique a documentação oficial.

**Passo 2: Instalar o VSCode**

1. Atualize a lista de pacotes e instale o VSCode:

   ```bash
   sudo apt update
   sudo apt install code
   ```

**Passo 3: Executar o VSCode**

Digite `code` no terminal para iniciar o Visual Studio Code.

## Instalação do Visual Studio Code no Windows:

**Passo 1: Baixe o Instalador do VSCode**

1. Acesse o site oficial do Visual Studio Code em https://code.visualstudio.com/.
2. Clique no botão "Download for Windows" (Baixar para Windows) para baixar o instalador.

**Passo 2: Execute o Instalador**

1. Localize o arquivo baixado e execute-o.
2. Siga as instruções do instalador. Você pode aceitar as configurações padrão.

**Passo 3: Inicie o VSCode**

Após a instalação, o Visual Studio Code estará disponível no menu Iniciar. Clique nele para iniciar o programa.

Lembrando que os passos fornecidos são para uma instalação padrão. Você pode personalizar as configurações durante a instalação, se necessário.

Com o VSCode instalado, você estará pronto para começar a escrever código e aproveitar todas as funcionalidades oferecidas por essa poderosa ferramenta de desenvolvimento.