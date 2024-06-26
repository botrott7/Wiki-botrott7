## [Назад](../FileSystem/fs.md)

### <center>Файловый дескриптор ✔️</center>
`это целое неотрицательное число, которое представляет собой открытый файл или сетевое соединение в операционной системе.`

Когда программа открывает файл или соединяется с сетью, система создает файловый дескриптор для этого файла или соединения. Файловый дескриптор используется программой для выполнения операций с файлом или соединением, таких как чтение, запись, перемещение и закрытие.

Файловый дескриптор можно рассматривать как указатель на файл или соединение в ядре операционной системы. Он позволяет программе идентифицировать файл или соединение и выполнять с ним операции, не беспокоясь о том, как это реализовано в системе.

Файловый дескриптор 0 обычно ассоциирован с стандартным вводом (stdin), файловый дескриптор 1 - с стандартным выводом (stdout), а файловый дескриптор 2 - с стандартным потоком ошибок (stderr)

**Особенности файловых дескрипторов:**

* Файловые дескрипторы являются уникальными для каждого процесса.
* Максимальное количество файловых дескрипторов, которые может иметь процесс, ограничено и зависит от операционной системы и настроек системы.
* Файловые дескрипторы могут быть унаследованы дочерними процессами.
* Файловые дескрипторы можно закрывать явно (с помощью системного вызова `close`) или неявно (когда процесс завершается).

Файловые дескрипторы являются важным механизмом для взаимодействия с файлами и сетевыми соединениями в операционных системах. Они позволяют программам легко выполнять операции ввода-вывода без необходимости беспокоиться о деталях реализации файловой системы или сетевого стека.