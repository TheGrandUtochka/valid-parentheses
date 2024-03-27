Необходимо разработать алгоритм, который будет принимать на вход строку, состоящую из символов скобок трёх типов: круглых (), квадратных [] и фигурных {}. Задача алгоритма — определить, является ли данная строка "правильной" последовательностью скобок.

Критерии "правильности" последовательности:Для каждой открывающей скобки в строке должна быть соответствующая закрывающая скобка того же типа.Скобки должны закрываться в правильном порядке. Это означает, что закрывающая скобка каждого типа должна соответствовать ближайшей непосредственно предшествующей ей открывающей скобке того же типа.Пустая строка считается правильной.Требования к алгоритму:Входные данные: Строка, содержащая символы скобок: (, ), {, }, [, ]. Длина строки может быть от 0 до 10^4 символов.Выходные данные: Булево значение — true, если строка является правильной последовательностью скобок, и false в противном случае.Примеры:
Входная строка: () Вывод: true

Входная строка: ()[]{} Вывод: true

Входная строка: (] Вывод: false

Входная строка: ([)] Вывод: false

Входная строка: {[]} Вывод: true

Замечания:Необходимо учитывать вложенность скобок.Эффективность алгоритма будет оцениваться по времени выполнения и использованию памяти.Рекомендуется использовать стек для реализации алгоритма проверки корректности последовательности.
Цель задачи — разработать алгоритм, способный эффективно проверять большие последовательности скобок на соответствие критериям "правильности". Это задание поможет улучшить навыки работы со структурами данных и алгоритмами, а также понимание принципов программирования.
