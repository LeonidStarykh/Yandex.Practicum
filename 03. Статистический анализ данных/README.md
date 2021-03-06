# 03. Статистический анализ данных

# Определение перспективного тарифа для телеком-компании

## Цель исследования
По выборке клиентов изучить их предпочтения по использованию пакетов услуг, выяснить какой из двух тарифов более прибыльный.

## Задачи:
   - посчитать для каждого пользователя:
	- количество сделанных звонков и израсходованных минут разговора по месяцам;
	- количество отправленных сообщений по месяцам;
	- объем израсходованного интернет-трафика по месяцам;
	- месячную выручку с каждого пользователя.
   - изучить поведение клиентов оператора, выяснить сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям каждого тарифа в месяц
   - проверить гипотезу о равенстве средних выручек с пользователей каждого тарифа
   - дать рекомендации коммерческому отделу по корректировке рекламного бюджета, исходя из того какой из тарифов приносит больше прибыли

## Результаты исследования

1. Изучили количество израсходованных минут, сообщений, интернет-трафика и среднюю выручку с пользователей двух тарифов;
2. Посчитали среднее количество, дисперсию и стандартное отклонение, построили гистограммы;
3. Нашли сколько минут разговора, сколько сообщений и какой объём интернет-трафика требуется пользователям в месяц каждого тарифа:
	- **для тарифа 'Смарт'**: 
	 	* 29% пользователей не хватает 500 минут; 
	 	* 25% - не хватает 50 сообщений; 
	 	* 65% - не хватает 15 гигабайт интернет-трафика; 
	 	* 90% - доплачивают за потребляемые услуги связи (минуты разговора, SMS, интернет) сверх абонентской платы;
	- **для тарифа 'Ультра'**:
	 	* всем пользователям хватает лимита в 1500 минут (при доступном 3000);
	 	*  всем пользователям хватает лимита в 1000 сообщений; 
	 	*  9% - не хватает 30 гигабайт интернет-трафика и 67% из них доплачивают за потребляемые услуги связи сверх абонентской платы;
4. Предложили варианты по изменению размеров пакетов услуг, входящих в тариф 'Смарт', с целью увеличения общей выручки;
5. Проверили гипотезы о равенстве средних выручек в зависимости от тарифа и от города проживания пользователя. В результате получили, что:
	- пользователи тарифа "Ультра" приносят больше средней выручки;
	- средняя выручка клиентов из Москвы и из других городов не отличается.
