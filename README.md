<h1 align="center" style="font-weight: bold">Лабораторні роботи з комп'ютерної графіки та мультимедіа✍️</h1> 

# Лабораторна робота №1
## [Частина 1](https://hok405.github.io/Computer_Graphics_And_Multimedia/lab1/index1.html) 🔗
## [Частина 2](https://hok405.github.io/Computer_Graphics_And_Multimedia/lab1/index2.html) 🔗

1. **Створити програму WebGL**:
- створити документ HTML з елементом Canvas;
- налаштувати Viewport та встановити довільний колір екрану;
- створити контекст WebGL за допомогою «setupWebGL» та подію
«windowonload».

2. **Виконати рендеринг кольорового трикутника:**
- створити фрагментний шейдер;
- створити вершинний шейдер;
- налаштувати буфер вершин з відповідним покажчиком на атрибут
для створення трикутника, кожна вершина якого має відмінний від інших
вершин колір.
3. **Обертання фігури:**
- додати другий трикутник та утворити прямокутник;
- розмістити квадрат в центрі екрана та організувати його обертання
навколо власного центру за допомогою функції «RequestAnimationFrame».
4. **Створити довільну графічну фігуру за допомогою режима**
gl.TRIANGLE_FAN та налаштувати її рух вниз та вгору.

# [Лабораторна робота №2](https://hok405.github.io/Computer_Graphics_And_Multimedia/lab2) 🔗

1. Створити комп’ютерну програму, що містить обробник подій,
який створює точки за натисканням на комп’ютерну мишу.
Врахувати, що точки зсуваються від курсора миші, що є небажаним.
Відповідно, потрібно створити обмежувальний прямокутник канвас в
клієнтській області за допомогою event.target.getBoundingClientRect() і
виправити позицію курсора, використовуючи ліву та верхню координати
цього прямокутника.
2. Додати елемент управління «Button», яка очищає канвас.
Створити меню вибору кольору, що буде використовуватися після
очищення канвас.
Додати меню вибору кольору, щоб встановити колір створюваних
точок, що вимагає оновлення шейдерних програм.
3. Забезпечити роботу двох режимів рисування. Перший режим має
рисувати точки, другий — будувати трикутник. Додати елемент управління
«Button» для кожного з режимів.
Під час візуалізації створити вершини в масиві індексів точок як
точок і нарисувати вершини в масиві індексів трикутника як трикутники.
Намагатися викликати gl.drawArrays якомога менше разів.
4. Додати кнопку для режиму рисування кола.
Створити масив для індексів кола. При рисуванні в режимі кола
програма має додавати точку при першому натисканні на комп’ютерну
мишу, відповідно при другому натисканні додавати вершини для
окружності, використовуючи положення, задане під час першого
натискання на комп’ютерну мишу, щоб встановити радіус кола.
Додати індекс центральної вершини до масиву індексів кіл та
видалити цей індекс із масиву точкових індексів.
Нарисувати кожне коло з використанням режиму gl.TRIANGLE_FAN
для візуалізації.

# [Лабораторна робота №3](https://hok405.github.io/Computer_Graphics_And_Multimedia/lab3) 🔗

1. Створити графічний об’єкт в ортогональній проекції.
2. Представити у перспективній проекції створений у попередньому
завданні графічний об’єкт.
3. Забезпечити використання різних кольорів для різних елементів
графічного об’єкту.
4. Реалізувати для куба анімацію з довільними налаштуваннями.

# [Лабораторна робота №4](https://hok405.github.io/Computer_Graphics_And_Multimedia/lab4) 🔗

1. Створити програму WebGL та використати фоновий колір.
2. Створити та розмістити у графічний сцені об’єкт довільної форми
у перспективній проекції.
3. Реалізувати освітлення графічної сцени за допомогою моделі
віддзеркалення Фонга
4. Внести зміни в освітлення сцени.

# [Лабораторна робота №5](https://hok405.github.io/Computer_Graphics_And_Multimedia/lab5) 🔗
1. Створити WebGL-програму, що створює фігуру на зразок
розміщеної на зображенні.
2. Застосувати до фігури текстуру.
3. Застосувати до фігури додаткову текстуру
4. Передбачити можливість зміни текстури за рахунок натискання
клавіші миші.