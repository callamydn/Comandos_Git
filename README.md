#  ***Aula sobre Git/GitHub*** | **DIO** 🎓

Resumos sobre as aulas passadas no BootCamp Santander pela **[Dio](https://web.dio.me/home)** 
## **Links importantes** ❗

- [Git](https://git-scm.com/) - **Versionamento de codigo**
- [GitHub](https://github.com/) - **Desenvolvedor de Softwarre**
- [Dio](https://web.dio.me/home) - **Instituição de ensino EAD**
- [Sintaxe de MD](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)  - **Lista de comandos para criação e sintaxe de MarkDown**
- [Manual Git](https://git-scm.com/docs) - **Manual de comandos Git**
------
## **Comandos para o Git** 💻
|**Comandos**  | **Função**       |
|---------|--------------|
|`ctrl+L` | Limpar tela|
|`/(pasta ou arquivo)` *EX.: cd /pasta local*| Abre direto a pasta/arquivo ou direciona para o mesmo|
|`mkdir`(Nome)| Criar pasta|
|`ls` | Ver conteudo da pasta|
|`touch`(Nome).md| Criar bloco de notas em **MD**(Markdown) linguagem de marcação simples|
|`cd`(destino)| Abre a pasta de destino|
|`cd..`<dois pontos>| Volta um nivel da pasta atual|
|`git init`| Iniciar arquivo git na pasta|
|`cd .git` |Abre arquivo **.git** do diretorio (se foi criado pelo `git init`)|
|`cat config`| Mostra configuração do arquivo **.git**|
|`git clone`(Url)(adicionar nome opcional)| Clonar diretorio remoto|
|`git remote -v`| Mostra os diretorios vinculados|
|`git remote add`(adicionar nome ao diretorio)(url)|Linkar repositorio local com remoto|
|`git branch`| Listar, criar ou deletar branches|
|`git fetch`| Baixar objetos e referencias de outro repositorio|
|`git status`| Mostrar status da arvore de trabalho e tambem da area de preparação|
|`git add`(arquivo)| Adicionar arquivo para area de preparação|
|`git commit -m` "(nome)" | Criar commit |
|`git log`| Mostrar registros de commits|
|`echo` (pasta detino)/ ou  (arquivo)/| Mudança no arquivo|
|`.gitignore`(nome do arquivo ou pasta).gitignore| Ignorar arquivo ou pasta|
|`>` EX.: echo pasta/ > .gitignore| Adicionar para arquivo|
|`>` EX.: echo > .gitignore| Retirar de arquivo|
|`.gitkeep` | Cria arquivo para definir diretorio vazio|
|`git add`(nome do diretorio) | Adicionar diretorio especifico|
|`git add .`| Adiciona todos os arquivos pendentes|
| `rm -rf`(arquivo)| Remover arquivos|
|`git restore`(Nome do arquivo)| Restaura modificações do arquivo desejado|
|`git commit --amend -m"(mensagem)"`| Altera o nome do ultimo commit|
|`git commit --amend`| Abre tela de console para alteração dos logs (ver abaixo comandos)|
|`git reset`(arquivo)| Remove arquivo especifico da area de preparação|
|`git reset --soft`(hash do commit)| Retornar para commits posteriores ao hash devolta para a area de preparação|
|`git reset --mixed`(hash do commit)| Retorna os arquivos para a area de untracked files(desconhecidos)|
|`git reset --hard`(hash do commit)| Apaga todos as modificações posteriores ao hash|
|`git reflog` | Historico detalhado das modificações realizadas|
|`git restore --staged`(arquivo)| Remove arquivo especifico da area de preparação|
|`git remote add origin`(url) | Linkar diretorio local com diretorio remoto|


## 📙 **Sobre configurar o Git**


## 🚩 **Conteudo Importante**
* **Estados:** 
    1.  Modificado (*modified*);
    2.  Preparado (*staged/index*);
    3.  Consolidado (*comitted*);
* O comando `touch` podemos direcionar a pasta de destino, adiconando o `\(pasta de destino)` + `(nome do arquivo.md)`
* O comando `>` ajuda a direcionar arquivos para seu destino.
* O comando `git restore` reseta todas as configurações feitas no arquivo como se fosse um Ctrl+Z muito cuidado progressos podem ser perdidos.
* No comando `git commit --amend` na tela de console aperte `i` para modificar texto. Para sair precione `esc` `:` `w` `q`

### **🔎Referências**