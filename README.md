# Шпаргалка по Git для начинающих

Git - это система управления версиями, позволяющая отслеживать изменения в вашем проекте и сотрудничать с другими.

## Начало работы с Git

1. **Установите Git:**
   - [Скачайте Git](https://git-scm.com/downloads) и установите его.

2. **Настройте имя и email:**
   ```bash
   git config --global user.name "Ваше имя"
   git config --global user.email "ваш@example.com"
   ```

## Основные команды Git

3. **Инициализация репозитория:**
   ```bash
   git init
   ```

4. **Клонирование существующего репозитория:**
   ```bash
   git clone <URL репозитория>
   ```

5. **Добавление файлов в коммит:**
   ```bash
   git add <файлы>
   ```

6. **Создание коммита:**
   ```bash
   git commit -m "Описание коммита"
   ```

7. **Просмотр состояния репозитория:**
   ```bash
   git status
   ```

8. **Отправка изменений на удаленный репозиторий:**
   ```bash
   git push
   ```

9. **Обновление локального репозитория из удаленного:**
   ```bash
   git pull
   ```

10. **Создание новой ветки:**
    ```bash
    git branch <название ветки>
    ```

11. **Переключение на другую ветку:**
    ```bash
    git checkout <название ветки>
    ```

## Работа с Markdown (стилизация) для README.md (и прочих файлов формата '.md')

Markdown - это простой способ форматирования текста для документации.

1. **Заголовки:**
    ```markdown
    # Заголовок 1
    ## Заголовок 2
    ```

2. **Списки:**
    ```markdown
    - Элемент списка 1
    - Элемент списка 2
    ```

3. **Ссылки:**
    ```markdown
    [Текст ссылки](http://example.com)
    ```

4. **Выделение текста:**
    ```markdown
    *Курсив* 
    **Жирный** 
    ***Курисв и Жирный*** 
    ```

6. **Цитаты**:
   - `> Текст цитаты`

7. **Код**:
   - Встроенный код: \`код\`
   - Блок кода:  
     \```язык  
     код  
     \```  

8. **Горизонтальная черта**:
   - `---`

9. **Таблицы**:
   ```
   | Заголовок 1 | Заголовок 2 |
   | ----------- | ----------- |
   | Строка 1    | Строка 2    |
   ```

10. **Экранирование символов**:
    - ('') для экранирования специальных символов, например, `*` или `[`.
