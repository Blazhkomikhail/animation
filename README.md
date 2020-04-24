#Настройка: 

1. Создаете локальную копию проекта 

    `git clone <ссылка на GitHub вашего форка>` или клон с fl-05-epam  

2. Настройка upstream ветки

    `git remote add origin <ccылка на Ваш форк>`
    
    `git remote add upstream https://github.com/fl-05-epam/animation.git`

3. Алгоритм комита: 

    `git pull upstream master` - стягивает изменения с основной ветки
    
    `git status` - проверить, какие файлы Вы изменяли
    
    `git add <файл или . (добавить все)>` - добавляет все измененные файлы. 

    `git commit -am "описание того, что вы сделали"` - сохраняем изменения на ветке

    `git push origin master` - отправляем изменения себе в форк

    Создать pull request в удаленном репо.
