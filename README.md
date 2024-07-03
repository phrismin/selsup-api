Класс для работы с API Честного знака. Класс thread-safe и поддерживает ограничение на количество запросов к API. Ограничение указывается в конструкторе в виде количества 
запросов в определенный интервал времени. Экземпляр класса создается вызовом публичного метода getInstance(TimeUnit timeUnit, int requestLimit), где
timeUnit – указывает промежуток времени – секунда, минута и пр.
requestLimit – положительное значение, которое определяет максимальное количество запросов в этом промежутке времени.
