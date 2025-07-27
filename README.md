# content_lifespan
Analiza cyklu życia publikacji Onet LS. Cel: Zrozumienie, jak długo artykuł generuje ruch po publikacji oraz jakie czynniki wpływają na jego trwałość, aby:  Pomóc redakcji planować publikacje efektywne pod względem retencji ruchu.  Wskazać treści warte ponownej promocji lub aktualizacji.  Lepsze dopasowanie strategii dystrybucji do typu treści.

## 🧰 Wymagania

- Python 3.8+
- Pandas, NumPy, Matplotlib, Seaborn

Zalecane jest utworzenie środowiska wirtualnego i instalacja zależności z pliku `requirements.txt`.

## 📁 Dane wejściowe

Notebook nie zawiera osadzonego pliku CSV. Użytkownik zostanie poproszony o podanie ścieżki do pliku z danymi w formacie:

`Analiza cyklu życia artykułu_LS_14.06-13.07.csv`

Podczas uruchamiania notebooka pojawi się komunikat:

```python
file_path = input("Podaj ścieżkę do pliku CSV: ")
df = pd.read_csv(file_path)

