# Nama_MorphAnalyzer
### Морфологический анализатор языка нама
Проект предоставляет инструменты для анализа морфологии языка нама. Нама является одним из языков семьи кхое-квади, которые распространены в южной Африке.

### Описание проекта
Морфологический анализатор языка нама является программным инструментом, разработанным для обработки и анализа текстов на данном языке. Он предоставляет возможность разбора слова на основе морфологических признаков имен и глаголов, таких как род, число, падеж; время, наклонение, вид и т. д.

### Структура
1)  *nama.lexd* — описание морфологических структур языка;
2)  *nama.twol* — морфологические правила, действующие в языке;
3)  *name.ipynb* — непосредственно сам код.

### Запуск
Весь код, необходимый для работы морфологического анализатора находится в файле nama.ipynb. Данный формат состоит из фрагментов кода, которые можно запускать последовательно в таких средах разработки, как, например, Google Colab или Jupyter Notebook. Код представлен восемью фрагментами, первые пять из который отвечают за установку и настройку всего необходимого для его корректной работы, как то: установка apertium, запись файлов в форматах .lexd и .twol, их дальнейшее преобразование в файлы формата .hfst, предоставляющие собой скомпилированные трансдьюсеры. Следующие три ячейки призваны продемонстрировать работу морфологического анализатора: шестая демонстрирует пример разбора двух словоформ:\
    *ǃgâgu*	\<brother\>\<3p\>\<pl\>\<m\>\
    *ǁamagu* \<buy\>\<3p\>\<pl\>\<m\>\<obj\>\
    *ǁamagu* \<buy\>\<recp\>\
cедьмая приглашает пользователя ввести словоформу, которую ему требуется проанализировать, восьмая ячейка порождает все формы, которые данный морфологический анализатор в состоянии проанализировать.
