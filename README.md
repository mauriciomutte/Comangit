<p align="center"><img src="https://image.prntscr.com/image/AWWl5Ne3T7CxslETpHuEeA.png" width="250"></p>

# Comangit | Alguns comandos do Git


## Estrutura do Git

![Estrutura do Git](git_structure.png)



## Básico

- **git init:** cria um novo repositorio

- **git status:** mostra o estado dos arquivos

- **git add (nome do arquivo):** adiciona o arquivo para ser 'commitado'

- **git commit -m "Mensagem":** 'Commita' o arquivo



## Inspecione os arquivos

- **git log:** Mostra informações dos 'commits'

- **git log --author="nome do autor":** Filtra os commits feito pelo autor

- **git shortlog:** mostra os autores e seus commits

- **git log --graph:** apresenta a estrutura dos commits em forma de gráfico

- **git show (ID do commit):** mostra as alterações do commit 


- **git diff:** mostra as alterações ainda não 'commitadas'

- **git diff --name-only:** mostra apenas os nomes dos arquivos modificados e não 'commitados'



## Volte atrás

- **git checkout (nome do arquivo):** remove todas as alterações no arquivo

- **git reset HEAD (nome do arquivo):** faz o arquivo no estado index voltar ao estado workspace

- **git reset --soft (ID do commit):** faz os commits sucessores (já 'commitados') voltarem ao estado index

- **git reset --mixed (ID do commit):** faz os commits sucessores (já 'commitados') voltarem ao estado workspace

- **git reset --hard (ID do commit):** remove os commits sucessores (já 'commitados')



## Repositórios remotos

- **git push origin master:** envia as alterações para o repositório no Github

- **git clone (link do repositório) (nome da pasta para ser criada):** clona o repositório para sua máquina local

**Obs:** caso você não seja dono do repositório, deve-se fazer um 'fork' do repositório antes de enviar as alterações


