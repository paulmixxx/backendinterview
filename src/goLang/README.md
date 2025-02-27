## GoLang

**Go** (Golang) — компилируемый многопоточный язык программирования.

Язык Go разрабатывался как язык программирования для создания высокоэффективных программ, работающих на современных распределённых системах и многоядерных процессорах. Он может рассматриваться, как попытка создать замену языкам Си и C++. Компилируемый язык. Предполагается, что программы на Go будут транслироваться компилятором в объектный код целевой аппаратной платформы и в дальнейшем исполняться непосредственно, не требуя виртуальной машины. Архитектура языка изначально проектировалась так, чтобы обеспечить быструю компиляцию в эффективный объектный код. 

  * [Типы данных](types.md)

  * [Сoncurrency](concurrency/README.md)
    * [Каналы](concurrency/chanel.md)
    * [Горутины](concurrency/gouritine.md)
    * [Sync](concurrency/sync.md)
    * [Паттерны](concurrency/patterns.md)
    
  * [Планировщик](scheduler.md)

  * [Управление памятью](memory.md)

  * [Экосистема](ecosystem.md)

    

## Вопросы

- Как хранятся переменные в Golang?

- Что представляет собой тип данных string в Go?

- Что вернет функция len(), примененная к строке?

- Что собой представляет тип данных rune?

- Как устроен слайс и чем он отличается от массива?

- Как работает функция append? Что происходит с capacity и базовым массивом?

- Как создать многомерный массив в Golang

- Нужно ли передавать slice по ссылке в функцию?

- Что представляет собой map?

- Чем является функция в Go?

- Что такое метод структуры? Что такое получатель (receiver) метода? В чем разница между получателем по значению и указателем?*** значения-методы и выражения-методы - в чем отличие?

- Что такое интерфейсы? Как устроен пустой интерфейс?

- Как огранить число потоков на системы при запуске Golang программы и возможно ли огранить их до 1 потока?

- Что такое каналы и каких видов они бывают? Что будет если писать в закрытый канал? Что будет если писать в неинициализированный канал?

- Как в golang освобождает память и можно ли отключить это поведение и зачем это делать?

- Что представляют собой каналы? Какой дефолтный размер буфера у канала? Что вернет получение значения из закрытого канала? Что произойдет при записи значения в закрытый канал?

- В чем отличие буферизированного канала от небуферизированного?

- Каким способом происходит отмена работы других горутин? Почему важно завершать горутины по окончании / прерывании работы главной программы?

- Что такое гонка данных (race condition, состояние гонки)? Какие существуют способы избежать состояния гонки в Go?

- Что такое семафор? Бинарный семафор? Что такое mutex? Какие бывают виды mutex в Go?

- В чем различия goroutine от потока системы?

- Расскажите об ООП в Golang

  

*Дополнительно:*

- [Исходный код](https://golang.org/src/runtime/chan.go)
- [Каналы в спецификации Go](https://golang.org/ref/spec#Channel_types)
- [Каналы Go на стероидах](https://docs.google.com/document/d/1yIAYmbvL3JxOKOjuCyon7JhW4cSv1wy5hC0ApeGMV9s/pub)
- [Планировщик Go](https://habr.com/ru/company/ua-hosting/blog/269271/)
- [Work-stealing планировщик в Go](https://habr.com/ru/post/333654/)
- [Как не наступать на грабли в Go](https://habr.com/ru/post/325468)
- [Go Traps](https://go-traps.appspot.com/)
- [Хэш таблицы в Go. Детали реализации](https://habr.com/ru/post/457728)
- [Algorithms to Go](https://yourbasic.org/)
- [Практичный Go: советы по написанию поддерживаемых программ в реальном мире](https://habr.com/ru/post/441842/)
- [50 оттенков Go: ловушки, подводные камни и распространённые ошибки новичков](https://habr.com/ru/company/mailru/blog/314804/)