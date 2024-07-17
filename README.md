# **blink_built_in_led (in English)** 

> [!NOTE]
> First there will be a description in English, then in Ukrainian. 

**This repository is dedicated to work with stm32 !!**
Here will be collected the projects that I managed to execute on stm32 (stm32f103c8t6 / stm32f401ceu6 ) First there will be a description in English, then in Ukrainian. There are several sections, each of which has projects on a similar topic:

1. **task_BlinkLed**. - projects with LED + button control;



## task_BlinkLed 
A folder that contains projects with a built-in LED and the use of an additional button (built-in and external).
It includes the following projects:

1. **blink_built_in_led** - a project that uses the simplest blinking function of the built-in LED on the stm32;
After starting the project, the LED will perform an infinite period: on for 1 second, off for 1 second. 
   
---
:shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: 

# **blink_built_in_led (українською)**

Ця гілка містить одноіменний проект **blink_built_in_led** - проект, який використовує найпростішу функцію на мигання вбудованого світлодіода на stm32;

## Опис

Після запуску проекту світлодіод буде виконувати нескінченний період: горить 1 секунду, а після вимикається на 1 секунду.

## Встановленння

Для того, щоб запустити цей проект, необхідно виконати наступні кроки:

1. Завантажте та встановіть STM32CubeIDE з офіційного сайту STMicroelectronics.
2. Клонуйте цей репозиторій на ваш локальний комп'ютер.
  
   git clone https://github.com/okichi27/stm32.git

3. Після клонування перейдіть до папки репозиторію
    
    cd stm32

4. Завантажте потрібну гілку.
    
    git chechout blink_built_in_led
   
5. Запустіть STM32CubeIDE та оберіть опцію "Import Project".
6. Виберіть "Existing Projects into Workspace" та вкажіть шлях до клонувавного репозиторію.
7. Переконайтесь, що проект blink_built_in_led відображається у списку, та натисніть "Finish".


## Запуск та використання

Після того, як проект було імпортовано у STM32CubeIDE, необхідно виконати наступні кроки для його запуску:

### Для плати STM32F103C8T6

1. Підключіть плату STM32F103C8T6 до комп'ютера через USB та програматор.
2. Оберіть проект у вікні "Project Explorer".
3. Натисніть на кнопку "Build" для компіляції проекту.
4. Після успішної компіляції натисніть на кнопку "Debug" для прошивки проекту на плату.

### Для іншої плати STM32 (MCU тієї ж серії)

1. Виберіть «Файл» > «Новий проект».
2. Виберіть MCU, що належить до тієї ж серії.
3. Виберіть «Файл» > «Імпортувати проект». У вікні імпорту проекту знайдіть файл .ioc для завантаження. Повідомлення попереджає про те, що поточний вибраний MCU відрізняється із зазначеного у файлі .ioc.
4. Натисніть кнопку «Спробувати імпорт» і перевірте стан імпорту, щоб переконатися, що імпорт був успішним.
5. Натисніть OK, щоб справді імпортувати проект. Потім відобразиться вкладка виводу для звіту про результати.
6. На вкладці проекту «Диспетчер проектів» налаштуйте нову назву проекту та розташування папки.
Натисніть піктограму «Створити», щоб зберегти проект і створити код.
7. У діалоговому вікні виберіть «Відкрити проект», оновіть розділи користувача за допомогою
коду користувача.
8. Підключіть вашу плату до комп'ютера через USB та програматор.
9. Натисніть на кнопку "Build" для компіляції проекту.
10. Після успішної компіляції натисніть на кнопку "Debug" для прошивки проекту на плату.