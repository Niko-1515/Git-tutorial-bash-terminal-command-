# Git-tutorial-bash-terminal-command-

## Список корисних команд для роботи з git

1. git clone - копіює (клонує) репозиторій(папку з файлами) на компютер
2. git branch "branchName" - створює гілку з назвою "branchName"
   git branch name - створює гілку з ім’ям name
3. git checkout "branchName" - переходить на гілку з назвою "branchName"
   git checkout name - перехід до потрібної гілки
4. git checkout -b "branchName" - створюємо гілку з назвою "branchName" і переходимо на неї
   git checkout -b name - створює нову гілку з ім’ям “name” і переходить в неї
5. git add . - зберігаємо зміни в файлах
6. git commit -m "commit message" - підписуємо збереженні зміни в файлах
7. git push - відправляємо зміни на сайт github (Стягує оновлення з репозиторію)
8. git pull - отримуємо останні зміни з сайту github
9. git status - показуємо статус проекту (статус в локальному репозитрії)
10. git branch - показуємо список гілок в проекті
11. git branch -r - показуємо список гілок на сайті github
12. git branch -a - показуємо список гілок на компютері та на сайті github
                     (показує список віддалених гілок)
13. git fetch - отримуємо зміни з сайту github
14. git stash - ховаємо не збережені зміни в файлах і кладемо їх в буфер (“карман”) обміну
    (Використовується тоді коли потрібно перейти в іншу гілку але не хочеться робити коміт)
15. git stash apply - вставляємо збережені зміни з буфера обміну (Повертає схований код)
16. git merge "banchName" - зливаємо гілку з назвою "branchName" в поточну гілку
    git merge name - злятя гілки “name” в поточну
17. git merge --abort - відміняємо зливання гілок
18. git branch -d branchName - видаляє гілку локально з проекту (потрібно з неї вийти)
19. git push origin --delete name - видаляє гілку з сайту github
20. git diff - показує відрізки рядків між двома версіями файлу (між двома комітами)
21. git log - показує історію комітів
22. cd gitTutorial - переходимо в папку gitTutorial
23. git push -u origin name - перший пуш нової локальної гілки на гітхаб
24. git commit -am “text commit ” - короткий запис команда git add . та git commit -m “” 
                     (Працює лише для вже відстежуваних файлів)
25. git switch -c "branch_name" - створення нової гіпереходом в неї
26. git switch "branch_name"    - зміна гілки (перехід в іншу гілку)

Для того щоб вийти з режиму перегляду комітів використовуйте клавішу q (стосується команди №20 і №21)

- Для першого запуску gulp збірки
- $ npm install
- $ gulp
Для наступних запусків збірки
- $ gulp
- Щоб закінчити роботу gulp
- Ctrl + C
