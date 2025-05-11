Projekt klasyfikacji binarnej na podstawie realnych danych Tajwańskich przedsiębiorstw (źródło: https://doi.org/10.24432/C5004D).
W ramach 6819 obserwacji z 96 zmiennymi mamy stosunek ilościowy klas ok. 97:3 w ramach zmiennej objaśnianej.

W przygotowaniu modelu wykorzystano biblioteki: pandas, scikit-learn, imblearn, matplotlib

Projekt obejmuje min.:
- krótki przegląd danych
- test kilku bazowych modeli uczenia maszynowego za pomocą kroswalidacji
- test modelu XGBoost ze zmienionymi wagami
- eksperymenty z różnymi metodami oversamplingu i undersamplingu
- konstrukcję własnej metryki oceny modelu
- przeszukiwanie siatki hiperparametrów modeli 
