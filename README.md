# concrete-strenght-calculator
Prosta analiza wpływu poszczególnych składników na końcową wytrzymałość betonu na ściskanie

## Jest to wersja "step by step"
Każda linijka będzie opisana komentarzem.
Powstała ona w celu nauki własnej i lepszego zrozumienia pisanego kodu i operacji wykonywanych na danych

## Predykcja wytrzymałości betonu na ściskanie

Wytrzymałość na ściskanie betonu jest określana zazwyczaj w przedziale od 7 do 28 dni (lub w czasie równoważnym do cementu) wg normy PN-EN 206.

Ze względu na długi czas oczekiwania na wynik a w szczególności w oczekiwaniu na korekty w składzie betonu postanowiłem opracować model uczenia maszynowego którego celem jest określenie wytrzymałości betonu na ściskanie dla różnych składników wejściowych.
Korekty w składzie mieszanki betonowej dokonuje się najczęściej w przypadku niewłaściwej konsystencji mieszanki lub osiągnięcia niewystarczającej wytrzymałości na ściskanie. Dzięki takiemu modelowi będzie można zbadać wpływ poszczególnych skladników na mieszankę betonową a w konsekwencji dobrać ilościowo surowiec w sposób jak najbardziej optymalny 

Wartości zostaną obliczone za pomocą kilku rodzajów modeli w celu wybrania najbardziej optymalnego rozwiązania i miarodajnego rozwiązania
Poniższa baza powstała w zakładzie prefabrykacji podczas zarobów próbnych i testowej produkcji betonu.
Zawiera ona informacje z naważania składników oraz wytrzymałość na ściskanie po określonej ilości dni
W celu zwiększenia ilości próbek w danych wsadowych uwzględniono również wyniki badań kostek "świadków" w wieku od 90 do 365 dni oraz zbiór danych z serwisu kaggle.com

## Ze względu na testowanie nowych funkcjonalności do odwołania inne pliki .jpynb niż test predykcji nie będą upubliczniane
