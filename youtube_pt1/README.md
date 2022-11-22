# Анализ показателей YouTube канала в соотвествии с методикой AIDA

[Jupyter тетрадь](https://github.com/aksyutenko/data_analyst_portfolio/blob/main/youtube_pt1/yt_dashboard.ipynb)  
[Looker Studio дашборд](https://datastudio.google.com/reporting/d8c8a0af-4a13-4a02-9141-f3007a7d13b2)  

**Цель исследования**

Осуществить выгрузку метрик YouTube канала с помощью API и подготовить дашборд в Looker Studio в соответствии с методикой AIDA. На следующем этапе данная информация будет использоваться для расчета ROMI.

**Задачи исследования**
- Импорт данных YouTube канала в разрезе видео роликов и дат в Google Sheets;
- Подготовить дашборд в Looker Studio;

**Использованные библиотеки**
- pandas
- gspread
- googleapiclient
- os

**Результат исследования**
- Данные загружены с сервера с помощью YouTube API используя скрипт Python;
- Данные выгружены в Google Sheets с помощью библиотеки gspread;
- На основе данных и в соответствии с методикой AIDA подготовлен [дашборд](https://datastudio.google.com/reporting/d8c8a0af-4a13-4a02-9141-f3007a7d13b2) в Looker Studio;
