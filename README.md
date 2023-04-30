Proste Api do kursu walut.

Przykładowa baza danych znajduje się w xampp/mysql/data/exchange_rate_api.

Możliwe jest odczytanie wszystkich kursów z bazy lub konkretnego kursu (przykładowo, by odebrać kurs dolara potrzeba dopisać do requesta ?currency[eq]=usd).

Endpointy zostały zabezpieczone autoryzacją. By zakutalizować kurs potrzeba podać token updatera lub administratora.
