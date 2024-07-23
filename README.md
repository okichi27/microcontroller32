# **STM32-blink_built_in_led (in English)** 

> [!NOTE]
> First there will be a description in English, then in Ukrainian. 

This branch contains the project of the same name **blink_built_in_led** - a project that uses the simplest function to blink the built-in LED on STM32;

## Description

After starting the project, the LED will perform an infinite period: on for 1 second, then off for 1 second.

## Installation

In order to run this project, you need to perform the following steps:

1. Download and install STM32CubeIDE from STMicroelectronics official website.
2. Clone this repository to your local computer.

       git clone https://github.com/okichi27/stm32.git

3. After cloning, navigate to the repository folder

       cd stm32

4. Download the desired branch.

       git checkout blink_built_in_led

5. Start STM32CubeIDE and select the "Import Project" option.
6. Select "Existing Projects into Workspace" and specify the path to the clone repository.
7. Make sure the blink_built_in_led project is listed and click Finish.


## Start and use

Once the project has been imported into STM32CubeIDE, the following steps are required to run it:

### For STM32F103C8T6 board

1. Connect the STM32F103C8T6 board to the computer via USB and the programmer.
2. Select a project in the "Project Explorer" window.
3. Click on the "Build" button to compile the project.
4. After successful compilation, click on the "Debug" button to flash the project to the board.

### For another STM32 board (MCU of the same series)

1. Choose File > New Project.
2. Select an MCU belonging to the same series.
3. Choose File > Import Project. In the import project window, locate the .ioc file to download. The message warns that the currently selected MCU is different from the one specified in the .ioc file.
4. Click the Try Import button and check the import status to make sure the import was successful.
5. Click OK to actually import the project. The output tab for the results report will then appear.
6. On the Project Manager project tab, configure the new project name and folder location.
Click the Build icon to save the project and generate the code.
7. In the dialog box, select Open Project, update the user sections with
user code.
8. Connect your board to the computer via USB and the programmer.
9. Click on the "Build" button to compile the project.
10. After successful compilation, click on the "Debug" button to flash the project to the board.

**Have fun using the project!**

---
:shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: :shipit: 

# **STM32-blink_built_in_led (українською)**

Ця гілка містить проект **blink_built_in_led** - проект, який використовує найпростішу функцію на мигання вбудованого світлодіода на STM32;

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

**Гарного використання!**
