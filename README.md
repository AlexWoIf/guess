# Игра "Виселица"

## Функция get_rand_word(filename)

Функция открывает файл с именем `filename`, извлекает строки, убирает лишние пробелы в начале и конце каждой строки, затем выбирает случайное слово из этих строк в нижнем регистре.

## Функция print_game(wrong, word, letters)

Функция выводит текущее состояние игры на экран, отображая угаданные и неверные буквы, а также скрытые буквы слова.

![screenshot](./gameplay.png)

## Функция get_letter(attempt, guess)

Функция получает ввод от пользователя для угадывания буквы. Проверяет валидность ввода и возвращает угаданную букву или `None`, если ввод неверен.

## Функция play(word)

Главная функция игры. Инициализирует переменные для отслеживания попыток и угаданных букв, затем начинает цикл, в котором игроку предлагается угадать букву до тех пор, пока игрок не выиграет или не исчерпает все попытки.
