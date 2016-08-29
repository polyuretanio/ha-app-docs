JavascriptChallengeGoal
=======================

Несмотря на название, с классом `Goal` не имеет ничего общего. Позволяет запускать одну проверку для текущего состояния javascript-кода.

Методы для определения проверок
-------------------------------

 * `initializeVariable` - перед выполнением кода переменная с указанным именем (если она объявлена в коде) будет проинициализирована указанным значением.
 * `initializeVariables` - проинициализировать сразу несколько переменных
 * `assertEqual` - добавить в конец скрипта код, проверяющий, что переменная с указанным именем имеет указанное значение
 * `assertEquals` - добавить несколько проверок по разным переменным

Метод для выполнения проверок
-----------------------------

 * `run` - собственно, выполняет все проверки. Если проверки проходят, возвращает `true`, иначе `false`.