# GEEKBRAINS: XML И JSON:
## Задача №1: проверить XML на Well formed:
```
<req>
    <surname>Иванов</surname>
    <name>Иван</name>
    <patronymic>Иванович</patronymic>
    <birthdate>01.01.1990</birthdate>
    <birthplace>Москва</birthplace>
    <phone>8 926 766 48 48</phone>
</req>
```
файл корректен и нетребует исправлений.

## Задача №2: проверить JSON на Well formed:
```
{

    "surname": ""Иванов""

    "name"": ""Иван"

    "patronymic"": ""Иванович"

    "birthdate"": ""01.01.1990"

    "birthplace"": ""Москва"

    "phone"": ""8 926 766 48 48"
}
```
Данный JSON является некорректным, так как в нем есть ошибки:

- Пропущена запятая после значения `"Иванов"` в ключе `"surname"`
- Лишняя кавычка в ключе `"name"`
- Пропущена запятая после значения `"Иван"` в ключе `"name"`
- Лишняя кавычка в ключе `"patronymic"`
- Пропущена запятая после значения `"Иванович"` в ключе `"patronymic"`
- Лишняя кавычка в ключе `"birthdate"`
- Пропущена запятая после значения `"01.01.1990"` в ключе `"birthdate"`
- Лишняя кавычка в ключе `"birthplace"`
- Пропущена запятая после значения `"Москва"` в ключе `"birthplace"`
- Лишняя кавычка в ключе `"phone"`
