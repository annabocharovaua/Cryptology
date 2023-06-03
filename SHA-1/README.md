SHA-1 (Secure Hash Algorithm 1) є криптографічним алгоритмом хешування, який використовується для створення унікального хеш-коду певного повідомлення або даних. Цей алгоритм був розроблений американським Національним інститутом стандартів і технологій (NIST) і став широко використовуваним протоколом у багатьох криптографічних системах.
Алгоритм SHA-1 приймає вхідні дані фіксованої довжини і генерує хеш-код фіксованої довжини 160 бітів (або 20 байтів). Процес хешування включає кілька кроків:
1. Ініціалізація: Початкове значення хешу (160-бітний вектор) встановлюється у визначене значення.
2. Підготовка повідомлення: Вхідні дані діляться на блоки фіксованої довжини і обробляються послідовно.
3. Доповнення повідомлення: Повідомлення доповнюється бітами, щоб його довжина була кратною 512 бітам.
4. Обробка блоків: Кожен блок повідомлення обробляється окремо за допомогою складних логічних операцій, таких як "і" (AND), "або" (OR) і "виключне або" (XOR), а також бітових зсувів.
5. Підрахунок хеш-коду: Після обробки всіх блоків вхідних даних отримується хеш-код, який є кінцевим результатом алгоритму SHA-1.

SHA-1 був широко використовуваний протягом багатьох років, але він вважається застарілим і небезпечним у зв'язку зі знайденими вразливостями. Через зростаючу обчислювальну потужність сучасних комп'ютерів, атаки
на SHA-1 стають все більш ефективними. З цієї причини рекомендується використовувати більш безпечні алгоритми хешування, такі як SHA-256, які мають більшу довжину хеш-коду та відповідність сучасним криптографічним вимогам.