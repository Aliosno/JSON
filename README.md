Окружение OC: Windos 10
  ---
1. Создать внешний репозиторий c названием JSON.
```
В GitHub кликаю справа на кнопку New --> в Repository name прописываю JSON --> 
оставляю репозиторий публичным --> ставлю галочку рядом с Add a README file 
(чтоб репозиторий был непустой).Кликаю внизу на кнопку Creat repository
```
2. Клонировать репозиторий JSON на локальный компьютер.
```bash
git clone <ссылка на репозиторий>  # в необходимом репозитории кликнуть 
# справа на кнопку Code и скопировать HTTPS)
```
3. Внутри локального JSON создать файл “new.json”. 
```bash
touch new.json
```
4. Добавить файл под гит. 
```bash
git add new.json
```
5. Закоммитить файл. 
```bash
git commit -m "the first file"
```
6. Отправить файл на внешний GitHub репозиторий
```bash
git push
```
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, 
 будущая желаемая зарплата). Всё написать в формате JSON. 
```bash
vim new.json  # (режим редактирования (I) - прописываю 
```
```json
 {
  "name": "Sosno Alisa",
  "age": 55,
  "animals": "One cat",
  "salary": "120000 rur"
 }
 
```
Для выхода с сохранением: 
```bash
ESC  
:wq
```
8. Отправить изменения на внешний репозиторий. 
```bash
git add new.json 
git commit -m "anketa" 
git push
```
9. Создать файл preferences.json 
```bash
touch preferences.json
```
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, 
 страна которую хотели бы посетить) в формате JSON. 
``` 
vim preferences.json  # (режим редактирования (I) - прописываю
```
```json
 {
   "movie":"Avatar",
   "show":"Black mirror",
   "food":"Zapekanka",
   "season":"Spring",
   "country":"UAE"
 }
```
Для выхода с сохранением: 
```bash
ESC  
:wq
```
11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON 
```bash
touch sklls.json
vim skills.json  # (режим редактирования (I) - прописываю 
```
```json
 {
   "skills": "Terminal, Git, Testing"
 }
 
```
Для выхода с сохранением: 
```bash
ESC  
:wq
```
12. Отправить сразу 2 файла на внешний репозиторий.
```bash
git add . 
git commit -m "first json_1" 
git push
13. На веб интерфейсе создать файл *bug_report.json*.
```
в репозитории JSON кликаю справа на кнопку *ADD FILE* 
creat new file  
в *NAME YOUR FILE* прописываю bug_report.json
кликаю внизу на кнопку *Commit new file*
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
```bash
какие изменения? они только в 18 пункте
```
15. На веб интерфейсе модифицировать файл *bug_report.json*, добавить баг репорт в формате JSON. 
```bash
в репозитории JSON находим нужный файл и кликаем по его названию 
справа кликаем на значок карандаша (редактирование) 
прописываем
```json
// содержимое файлва JSON
 {
  "bag": "моя фантазия не придумала баг"
}
```
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```bash
кликаю внизу на кнопку **Commit changes** (сохранить)
```
17. Синхронизировать внешний и локальный репозиторий JSON
```bash
git pull  # (в терминале)
```
