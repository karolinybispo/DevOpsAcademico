# PROCEDIMENTO OPERACIONAL PADRAO

## OBJETIVO
Descresver o processo que devera ser seguido para o desenvolvimento de novas features 

## PASSO A PASSO PARA CRIAR FEATURE EM PROJETOS JA DESENVOLVIDOS
1. **Criar nova branch**
 - Comando para branch com historico em comum: `git checkout -b nome-da-feature ou da branch`
 - Comando para branch orfã: `git checkout --orfhan nome-branch ou feature`, na nova branch: `git rm -rf .`  isso apaga o que veio da branch anterior. No momento de fazer o merge faça: `git merge nome-branch --allow-unrelated-historie` isso faz o merge acontecer mesmo nao havendo historico de commits em comum.
4. **Desenvolver a nova feature**
5. **Testar**
6. **Commits**
7. **Fazer merge**


## PASSO A PASSO PARA CRIAR FEATURE EM NOVOS PROJETOS
1. **Criar repositorio remoto**
2. **Definir as features que o projeto terá**
3. **Em cada sprint escolher qual feature será desenvolvida**


