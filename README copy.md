# stm32


**This repository is dedicated to work with stm32 !!**
Here will be collected the projects that I managed to execute on stm32 (stm32f103c8t6 / stm32f401ceu6 ) First there will be a description in English, then in Ukrainian. There are several sections, each of which has projects on a similar topic:

1. **task_BlinkLed**. - projects with LED + button control;
2. ** **. - ;
3. ** **. - ;
4. ** **. - ;
5. ** **. - ;
6. ** **. - ; 


## task_BlinkLed 
A folder that contains projects with a built-in LED and the use of an additional button (built-in and external).
It includes the following projects:

1. **blink_built_in_led** - a project that uses the simplest blinking function of the built-in LED on the stm32;
After starting the project, the LED will perform an infinite period: on for 1 second, off for 1 second. 
   
2. **led_blink_only_btn_press** - project about dependence LED on the blinking button.
After flashing stm32, the program will work with the following period: after a press of the button, the LED starts flashing, until the button is pressed again and you can start over.


3. **led_blink_from_1s_to_0s** - the project about the dependence of the LED blinking speed on the button.
After starting the project, the program will execute an infinite period: by default, the LED flashes with a period of 1s on, 1s off; decreases when the button is pressed
the flashing period of flashing (the longer the button is pressed or the more button clicks, the more the glow and non-glow of the LED decrease proportionally) from 1 to 0 seconds.
 After the compliance period reaches 0 seconds, the program returns to its initial state : period - 1 second.




# stm32 in Ukrainian

**Цей репозиторій призначений проектам з stm32 !!**
Тут будуть зібрані проекти, які мені вдалось виконати на stm32 (stm32f103c8t6 / stm32f401ceu6 ). Є декілька розділів, у кожному з яких проекти за схожою тематикою:

1. **task_ADCandRWM**. - проекти з АЦП(аналого-цифровий перетворювач) та ШІМ(широтно-імпульсна модуляція);
2. **task_BlinkLed**. - проекти з світлодіодом + керування кнопкою;
3. **task_Other**. - проекти з одиночними темами;
4. ** **. - ;
5. ** **. - ;
6. ** **. - ; 



## task_ADCandRWM
Папка, яка містить проекти з АЦП(аналого-цифровий перетворювач) та ШІМ(широтно-імпульсна модуляція).
Має в собі такі проекти:

1. **ADC_with_UART** - проект з АЦП та UART; 
Цей проект виконує завдання по читанню значень з аналого-цифрового перетворювача (ADC/АЦП) і передачі цих значень через інтерфейс UART. Це дозволяє мікроконтролеру збирати аналогові дані і передавати їх на комп'ютер для подальшого аналізу;

2. **ADC_with_RWM** - 

3. **PWM** - проект, який робить генерацію сигналу ШІМ на каналі 1 таймера 1; 
Це означає, що мікроконтролер буде генерувати модульований сигнал на відповідному вихідному піні, який можна використовувати для керування підключеними пристроями.


### Як використовувати цей код:





## task_BlinkLed 
Папка, яка містить проекти з вбудованим світлодіодом та використання додатково кнопки(вбудованої та зовнішньої).
Має в собі такі проекти:

1. **blink_built_in_led** - проект, який використовує найпростішу функцію мигання вбудованого світлодіода на stm32;
Після запуску проекту світлодіод буде виконувати нескінченний період: горить 1 секунду, а після вимикається на 1 секунду.
   
2. **led_blink_only_btn_press** - проект, про залежність від кнопки блимання світлодіода.
Після прошивання stm32 програма буде працювати з таким періодом: після короткотривалого натиску кнопки світлодіод починає блимати,
до моменту доки кнопка знову не натиснеться і можна почати спочатку.

3. **led_blink_from_1s_to_0s** - проект, про залежність від кнопки швидкості блимання світлодіода.
Після запуску проекту, програма буде виконувати безкінечний період: за умовчанням світлодіод блимає з періодом 1с світить, 1с- ні; при натиску кнопки зменшується
період блимання блимання (чим довше затиснута кнопка чи чим більше кліків кнопки тим більше зменшується світіння і не світіння світлодіода пропорційно) з 1 до 0 секунд.
Після досягнення періодом відповідності 0 секундам, програма повертається до початкового стану в період по 1 секунді.



## task_Other
Папка, яка містить проекти на різні одиночні теми. Має в собі такі проекти:

1. **message_transfer_via_USB** - проект з використанням USB;
Цей проект здійснює передачу повідомлення через інтерфейс USB (за допомогою CDC, Communication Device Class) з певним інтервалом.

