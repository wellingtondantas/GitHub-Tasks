# GitHub Tasks
 A list of tasks git
 
## Adiciona pastas/arquivos/codigos em repositório no git e enviar para o github

1. Verificar o status de arquivos não enviados:
```
git status
```
2. Adiciona PASTA:
```
git add PASTA
```
3. Enviar para git (repositório local):
```
git commit -m "descrição sobre a pasta"
```
4. Enviar para github (repositório na nuvem):
```
git push -u origin master
```


## Deleta pastas/arquivos/codigos em repositório no git e enviar para o github

1. Certifique-se que o seu repositório está sincronizado com o repositório remoto: 
```
git pull origin master, (supondo que o branch seja master).
```
2. Remova a pasta localmente:
```
git rm -r PASTA1 PASTA2.
```
3. Faça um commit das modificações: 
```
git commit -m "Remove pastas PASTA1 e PASTA2"
```
4. Sincronize com repositório remoto: 
```
git push origin master
```

Fonte: https://pt.stackoverflow.com/questions/110101/deletar-pastas-no-github

## Cronar (Baixar) pastas/arquivos/codigos em repositório github

1. Digite git clone (clonar git) e cole a URL do github que deseja cronar
```
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```


## Outros comandos

1. Verifica o diretorio remoto
```
git romote -V
```