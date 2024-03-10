# customer-buying-behavior
Análise do comportamento de compra de clientes em uma companhia aérea (British Airlines)

Fonte de dados: https://www.kaggle.com/datasets/kamyababedi/customer-buying-behaviour 

Este conjunto de dados inclui informações essenciais relacionadas com as reservas das companhias aéreas, fornecendo informações sobre vários aspetos da experiência de reserva dos passageiros.
O conjunto de dados foi projetado para ajudar a entender as preferências dos passageiros, otimizar os serviços e melhorar a satisfação geral.

Colunas:
* num_passengers: Number of passengers per booking	
* sales_channel:	Source of ticket purchase (e.g., online, agency)	
* trip_type:	Type of trip (one-way, round trip, multi-city)	
* purchase_lead:	Lead time between ticket purchase and departure	
* length_of_stay:	Duration of the entire trip	
* flight_hour:	Scheduled departure hour of the flight	
* flight_day:	Scheduled departure day of the flight	
* route:	Specific flight path or route	
* booking_origin:	Location where the booking was initiated	
* wants_extra_baggage:	Preference for additional baggage	
* wants_preferred_seat:	Preference for a preferred seat	
* wants_in_flight_meals:	Preference for in-flight meals	
* flight_duration:	Estimated duration of the flight	
* booking_complete:	Booking completion status (0 = incomplete, 1 = complete)	

Tarefa: prever o comportamento de compra do cliente

Algoritmos usados:
* Random Forest
* SVM
* Gradient Boosting
* XGBOOST