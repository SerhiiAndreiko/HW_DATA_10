# HW_DATA_10
# ***Частина 1***

*​В якості домашнього завдання вам пропонується створити нейронну мережу за допомогою механізмів Keras, яка буде класифікувати товари із датасету fasion_mnist.*

*На відміну від попереднього завдання вам пропонується створити згорткову нейромережу. Підберіть архітектуру мережі та навчіть її на даних із датасету fasion_mnist. Спробуйте досягти максимально можливої точності класифікації за рахунок маніпуляції параметрами мережі. Порівняйте точність отриманої згорткової мережі з точністю багатошарової мережі з попереднього завдання.* 
**Зробіть висновки**

![CNN](image/CNN.png)

![MLP](image/MLP.png)

# За даними можна зробити наступні висновки:

* Згорткова мережа досягла високої точності на тестових даних
у розмірі 91.54%, що свідчить про її добру універсальність на нових, раніше не бачених даних.

* Точність на тренувальних даних для згорткової мережі становить 94.89%, що свідчить про високу здатність моделі підлаштовуватися під тренувальні дані.

* Час тренування згорткової мережі становить 7 хвилин, що є прийнятним для такого рівня точності та складності моделі.

* Багатошарова мережа також досягла досить високої точності на тестових даних у розмірі 85.59%, але менше, ніж згорткова мережа.

* Точність на тренувальних даних для багатошарової мережі складає 86.79%, що може свідчити про перенавчання моделі або про меншу здатність моделі адаптуватися до нових даних.

* Час тренування багатошарової мережі значно менший - лише 1 хвилина, що може бути перевагою у випадках, коли важливий час тренування.

Отже, згорткова мережа демонструє кращі результати як у точності, так і у здатності універсального застосування на нових даних, але вона вимагає більше часу для тренування порівняно з багатошаровою мережею, яка, у свою чергу, має меншу точність.

