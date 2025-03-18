## Основные команды
git init  
git branch  
git checkout  
git merge  
git push  
git tag 

## Коммиты и слияния
- 3 коммита в каждой feature-ветке
- Слияние feature-веток в develop
- Создание и исправления в release/1.0
- Слияние release/1.0 в main и develop
- Создание тега v1.0

## Структура веток
```plaintext
main
 ├── develop
 │   ├── feature/login
 │   ├── feature/dashboard
 │   ├── feature/settings
 │
 ├── release/1.0
