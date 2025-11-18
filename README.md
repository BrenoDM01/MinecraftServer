# MinecraftServer

Passos para configuração do servidor:

- 1 - Instalando o Crafty Control:
    - 1.1 - Acesse <https://craftycontrol.com/>;
    - 1.2 - Vá na opção de instalação para Linux;
    - 1.3 - Execute no terminal o comando <sudo apt update && sudo apt upgrade && sudo apt install git>;
    - 1.4 - Execute no terminal o comando <pip install distro>;
    - 1.5 - Execute no terminal o comando <git clone https://gitlab.com/crafty-controller/crafty-installer-4.0.git>;
    - 1.6 - Execute no terminal o comando <cd crafty-installer-4.0>;
    - 1.7 - Execute no terminal o comando <sudo ./install_crafty.sh>;
    - 1.8 - Instalar o Crrafty no caminho: </workspaces/MinecraftServer/minecraft>.

- 2 - Configuração do Cafty:
    - 2.1 - Inicie o serviço com o comando </workspaces/MinecraftServer/minecraft/run_crafty.sh>;
    - 2.2 - Clique na opção de abrir a aplicação pelo navegador;
    - 2.3 - Informe que esqueceu a senha para gerar uma nova;
    - 2.4 - Pegue as credenciais informadas no terminal;
    - 2.5 - Altere a senha do user admin;
    - 2.6 - Faça logout e login com a senha nova;
    - 2.7 - Crie e configure o servidor.

- 3 - Instalação do PlayIt:
    - 3.1 - Acesse <https://playit.gg/>;
    - 3.2 - Clique em "download";
    - 3.3 - Acesse a aba "Linux";
    - 3.4 - Copie os comandos de instalação;
    - 3.5 - Crie um novo terminal;
    - 3.6 - Execute os comandos de instalação;
    - 3.7 - Ao finalizar, execute o comando <playit> no terminal e acesse o link sugerido;
    - 3.8 - Crie uma conta (se necessário) e acesse o novo link sugerido após o login;
    - 3.9 - Crie o tunel assim que o serviço da PlayIt permitir;


- Comandos Úteis:
    - Inicialização do Crafty: </workspaces/MinecraftServer/minecraft/run_crafty.sh>;
    - Atualização do Crafty: </workspaces/MinecraftServer/minecraft/update_crafty.sh>.
