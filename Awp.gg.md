## Проблемы с Roblox  
- Переустанови Roblox.  
   - Используй [Revo Uninstaller](https://www.revouninstaller.com/products/revo-uninstaller-free/) для полного удаления.  
- Выбери все ключи реестра и связанные папки для удаления.  

## Отсутствующие зависимости  
- Установи оба пакета, затем переустанови AWP:  
   - [VC Redist x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)  
   - [VC Redist x86](https://aka.ms/vs/17/release/vc_redist.x86.exe)  

## Проверка системы на x64  
- Найди "Сведения о системе" в Windows.  
- Убедись, что в поле "Тип системы" указано "x64-процессор".  

## Отключение Защитника Windows  
- Используй этот метод, только если у тебя нет другого антивируса.  
   - [Defender Control v1.5](https://github.com/qtkite/defender-control/releases/tag/v1.5)  

## Альтернативный способ отключения Защитника Windows  
- Следуй инструкциям из этого видео вместо полного удаления:  
   - [Видео-гайд](https://www.youtube.com/watch?v=UKu6qtc534A)  

## Ошибка запуска прокси  
- Добавь исключение для %localappdata%\Roblox (нажми Win+R, введи %localappdata%\Roblox и нажми Enter).  
- Отключи Защитник Windows через Defender Control.  
- Или найди loader-proxy-rs.exe в папке с Roblox и разреши его в системе.  

## Сброс HWID  
`Изменения в железе или подмена HWID могут вызывать эту ошибку.`  
- Если тебя выкидывает из игры с просьбой сбросить HWID - это проблема скрипта.  
- Сбрось HWID только для скрипта, для AWP ничего делать не нужно.  

## Гайд по установке  
- [Инструкция](https://www.youtube.com/watch?v=lnisV_AkAts)  

## Подключение AWP  
- Убедись, что Roblox закрыт.  
- Запусти интерфейс после установки.  
- Введи свои данные для входа.  
- Нажми иконку запуска (ракета).  
- При ошибке:  
   - Нажми "Scripting" вверху интерфейса.  
   - Перейди в Настройки.  
   - Нажми "Fix Channel" и попробуй снова.  

## Ошибка получения размера файла Hyperion  
1. Проверь установленные версии Roblox:  
   - Ищи папки Roblox в:  
     - `C:\Program Files (x86)\Roblox`  
     - `C:\Users\ТвоеИмя\AppData\Local\Roblox`  
   - Если найдешь - удали обе папки.  

2. Переустанови Roblox:  
   - Полностью удали через [Revo Uninstaller](https://www.revouninstaller.com/products/revo-uninstaller-free/).  
   - Скачай с [оф.сайта](https://www.roblox.com/download).  

3. Найди Roblox.exe после установки:  
   - Должен быть в:  
     - `C:\Program Files (x86)\Roblox`  
     - `C:\Users\ТвоеИмя\AppData\Local\Roblox`  

4. Запусти Roblox:  
   - Открой папку "Versions" и запусти "RobloxPlayerLauncher.exe".  

5. Полностью закрой Roblox.  

6. Почини канал в интерфейсе:  
   - Открой настройки и нажми "Fix Channel".  

7. Перезапусти Roblox:  
   - Он откроется автоматически - снова закрой.  

8. Завершающий шаг:  
   - Нажми кнопку запуска (ракета) в интерфейсе.