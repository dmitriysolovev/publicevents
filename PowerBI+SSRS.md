#Database credentials:
- Server: mysamplesqlserver2.database.windows.net
- Database Name: AdventureWorksDW
- User Name: azureuser
- Password: Pa55w.rd

#Что нужно сделать?
1. Зайти в https://powerbi.com с учеткой вида userXX@azurelabs0919.onmicrosoft.com и паролем: Pa55w.rd
1. Создать рабочую область и назвать ее UserXX-Worksapce
1. Создать поток данных на основании данных Azure SQL Database. Таблицы для потока данных: 

    - FactInternetSales
    - DimProduct
    - DimDate
    - DimCustomer
    - DimProductCategory
    - DimProductSubCategory
    - DimGeography
1. Использовать AutoML для предсказания суммы продажи :)
1. Создать отчет Power BI Desktop на основе потока данных и опубликовать в рабочую облать
1. Создать отчёт SSRS на основании датасета Power BI и опубликовать в сервис
