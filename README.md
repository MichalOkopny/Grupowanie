## Analizowane metody
1. **Hierarchiczne grupowanie**
   - Metryki odległości: `euclidean`, `cityblock`, `cosine`
   - Metody łączenia: `ward`, `average`, `complete`
   - Wizualizacja dendrogramów
   - Przypisanie obserwacji do klastrów

2. **K-Means**
   - Klasteryzacja dla różnych `k`
   - Wybór optymalnego `k` na podstawie **Silhouette Score**
   - Wizualizacja wyników

##  Najlepszy model
Na podstawie wyników **najlepiej sprawdził się model K-Means** z optymalnym `k` wybranym na podstawie **Silhouette Score**. Zapewnił on:
- Dobrą separację klastrów  
- Skalowalność na większych zbiorach danych  
- Przejrzystą interpretację wyników  
