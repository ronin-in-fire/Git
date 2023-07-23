# GitHub Homework 2

|Задание|Решение|
|:---------------|:-----|
|1. На локальном репозитории сделать ветки для:  |
|- Postman| `git branch` Postman |
|- Jmeter| `git branch` Jmeter |
|- CheckLists| `git branch` CheckLists |
|- Bag Reports| `git branch` Bag_Reports |
|- SQL| `git branch` SQL |
|- Charles| `git branch` Charles |
|- Mobile testing| `git branch` Mobile_testing |
|2. Запушить все ветки на внешний репозиторий|  `git push` `-u` `origin` `--all`|
|3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта| `git checkout` Bag_Reports ,  `vim` Bag_report_structure.txt |
|4. Запушить структуру багрепорта на внешний репозиторий| `git add` Bag_report_structure.txt , `git commit` `-m` "Bag-Report Structure" , `git push` `-u` `origin` Bag_Reports |
|5. Вмержить ветку Bag Reports в Main| `git checkout` main , `git merge` Bag_Reports |
|6. Запушить main на внешний репозиторий.| `git push` `-u` `origin` main |
|7. В ветке CheckLists набросать структуру чек листа.| `git checkout` CheckLists , `vim` Check_Lists_Structure.txt |
|8. Запушить структуру на внешний репозиторий| `git add` Check_Lists_Structure.txt , `git commit` `-m` "Check-Lists Structure" , `git push` `-u` `origin` CheckLists |
|9. На внешнем репозитории сделать Pull Request ветки CheckLists в main| `Compare & pull` , `Create pull request` , `Merge pull request` , `Confirm merge` |
|10. Синхронизировать Внешнюю и Локальную ветки Main| `git fetch` , `git pull` ,  `git push -u origin` main |
