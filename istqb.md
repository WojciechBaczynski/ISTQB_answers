# Testowanie  poziom podstawowy ISTQB by Wojciech Baczyński

## 1.1 Dlaczego testowanie jest niezbędne? 

##### 1.1.1 Kandydat potrafi opisać - podając przykłady - w jaki sposób usterka w oprogramowaniu może wyrządzić szkodę osobie, środowisku lub firmie.
>Oprogramowanie, które działa niepoprawnie może spowodować wiele problemów, stratę pieniędzy, czasu lub utratę reputacji biznesowej. Może nawet spowodować utratę zdrowia lub życia. 

##### 1.1.2 Kandydat rozróżnia przyczynę usterki od jej skutków.
> Przyczyna usterki to najczęścniej ludzki błąd, natomiast jej skutek to oprogramowanie działające nie tak jakbyśmy tego chcieli.

##### 1.1.3 Kandydat potrafi podać powody tego, że testowanie jest niezbędne opierając się na przykładach.  
>Rygorystyczne testy systemów i dokumentacji mogą pomóc w zmniejszeniu ryzyka wystąpienia problemów podczas użytkowania oprogramowania i przyczynić się do podniesienia jakości sytemu, jeżeli znalezione usterki zostaną poprawione przed wdrożeniem systemu do użytkowania.

##### 1.1.4 Kandydat potrafi uzasadnić, że testowanie stanowi część zapewnienia jakości i podać przykłady tego, w jaki sposób testowanie przyczynia się do zwiększenia jakości. 
>Za pomocą testów można zmierzyć jakość oprogramowania wyrażoną przez ilość znalezionych usterek zarówno dla funkcjonalnych jak i niefunkcjonalnych wymagań i atrybutów oprogramowania. Testowanie może budować zaufanie do jakości oprogramowania, jeżeli osoby testujące znajdują mało usterek lub nie znajdują ich wcale.

##### 1.1.5 Kandydat potrafi wyjaśnić i porównać pojęcia pomyłka, usterka, awaria oraz odpowiadające im pojęcia błąd i pluskwa, podając przykłady. 
>Człowiek może popełnić błąd (pomyłkę), która powoduje powstanie defektu (usterki, pluskwy) w kodzie programu lub dokumencie. Jeżeli kod zawierający defekt zostaje wykonany, system nie zrobi tego co powinien (lub wykona to czego nie powinien) powodując awarię. Usterki w oprogramowaniu, systemach lub dokumentach mogą prowadzić do wystąpienia awarii, ale nie wszystkie usterki powodują awarie. 

## 1.2	 Co to jest testowanie?

##### 1.2.1 Kandydat pamięta ogólne cele testowania. 
>Istnieją różne cele testowania:
>* znajdowanie usterek 
>* nabieranie zaufania do poziomu jakości 
>* dostarczanie informacji potrzebnych do podejmowania decyzji 
>* zapobieganie defektom 

##### 1.2.2 Kandydat potrafi podać przykłady celów testowania w różnych fazach cyklu życia oprogramowania. 
>Różne punkty widzenia pozwalają na wzięcie pod uwagę w testach różnych celów. Na przykład w testowaniu wytwórczym (np. testowaniu modułowym, integracyjnym lub systemowym) głównym celem może być wywołanie tylu awarii, ile się da, żeby zidentyfikować i poprawić usterki występujące w oprogramowaniu. W testach akceptacyjnych głównym celem może być potwierdzenie, że system działa tak jak powinien oraz nabranie pewności, że spełnia wymagania. W niektórych przypadkach celem testowania może być ocena jakości oprogramowania (bez intencji naprawiania defektów), by dostarczyć interesariuszom informacji o ryzyku związanym z wydaniem systemu w danej chwili. Testowanie pielęgnacyjne często zawiera testy sprawdzające, czy nie wprowadzono nowych usterek podczas wykonywania zmian. Głównym celem testowania produkcyjnego może być ocena atrybutów systemu takich jak niezawodność lub dostępność. 

##### 1.2.3 Kandydat rozróżnia testowanie od debagowania.
>Debagowanie różni się od testowania. Testowanie dynamiczne może pokazać awarie, których źródłem są usterki. Debagowanie jest czynnością programistyczną, która znajduje, analizuje i umożliwia usunięcie przyczyny awarii.

## 1.3	Siedem zasad testowania 

##### 1.3.1 Kandydat potrafi wyjaśnić siedem zasad testowania. 
> 1. Testowania ujawnia usterki 
> 2. Testowanie gruntowne jest niewykonalne 
> 3. Wczesne testowanie
> 4. Kumulowanie się błędów 
> 5. Paradoks pestycydów - jeżeli te same testy są powtarzane bez zmian, to w końcu przestaną znajdować nowe usterki. Żeby przezwyciężyć "paradoks pestycydów", testy muszą być regularnie przeglądane i uaktualniane.
> 6. Testowanie zależy od kontekstu - testowanie wykonuje się w różny sposób w różnym kontekście. Na przykład oprogramowanie krytyczne ze względu na bezpieczeństwo testuje się inaczej niż sklep internetowy. 
Zasada 7 - Mylne przekonanie o braku błędów 
Znajdowanie i naprawa usterek nie pomoże, jeżeli produkowany system nie nadaje się do użytkowania lub nie spełnia wymagań i oczekiwań użytkownika.


## 1.4 Podstawowy proces testowy

##### 1.4.1 Kandydat pamięta pięć podstawowych czynności testowych i odpowiadające im zadania od planowania do zamknięcia testów. 
	
>Podstawowy proces testowy składa się z następujących czynności: 
> * planowanie i nadzór nad testami 
Planowanie testów polega na zdefiniowaniu celów testowania i określeniu czynności testowych potrzebnych do wypełnienia misji i celów testowania. 
> * analiza i projektowanie testów 
Podczas analizy i projektowania testów ogólne cele testowania przekształcane są w konkretne warunki testowe i przypadki testowe. 
> * implementacja i wykonanie testów
Implementacja i wykonanie testów, to czynność, podczas której specyfikowane są procedury i skrypty testowe przez ustawienie przypadków testowych w konkretnej kolejności oraz dołączenie innych informacji potrzebnych do wykonania testów, konfigurowane jest środowisko testowe oraz wykonywane są testy.  
> * ocena kryteriów zakończenia i raportowanie 
Ocena spełnienia kryteriów zakończenia polega na ocenie wykonania testów zgodnie z przyjętymi celami testowania. Powinna ona być wykonywana dla każdego poziomu testowania.
> * czynności zamykające test 
W ramach czynności zamykających testy zbierane są dane z zakończonych czynności testowych, żeby utrwalić doświadczenie, testalia, fakty i liczby. Czynności zamykające testy wykonywane są przy kamieniach milowych projektu takich jak: wydanie systemu, zakończenie (lub anulowanie) projektu testowego, osiągnięcie kamienia milowego, lub zakończenie wydania serwisowego. 
	
## 1.5	Psychologia testowania 

##### 1.5.1 Kandydat pamięta czynniki psychologiczne, od których zależy sukces testowania. 

##### 1.5.2 Kandydat potrafi pokazać różnice w nastawieniu testera i programisty.
