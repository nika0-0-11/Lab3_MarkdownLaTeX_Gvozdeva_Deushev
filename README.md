# Лабораторная работа №3. Работа с Markdown-разметкой и LaTeX

## Краткое описание

Данная лабораторная работа посвящена освоению языкы разметки **Markdown** и системы верстки **LaTeX** 
для создания качественной документации проектов. В ходе работы изучаются основные и расширенные
возможности Markdown, интеграция математических формул LaTeX, а также практическое применение
этих инструментов в реальных проектах на GitHub

---

## Содержание

- [Структура проекта]()
- [Примеры форматирования]()
- [Блоки кода]()
- [Таблицы]()
- [Изображения и ссылки]()
- [Расширенные возможности]()
- [Математические формулы]()

---

## Структура проекта


- Lab3_MarkdownLaTeX_Gvozdeva_Deushev/
    - docs/
        - advancedMarkdownLab3_Gvozdeva_Deushev.md
        - codeQuotesLab3_Gvozdeva_Deushev.md
        - formattingLab3_Gvozdeva_Deushev.md
        - headersLab3_FIO.md
        - linksImagesLab3_Gvozdeva_Deushev.md
        - listsLab3_Gvozdeva_Deushev.md
        - ReadmePushLab3_Gvozdeva_Deushev.md
        - separatorsLab3_FIO.md
        - tablesLab3_Gvozdeva_Deushev.md

    - img/ 
        - advancedMarkdownCommitLab3_Gvozdeva_Deushev.png
        - codeCommitLab3_Gvozdeva_Deushev.png
        - commitStructureLab3_Gvozdeva_Deushev.png
        - formattingCommitLab3_Gvozdeva_Deushev.png
        - gitPushLab3_Gvozdeva_Deushev.png
        - headersCommitLab3_Gvozdeva_Deushev.png
        - latexCommitLab3_Gvozdeva_Deushev.png
        - linksCommitLab3_Gvozdeva_Deushev.png
        - listsCommitLab3_Gvozdeva_Deushev.png
        - readmeFinalPushLab3_Gvozdeva_Deushev
        - separatorsCommitLab3_Gvozdeva_Deushev.png
        - tablesCommitLab3_Gvozdeva_Deushev.png
    
    - latex/
        - latexLab3_Gvozdeva_Deushev.md
    
    - README.md

---

## Примеры форматирования

### Заголовки разных уровней

# Заголовок H1
## Заголовок H2
### Заголовок H3

### Текстовое форматирование 

- **Жирный текст**
- *Курсивный текст*
- ~~Зачеркнутый текст~~
- `Моноширный текст`

### Списки

#### Маркированный список:

- Первый пункт
- Второй пункт
    - Вложеный пункт
    - Еще один вложенный

#### Нумерованный список:

1. Первый элемент
2. Второй элемент
3. Третий элемент
    1. Вложеный нумерованный 
    2. Еще один

### Цитаты 

> Это пример цитаты в **Markdown** 

---

## Блоки кода

### С указанием языка

```csharp
Console.WriteLine(HELLO FRIEND.);
```

---

## Таблицы 

| Компонент | Назначение | Статус |
| :-------- | :--------- | :----- |
| Markdown | Разметка документации | ✅ Готово |
| LaTeX | Математические формулы | ✅ Готово |
| Git | Контроль версий | ✅ Готово |

---

## Изображение и ссылки

### Изображение из папки img:

![Push screenshot](/img/advancedMarkdownCommitLab3_Gvozdeva_Deushev.png)

### Ссылки:

- **Внутренняя ссылка**: [Перейти к содержанию](#содержание)
- **Внешняя ссылка**: [Официальная документация Markdown](https://www.markdownguide.org/)

---

## Расширенные возможности 

### Чекбоксы 

- [x] Изучить основы Markdown
- [x] Освоить работу с Git
- [x] Завершить все задания

### Сноска 

**Markdown** значительно упрощает создание документации для разработчиков[^1]

[^1]: Особенно при работе с GitHub-репозиториями, создание README-файлов и технической документации проектов

### Alert-блоки GitHub:

> [!NOTE]
> Markdown поддерживается на большинстве плафторм для разработчиков

> [!TIP]
> Используйте расширения для VS code для удобного просмотра Markdown-файлов

> [!WARNING]
> Некоторые расширенные возможности Markdown работают только на конкретных платформах

---

## Математические формулы

###  Inline LaTeX:

Площадь круга вычисляется по формуле $S = \pi r^2$, где $r$ - радиус окружности

###  Block LaTeX:

Формула суммы первых $n$ натуральных чисел:

$$
\sum_{i=1}^n i = \frac{n(n+1)}{2}
$$
