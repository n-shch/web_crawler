# APO_13_c_cpp_hw-2
Условие ИЗ №2:
Реализовать краулер Википедии с помощью любой из команд для скачивания веб-страниц (curl/wget или любые др.).
 На вход программа должна получать адрес стартовой страницы, максимальную глубину прохода по ссылкам, а также директорию,
  в которую необходимо положить результат. Механизм работы краулера следующий – сначала скачивается исходная страница
   и сохраняется на диск в отдельную поддиректорию с адресом в названии внутри той директории, которая была передана на
   вход программе, а также найти все дочерние ссылки, на которые эта страница ведёт. Для каждой вложенной ссылки нужно
   повторить все те же действия, складывая все результаты уже внутри поддиректории с сайтом-родителем, созданном на
    предыдущем этапе. Переходить по дочерним ссылкам необходимо до тех пор, пока либо не закончатся ссылки, либо не
     будет достигнута максимальная глубина прохода, которая также задаётся в качестве одного из входных аргументов.
      Считать ссылками содержимое атрибута href тегов . Распараллеливание осуществить с помощью нескольких процессов.
