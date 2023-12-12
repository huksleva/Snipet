# Snipet для Visual Studio Code

#### Snipet сделан только для файлов с расширение .cpp
<br>

### 0. Общее описание Java Script функций
***"scope"*** - указывает для какого расширения создан snipet\
***"prefix"*** - кодовое слово, с помощью которого вставляется определённый код\
***"body"*** - код, который будет вставлятся\
***"description"*** - описание к snipet'у\
***"$X, $(X-1)...$2, $1, $0"*** - распологает каретку в указанных местах по убыванию. $0 - конечная позиция каретки. Смена позиции (например от $2 к $1) происходит по нажатию клавиши **TAB**\
<br>

### 1. Get_array
```json
"Get_array": {
    "scope": "cpp",
    "prefix": "ad",
    "body": [
        "int n;"
        "cin >> n;"
        "int m[n];"
        "for (int i = 0; i < n; ++i) { cin >> m[i]; }"
        "$0"
    ],
    "description": "Creating simple code to get array from console"
}
```
Считывает с консоли число n - кол-во элементов массива и далее n элементов массива m.\
<br>

### 2. Print_array
```json
"Print_array": {
    "scope": "cpp",
    "prefix": "da",
    "body": [
        "for (int i = 0; i < n; ++i) { cout << m[i]; }"
        "$0"
    ],
    "description": "Creating simple code to print array"
}
```
Выводит на экран консоли массив m, состоящий из n элементов\
<br>
##### Выполнил Тоц Леонид Александрович\
##### М3113\















