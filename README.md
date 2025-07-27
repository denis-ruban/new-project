1. Створити каталог та перейти у нього  
   mkdir new-project  
   cd new-project

2. Ініцюювати репозиторій  
   git init

3. Створити README.md та закомітіти  
   echo "# new-project" > README.md  
   git add README.md  
   git commit -m "init"

4. Створти та переключитися на гілку development  
   git checkout -b development

5. Додати інструкцію у файл REAMDE.md

6. Змержити зміни development в main  
   git merge development
   
7. Підготувати до пушу  
   git add README.md
   git commit -m "Smart message"
 
8. Запушити в репозиторій
   git push -u origin main
   git push -u origin development

