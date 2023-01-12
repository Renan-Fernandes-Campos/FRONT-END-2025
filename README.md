# --------------------------GIT-HUB----------------------

### Versinonamento
- Histórico
- Controle de Versão
- O que foi alterado
- Quando foi alterado
- Quem alterou o arquivo
- ver todos os arquivos
- Evolução continua / integração continua
ex: Arquivo A | Versão 1 | Versão 2
    Arquivo B | Versão 1 | Versão 2
### ------------------Instalação do GIT---------------------
- Baixar o GIT no link https://git-scm.com/downloads
### Criar uma conta no GITHUB
### ----------------Clonar os projetos----------------------
### Passos:
No git:
- copiar a url do repositório do git hub
No VS Code: .
- Abrir o folder do projeto
- Abrir o terminal
Comandos: 
- git clone + https://github.com/Renan-Fernandes-Campos/front_end_ebac.git] 
- (Clona o repositório do git)
## -------------------------Commits-----------------------------
- É a informação de alteração no codigo
- Obs: So deve realizado apois o código ser testado
### No terminal
Comando: cd + [nome do repositório] (acesso o repositório local)
- Comando: git add * (adcionar para staging)
- Comando: git commit -m (mensagem)
- Comando: git status (ver o status/alterações ex: precisa ter alterações)
- Comando: git push (publicar/enviar alteraçãoes para o repositório)
- Comando: git pull (Trazer as alterações do repositório do Github para a minha maquina)
## ---------------------Configurar o GitFloW-----------------------
- Fluxo do Git
- git flow init (Configurar um fluxo para a branch)
- git flow feature start + [nome da feature nova] ( cria uma branch nova como o nome escolhido com base na branch dev, maim ou master )
- touch .gitignore (add um arquivo novo com isntruções)
### -----------------------------Branchs---------------------------
- São as ramificações do codigo / versões do codigo trabalhadas em paralelo
- main ou master (E a versaõ que vai para a produção, é quando o projeto e publicado)
- develope (ambiente somente para desenvolvimento)
 obs: tem que atender ao DOD - definição de Pronto / Critérios de aceite
 (scrum)
- Versionamento   [versão 0/Beta]   [alterações]   [Correções de bugs]
                      0        .       1       .        10          = v0.1.10
- Dica/regra apos esta totalmaente comcluida ex: v1.0.0 pode-se enviar para a branch master para a publicação em PRD!

COMANDOS:
- git checkout -b dev (criar uma copia da main ou master para a nova branch dev)
- git branch (mostra quantas branchs)
- git checkout master (muda de branck)
### ------------------------------Marge----------------------------
- Mesclar as branchs
- Obs: Poder ser necessário resolver conflitos manualmente!!
- git merge main (chama a branch que eu quero mesclar ex comparar a branch dev com a main ou master)
### ---------------------------Pull Requests-----------------------
- Mescla de Branch no repositóro do git
- Permite code reveiw
- O repositório resolve os confltos automaticamente
### ---------------Merge para a branch main ou master--------------
- git fetch --all (para verificar alterações mo repositório do git ex na branch master) 
- git merge main ou master
### --------------------------Features-----------------------------
- Cada feature será mapeada como um versão da brannch dev
- Não trabalho direto na branch dev e sim em varias features
- Prefixo da feature = [feature/] (cada branch que tiver um feature vai começar com este prefixo!)
- ##### git flow feature start + [nome da feature nova] ( cria uma branch nova como o nome escolhido com base na branch dev, maim ou master )
Exemplos:
- [feature/]
- [bugfix/] para correção de bugs
- [release/] para quando uma nove versao for criada
- [hotfix/] para as correções rapidas 
- [supporte/] 
- version tag prefix [v] para acrescentar o "V" ao versionmanto.
- Comando: git flow feature finish + [nome da feature]
### -------------------------Continua!!!--------------------------