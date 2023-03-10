# BRANCH_HW
### GIT   HW#2

  
  
1. На локальном репозитории сделать ветки для:
- Postman - <code> <b>git branch Postman</b> </code>
- Jmeter - <code> <b>git branch Jmeter</b> </code>
- CheckLists - <code> <b>git branch CheckLists</b> </code>
- Bag Reports - <code> <b>git branch BagReports</b> </code>
- SQL - <code> <b>git branch SQL</b> </code>
- Charles - <code> <b>git branch Charles</b> </code>
- Mobile testing - <code> <b>git branch MobileTesting</b> </code>

2. Запушить все ветки на внешний репозиторий - <code> <b>git add .</b> </code>  
<code> <b>git commit -m "new seven branch"</b> </code> 
<code> <b>git checkout main</b> </code>
<code> <b>git push -u origin Postman SQL Jmeter CheckLists Charles MobileTesting BagReports</b> </code>

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта - <code> <b>git checkout BagReports</b> </code>
<code> <b>touch bug_report.txt</b> </code>
<code> <b>vim skills.txt</b> </code>
 <b>Нажать</b> <code> <b>i</b> </code>
 ```
ID: BR-14,
Title: What? Where? When?,
Severity: Minor,
Priority: Medium,
Precondition: Preparation steps,
Environment: Devices,
STR: Steps to restore,
ER: Expected result,
AR: Actual Result,
Attachment: link
 ```
<b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>

4. Запушить структуру багрепорта на внешний репозиторий - <code> <b>git add .</b> </code>
<code> <b>git commit -m "bug report"</b> </code>
<code> <b>git push</b> </code>

5. Вмержить ветку Bag Reports в Main - <code> <b>git checkout main</b> </code>
<code> <b>git merge Bag_reports</b> </code>

6. Запушить main на внешний репозиторий - <code> <b>git add .</b> </code>
<code> <b>git commit -m "merge branch Bag_reports in main"</b> </code>
<code> <b>git push</b> </code>

7. В ветке CheckLists набросать структуру чек листа - <code> <b>git checkout CheckLists</b> </code>
<code> <b>touch checkl.txt</b> </code>

<code> <b>vim checkl.txt</b> </code>

<b>Нажать</b> <code> <b>i</b> </code>

 ```
Структура чек-листа:
1 - ID/Номер;
2 - Title/Заголовок. В одном пункте — одно требование, элемент или ОР;
3 - Pass/Fail/Статус; 
4 - Link/Ссылка на БР.
 ```
<b>Нажать</b> <code> <b>Esc :wq Enter</b> </code>

8. Запушить структуру на внешний репозиторий - <code> <b>git add .</b> </code>
<code> <b>git commit -m "structure"</b> </code>
<code> <b>git push</b> </code>

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main - <b>После пуша check_list.txt на внешний репозиторий ветки CheckLists нажать на зеленую кнопку</b> <code> <b>Compare&pull requset</b> </code>
10. Синхронизировать Внешнюю и Локальную ветки Main - <code> <b>git checkout main</b> </code> <code> <b>git fetch</b> </code>
<code> <b>git pull</b> </code>