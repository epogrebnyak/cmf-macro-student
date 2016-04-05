###Задание 1. Ряды макроэкономических показателей (лекция 26.03.2016)

1.1. Составить список важнейших экономических показателей на основе анализа презентаций по макроэкономической статистике

- NY FED [Global Economic Indicators](https://www.newyorkfed.org/research/global_economy/globalindicators.html) and [full charts](https://www.newyorkfed.org/medialibrary/media/research/directors_charts/global_all.pdf)  
- ЦМАКП: Макроэкономические индикаторы (http://www.forecast.ru/Indicators.aspx)  
- ИКСИ: [Основные социально-экономические показатели](http://www.icss.ac.ru/macro/)  
 
Минимальный список: [здесь](https://github.com/epogrebnyak/rosstat-kep-data#Основные-показатели)  


1.2. Импортировать выбрнные показатели из баз данных rosstat-kep-data (РФ) и FRED (США) в месячном и годовом разрезе

Источники данных:
- St Louis [FRED](https://research.stlouisfed.org/fred2/) 
- Rosstat [Short-term Indicators (KEP)](https://github.com/epogrebnyak/rosstat-kep-data)  
 
Программные интерфейсы:
- R and pandas interfaces to KEP:
   - [interface.py](https://github.com/epogrebnyak/rosstat-kep-data/blob/master/interface.py)
   - [interface.r](https://github.com/epogrebnyak/rosstat-kep-data/blob/master/interface.r)
   
- R interface to FRED: [access_fred.r](https://github.com/epogrebnyak/cmf-macro/blob/master/access_fred.r)  

 
1.3. Сохранить полученные данные в csv, опционально - в xls.

1.4. Нарисовать графики этих показателей 

###Задание 2. СНС/МОБ/Flow of funds  (лекция 26.03.2016)

Cоставить список вопросов для анализа, которые могут решаться с помощью 
данных межотраслевого баланса и системы национальных счетов.

Дополнительно: на какие вопросы не нельзя ответить с помощью MOБ, с помошью СНС?
