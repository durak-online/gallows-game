## Недочеты
- В Game.jack 138 строчка - вы инициализируете список в 35 ячеек, а по факту используете только 29
- В Gallows.jack войд-методы, отрисовывающие виселицу, названы как drawStage{Number}, лучше бы, если методы отражали, что конретно отрисовывается, например drawColumn, drawRope, drawHead и т.д.
- В почти всех классах написан метод dispose(), хотя по факту вы используете его только в классе Main: game.dispose()

## Пожелания:
- Хочется иметь возможность бесконечно переигрывать игру, не перезапуская её каждый раз в эмуляторе.
- Игра про угадывание слов, но программа реагирует на нажатие не только букв, но любых клавиш - чисел, бэкспейса и тд.

## Общая оценка:
Игра прикольная, понравилось угадывать слова, не наскучило :)