# GitHub. 
## HomeWork_2
1. На локальном репозитории сделать ветки для:
   * Postman  
    `git branch postman`
   * Jmeter  
    `git branch jmeter`
   * CheckLists  
    `git branch check_lists`
   * Bug Reports  
    `git branch bug_reports`
   * SQL  
    `git branch SQL`
   * Charles  
    `git branch сharles`
   * Mobile testing
    `git branch mobile_testing`
   
2. Запушить все ветки на внешний репозиторий  
  `git push --all`
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта  
  `git checkout bug_reports`
  `vim bug_reports.txt`
4. Запушить структуру багрепорта на внешний репозиторий  
  `git push`
5. Вмержить ветку Bag Reports в Main  
  `git checkout master`  
  `git merge bug_reports`
6. Запушить main на внешний репозиторий.  
  `git add bug_reports.txt`  
  `git commit -m "Add bug_reports.txt"`  
  `git push`
7. В ветке CheckLists набросать структуру чек листа.  
  `git checkout check_lists`  
  `vim check_list.txt`
8. Запушить структуру на внешний репозиторий  
  `git add check_list.txt`  
  `git commit -m "Add check_list.txt"`  
  `git push`
9. На внешнем репозитории сделать Pull Request ветки check_lists в main  
   - на сайте github появляется предложение сравнить ветки и подтянуть изменения   
   - нажать кнопку "compare and pull request"  
   - нажать кнопку "create pull request",
   - нажать кнопки "merge pull reguest" и "confirm merge"
10. Синхронизировать Внешнюю и Локальную ветки Main  
  `git checkout main`  
  `git pull`