# Tests git technique

1. **Comment rebaser interactivement une branche pour réécrire l'historique des commits ?**
   - [ ] `git rebase -i HEAD~[nombre_de_commits]`
   - [ ] `git rebase -a HEAD~[nombre_de_commits]`
   - [ ] `git rebase --interactive HEAD~[nombre_de_commits]`
   - [ ] `git rebase --amend HEAD~[nombre_de_commits]`

2. **Comment afficher un journal des commits avec des statistiques sur les changements de fichier ?**
   - [ ] `git log --stat`
   - [ ] `git log --diff`
   - [ ] `git log --summary`
   - [ ] `git log --patch`

3. **Comment annuler un commit en gardant les changements dans la zone de staging ?**
   - [ ] `git reset --soft HEAD~1`
   - [ ] `git revert HEAD~1`
   - [ ] `git commit --amend`
   - [ ] `git reset --hard HEAD~1`

4. **Comment afficher les différences entre deux commits spécifiques ?**
   - [ ] `git diff [commit_1] [commit_2]`
   - [ ] `git show [commit_1]..[commit_2]`
   - [ ] `git compare [commit_1] [commit_2]`
   - [ ] `git log --diff [commit_1] [commit_2]`

5. **Comment fusionner une branche distante dans la branche courante ?**
   - [ ] `git merge [alias]/[branch]`
   - [ ] `git pull [alias]/[branch]`
   - [ ] `git fetch [alias] [branch]`
   - [ ] `git rebase [alias]/[branch]`

6. **Comment afficher l'historique des modifications d'un fichier spécifique, même après son renommage ?**
   - [ ] `git log --follow [file]`
   - [ ] `git log --rename [file]`
   - [ ] `git diff --follow [file]`
   - [ ] `git show --follow [file]`

7. **Comment supprimer un fichier du projet et ajouter cette suppression à la zone de staging ?**
   - [ ] `git rm [file]`
   - [ ] `git delete [file]`
   - [ ] `git remove [file]`
   - [ ] `git clean [file]`

8. **Comment afficher les branches locales et les branches distantes ?**
   - [ ] `git branch -a`
   - [ ] `git branch -r`
   - [ ] `git branch --all`
   - [ ] `git branch --list`

9. **Comment réécrire l'historique des commits de la branche courante pour appliquer les commits d'une autre branche par-dessus ?**
   - [ ] `git rebase [branch]`
   - [ ] `git merge --squash [branch]`
   - [ ] `git cherry-pick [branch]`
   - [ ] `git reset [branch]`

10. **Comment sauvegarder temporairement des modifications pour pouvoir changer de branche sans les committer ?**
    - [ ] `git stash`
    - [ ] `git save`
    - [ ] `git store`
    - [ ] `git cache`