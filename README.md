# analiza_online_retail
Analiza sprzedaży i klientów sklepu internetowego z wykorzystaniem Excel, SQL i Power BI.

# Opis projektu

Celem projektu była analiza danych sprzedażowych sklepu internetowego w celu identyfikacji najważniejszych rynków, klientów, produktów oraz zmian sprzedaży w czasie. Analiza obejmowała przygotowanie i oczyszczenie danych, analizę sprzedaży i zamówień oraz przygotowanie dashboardu wspierającego interpretację wyników biznesowych.


# Wykorzystane narzędzia

- Microfoft Excel - przygotowanie i analiza danych, tabele przestawne oraz podstawowa wizualizacja
- SQL - analiza sprzedaży, klientów, produktów i zamówień
- Power BI - dashboard i wizualizacja wyników


# Zakres analizy

# Excel
- przygotowanie danych do analizy,
- utworzenie kolumn Sales, TransactionType oraz SalesValid,
- identyfikacja anulowanych transakcji,
- analiza sprzedaży według kraju, klienta, produktu i czasu,
- analiza liczby zamówień,
- przygotowanie KPI i tabel przestawnych,
- przygotowanie wykresów.

# SQL
  Przygotowano zapytania dotyczące m.in.:
  - Top 10 klientów według sprzedaży,
  - średniej wartości zamówienia,
  - liczby zamówień przypadających na klienta,
  - sprzedaży według kraju,
  - Top 10 produktów,
  - sprzedaży według miesiąca,
  - Top 10 klientów według liczby zamówień.
 
# Power BI
    Przygotowano dashboard zawierający:
    - łączną sprzedaż
    - Top 10 krajów według sprzedaży,
    - Top 10 klientów według sprzedaży,
    - Top 10 produktów według sprzedaży,
    - sprzedaż w czasie,
    - liczbę zamówień w czasie.
 
   
 # Najważniejsze wnioski biznesowe

      1. Sprzedaż jest silnie skoncentrowana na rynku brytyjskim. United Kingdom jest krajem o najwyższej sprzedaży, a kolejne miejsca zajmują Netherlands i EIRE.
      2. Brakujące dane o klientach stanowią istotny problem jakości danych. Sprzedaż przypisana do pustego CustomerID wynosi 1 733 152,52 czyli około 16,3% całkowitej sprzedaży. Ogranicza to możliwość pełnej analizy zachowań klientów.
      3. Sprzedaż wykazuje sezonowość. Najwyższy poziom sprzedaży występuje w listopadzie, natomiast najniższy w lutym.
      4. Liczba zamówień jest zgodna z sezonowym wzorcem sprzedaży. Najwięcej zamówień występuje w listopadzie, a najmniej w lutym.
      5. Wybrane produkty mają szczególne znaczenie dla sprzedaży. Wśród produktów o najwyższej sprzedaży znalazły się Dotcom Postage, Regency Cakestand 3 Tier oraz Paper Craft Little Birdie.
 
     
 # Pliki projektu

    - Online_Retail.xlsx - dane i analiza w Excelu
    - Online_Retail_sql.csv - dane wykorzystane do analizy SQL
    - Online_Retail_sql_analysis.sql - zapytania sql
    - Analiza_Online_Retail.pdf - wersja raportu Power BI w formacie PDF
  
