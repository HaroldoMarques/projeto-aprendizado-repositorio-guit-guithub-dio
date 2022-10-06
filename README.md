# Projeto Aprendizado Guit/GuitHub Dio
### Projeto Aprendizado Git/Github Dio

## Iniciação ao Git

### Definição:

O Git é um sistema de versionamento de código distribuído de forma gratuita. Utilizado para monitorar o desenvolvimento de código-fonte, com o objetivo de criar softwares e de realizar o acompanhamento dos históricos de alterações realizadas ao longo do período de contrução do código.

## Objetos e Ferramentas do Git

### SHA1:

Secure Hash Algorithm (Algoritimo de Hash Seguro), é um conjunto de funções hash criptográficos projetados pela Agência de Segurança Nacional dos EUA (NSA). A encriptação gera um conjunto de caracteres identificadores de quarenta (40) dígitos únicos, utilizados para identificação de forma rotativa, sempre que acionado o arquivo, serão gerados novos caracteres. O SHA1 é uma forma curta de representar um arquivo.

### Blobs (Bolhas):

Possuem metadados do Git, referentes ao: tipo do objeto, tamanho do string, tamanho do arquivo, entre outros dados.

### Tree (Árvores):

Armazenam os Blobs, apontando para tipos diferentes de Blobs e metadados. Compostos de estruturas formadas de: Blobs, SHA1, nome do arquivo (ex: texto.txt), tamanho de arquivos e diretórios.

### Commit:

Objeto mais importante dentro do Git. Realiza o ajuntamento de todas as ações, apontando para a seguinte sequência: Árvore (Tree)>Parente>Autor>Mensagem.
O SHA1 desse Commit é o Hash de toda essa informação.

### SSH: 

Tipo de chave dentro do Git que estabelece uma conexão segura e encriptada entre o usuário do Git físico (máquina) e o GitHub (remoto).

### Git Status:

Auxilia no monitoramento do modo que os arquivos se encontram dentro da pasta/diretório, como em seus formatos: Untraked, Unmodified, Modified ou Staged.

### Git Mov:

Permite a movimentação de arquivos e pastas dentro do Git.

### Git Add * ou Add .:

Realiza a transferência de todos os arquivos modificados dentro do diretório de trabalho para a área do "Staged", para passarem pelo processo de "Commit".

### Git Add + Nome do Arquivo:

Adiciona o arquivo selecionado e descrito a pasta solicitada, exemplo: git add lasanha.md receitas/

### Git Commit -m:

Transmite uma mensagem ao Git, informando que todos os arquivos da área "Staged" serão envelopados (envolvidos) com áspas ("") descritos em uma mensagem ("mensagem"), onde em seguida será gerado um objeto no Git chamado "Commit".
Exemplo: git commit -m "adiciona index".

### Git Remote add origin:

Possibilita adicionar ao Git da máquina (computador do usuário) o GitHub que possuimos em nossa conta de acesso remoto. 
Exemplo: git remote add origin https: github.com/mentesbrilhantes/visionários-do-seculo-vinte.git

### Git Push:

Atua no envio dos arquivos Git para a plataforma remota da GitHub.
Exemplo: git push origin master.

### Git Pull:

Ele recolhe a versão do GitHub que foi alterada por algum usuário que clonou o código-fonte do autor que disponibilizou o acesso público ou até mesmo, quando o próprio criador do código realiza alguma alteração que seja diferente da versão que se encontra em sua máquina pessoal (computador do usuário). Essa versão atualizada do GitHub será transmitida para dentro do Git da máquina por meio do comando: git commit -m "resolve conflitos". Após a realização desse comando que geraram as alterações do código, será orientado a realização do comando "Git Push", para realizar o evio dos arquivos Git atualizados para a plataforma remota do GitHub.

### Git Init:

Inicializa um repositório Git na pasta em questão, sendo criado um novo repositório.

## Comandos Básicos

### DIR (Windows)/LS (Linux):
Espõe um lista de diretórios dentro da pasta que estamos trabalhando, exemplo: c:\desktop>documentos>despesas-mensais.

### CD: 
Permite a navegação entre as pastas e é igual para os dois tipos de Sistemas Operacionais (S.O) Windows e Linux. Conduz o usuário até a base do diretório que está navegando. Por meio desse comando, o usuário poderá navegar dentro de qualquer pasta delecionada, exemplo: c:\>cd windows - c:\windows>dir. Esse comando expõe todos os aquivos e programas executáveis dentro da pasta selecionada.

Para retroceder e voltar para a pasta de origem, realizando o caminho inverso, iremos realizar outro comando (c:\windows>cd ..), o qual retornar ao início do diretório.

### CLS ou Ctrl + L (Windows)/Clear (Linux): 
Esse comando permite a limpeza da tela do terminal Git, apagando os resultados expostos de comandos realizados anteriormente.

### MKDIR: 
Comando realizado para criar uma nova pasta dentro do diretório/terminal. Igual para os dois tipos de Sistemas Operacionais (S.O) Windows e Linux.

### ECHO: 
Possibilita a criação de novos arquivos dentro das pastas. Igual para os dois tipos de Sistemas Operacionais (S.O) Windows e Linux.

### DEL: 
Dentro do ambiente do S.O Windows, permite deletar somente arquivos dentro das pastas e não a pasta inteira, sendo deletados todos os diretórios e arquivos dentro da pasta selecionada.

### RMDIR (Windows)/RM-RF (Linux): 
Permite a remoção de todo o repositório/pasta e todos os arquivos contidos dentro dele. No S.O Linux serão deletados todos os diretórios, pastas e repositórios.

## Principais Comandos:
Windows: cd, dir, mkdir, del/rmdir
Unix/Linux: cd, ls, mkdir, rm-rf

