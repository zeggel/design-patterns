**Прототип** (англ. **Prototype**) - позволяет создавать новые объекты на основе некоторого объекта-прототипа при этом совсем
необязательно знать, как необходимый объект устроен.

Пример, конечно не очень, но он покажет суть шаблона. Перед подачей, наши бургеры нужно сложить в коробки.
Создание коробки привычным путем через **`new`** занимает много времени (в конструкторе мы эмулируем задержку в 1 секунду).
Если нужны 10 - это 10 секунд, 100 - 100 секунд и т.д. Что нам мешает сделать один общий объект, а дальше его клонировать?