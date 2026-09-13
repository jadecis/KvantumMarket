# KvantumMarket

Desktop-приложение на C# и Windows Forms для поиска товаров и сравнения предложений магазинов. Интерфейс выводит ссылки на результаты; в проекте используются Selenium WebDriver и HtmlAgilityPack.

## Стек

C#, Windows Forms, .NET Framework 4.7.2, NuGet, Selenium.

## Сборка

1. На Windows установите Visual Studio с поддержкой разработки desktop-приложений .NET и targeting pack .NET Framework 4.7.2.
2. Откройте `KvantumMarket/Kvantum Market.sln`.
3. Восстановите зависимости NuGet из `packages.config` и соберите решение.
4. Проверьте совместимость Chrome и используемого ChromeDriver перед запуском поиска.

## Структура

- `Form1.cs` — логика поиска и переходов по ссылкам.
- `Form1.Designer.cs` и `Form1.resx` — интерфейс формы и ресурсы.
- `Program.cs` — точка входа.
- `logo_market/` — изображения магазинов.

Исходники формы расположены в `KvantumMarket/Kvantum Market/`.

## Статус

Учебный desktop-проект. Парсинг зависит от разметки сайтов магазинов; работа с текущими сайтами не подтверждена. Бинарные результаты сборки и настройки Visual Studio не являются исходниками приложения.
