# github-linkd

**Pregunta**
### 1. Why would you use this command?
   - git rebase -i HEAD~10
### 2. What will this command print to the terminal?
   - git remote -v
   rpta: a list of remote repositories and their URLs
### 3. What option can be used with the git config command to apply configurations across the entire git environment?
   - rpta: --global
### 4. How does this command alter the currently checked-out branch
   - rpta: It sets HEAD to the previous commit and leaves changes  from the undone commit in the stage/index
    rpta:Esto se hace con mayor frecuencia cuando recuerdas que lo que acabas de cometer está incompleto, o escribiste mal el mensaje de confirmación, o ambos. Deja el árbol de 
     trabajo como estaba antes de "reiniciar".
### 5.You team lead needs a list of all commits that will be moved before you perform a rebase.Which command can you use to access that information
   - rpta: git rebase -i || git rebase --interactive
    Haga una lista de las confirmaciones que están a punto de volver a basarse.
    Deje que el usuario edite esa lista antes de reajustar. Este modo también se puede usar para dividir confirmaciones (ver DIVISIÓN DE COMPROMISOS a continuación).
El formato de la lista de confirmaciones se puede cambiar configurando la opción de configuración rebase.
