# VS Code 💻💾

## Atalhos encontrados
### git remote add origin https://github.com/suaURLAqui/.git = este comando serve para definir uma origin do repositório remoto
### git branch -m "nomeNovaBranch" = este comando serve para criar branchs no repositório remoto
### SHIFT + ALT + Down Arrow = replica a linha atual em baixo
### SHIFT + ALT + A = comentário em bloco com várias linhas de uma só vez
### CTRL + ; = comenta linha a linha individualmente
### CTRL + K S = abre a lista de atalhos do Vs Code
### CTRL + ALT = permite selecionar mais de uma linha para indentar
### CTRL + X = exclui a linha atual
### CTRL + espaço = autocomplete
### ALT + Up Arrow or Down Arrow = move a linha na direção que preferir
### ALT + SHIFT + F = indenta de forma automática
### && = Com o uso do mecanismo && (and) é possível concatenar vários comandos na mesma linha
### code . = Ao abrir uma pasta com arquivos do VS Code de um Git Bash Here e apos isso digite (code .) este comando permite abrir todos os arquivos da pasta atual no VS Code
### https://github.com/YuriAugusto/Analisador-de-Numeros //Aqui tenho um repositório público
### https://github1s.com/YuriAugusto/Analisador-de-Numeros //Ao inserir "1s" antes de ".com" o GitHub exibe o código no Browser
### Vs Code Shortcuts https://jsmanifest.com/21-vscode-shortcuts-to-code-faster-and-funner/#:~:text=Moving%20a%20line%20up%20or,Down%20Arrow%20)%20to%20move%20down

# Comandos Git e Terminal 👾👨‍💻

## Configuração inicial Git
### git init //inicia um repositório
### git config --global user.email "email@gmail.com" //configuração global para commits
### git config --global user.name "name name name" //configuração global para commits
### git add . ou -git add arquivo.txt   novaPasta/ //da pra adicionar exatamente o arquivo e a pasta que ele pertence
### git commit -m "First commit" //commita
### git remote add origin https://github.com/userGit/remoteRepository.git //aqui eu informo o endereço do repository do GitHub na nuvem para onde os arquivos locais serão enviados.
### git status //exibe status dos arquivos do repositório local
### git push origin branch //empurra os arquivos para o repositório remoto na na branch selecionada

## Comandos de branchs
### git branch // mostra a branch atual
### git branch -a  //exibe todas as branchs do repositório remoto
### git clone --branch nomeDaBranch --single-branch https://github.com/userGit/remoteRepository.git //clona uma branch específica de um repositório remoto
### git checkout nomeOfBranch //ele altera a branch que você irá fazer as alterações
### git branch -m nomeBranch //esse comando cria uma nova branch

## Comandos de configuração
### git remote -v //lista todos os repositórios cadastrados
### git remote add origin https://github.com/userGit/remoteRepository.git //define uma origem remota
### git config --list //o comando retorna a lista de todas as configurações do seu GIT "(q) sai da lista de configs"
### git config --global --unset user.email //aqui ele remove o email associado na configuração
### git config --global --unset user.name //aqui ele remove o name definido na configuração inicial
### git config --global  user.email "email@gmail.com" //aqui ele insere um email para referência nos commits
### git config --global  user.name "name name"//aqui ele insere um nome para referência nos commits 

## Comandos usuais
### git status //apenas para refiricar se há alguma pendência nos arquivos
### git log // mostra todos os commits Q para sair / Quando git travar CTRL + C sai
### git push origin branch //serve para empurrar os arquivos para o repositório remoto
### git pull origin branch//puxa os arquivos na versão que estão no repositório remoto
### git clone https://github.com/userGit/remoteRepository.git //clona um repositório remoto e inicia um repositório local

## Comandos de navegação no git
### ls // exibe pastas do diretório coloridas
### dir // exibe pastas do diretório
### echo> nomeAquivo.txt //cria arquivo do tipo declarado
### ls -a ou dir -a // exibe pastas ocultas
### cd pasta //permite que você navegue para a pasta
### cd ..   //permite que você saia da pasta atual
### (CTRL+L) // limpa o terminal
### mkdir pasta //cria uma pasta 
### rmdir pasta //só remove a pasta se estiver vazia

## Comandos de navegação do terminal
### cd //possibilita que as pastas sejam navegadas  
### cd/   //entra no diretório do disco C
### cd.. //volta para pasta anterior
### dir //exibe as pastas
### mkdir //cria pasta, mk == make dir == directory
### del //no windows permite que um arquivo seja deletado, não deleta pastas
### rmdir //rm == remove, dir == directory, esse comando permite deletar apenas a pasta vazia
### rmdir pasta /S /Q     //deleta o diretório, sendo assim a pasta e todos os arquivos são deletados
### cls // limpa a tela do terminal
### (TAB) é o autocomplete
### <echo mensgem de texto>nome_arquivo.txt // aqui eu criei um arquivo txt chamado "nome_arquivo", contendo em seu conteúdo a mensagem "mensgem de texto".