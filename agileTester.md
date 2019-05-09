# Testowanie poziom zwinny ISTQB by Wojciech Baczyński

## 1.1 Podstawy zwinnego wytwarzania oprogramowania

### 1.1.1 Kandydat pamięta podstawowe zasady zwinnego wytwarzania oprogramowania w oparciu o Manifest Agile

Manifest Agile zawiera cztery główne zasady:

- ludzie i współpraca ponad procesy i narzędzia,
- działające oprogramowanie ponad obszerną dokumentację,
- współpraca z klientem ponad formalne ustalenia,
- reagowanie na zmiany ponad podążanie za planem.

### 1.1.2 Kandydat rozumie korzyści wynikające z podejścia “cały zespół”

Wykorzystanie podejścia „cały zespół” do wytwarzania produktów stanowi jedną z głównych korzyści zwinnego wytwarzania oprogramowania. Podejście „cały zespół” ma wiele zalet, między innymi:

- Poprawia współpracę i komunikację w zespole,
- Umożliwia wykorzystanie synergii umiejętności członków zespołu z pożytkiem dla całego projektu,
- Czyni wszystkich odpowiedzialnymi za jakość.

### 1.1.3 Kandydat rozumie korzyści wynikające z wczesnego i częstego otrzymywania informacji zwrotnej

Zyskami z szybkiego i częstego otrzymywania informacji zwrotnej są, m.in.:

- Uniknięcie niezrozumienia wymagań, wykrycie czego w późnych etapach cyklu
  wytwórczego oraz poprawienie będzie dużo bardziej kosztowne,
- Wyjaśnianie zgłoszeń klienta odnośnie właściwości. Wczesne i regularne wyjaśnianie żądań podczas wytwarzania, zwiększa prawdopodobieństwo, że kluczowe właściwości będą dostępne dla użytkownika wcześniej i że produkt będzie bardziej odzwierciedlał
  to, co klient potrzebuje,
- Natychmiastowe ostrzeganie zespołu wytwórczego o problemach jakościowych przy
  wykorzystaniu procesu ciągłej integracji. Problemy mogą być łatwiej izolowane i
  rozwiązywane niż gdyby zostały wykryte później w cyklu wytwórczym,
- Informowanie zespołu zwinnego o jego wydajności i zdolności do dostarczenie
  produktu na czas,
- Promowanie stałego tempa prac projektowych.

## 1.2 Aspekty podejść zwinnych

### 1.2.1 Kandydat pamięta podejścia zwinne do wytwarzania oprogramowania

Nie istnieje jedno podejście do zwinnego wytwarzania oprogramowania, ale wiele różnych podejść. Każde z nich inaczej implementuje wartości i zasady z Manifestu Agile. Do popularnych podejść należą:

- eXtreme Programming,
- scrum,
- kanban.

### 1.2.2 Kandydat potrafi napisać historyjki użytkownika we współpracy z wytwórcami, przedstawicielami biznesu i właścicielem produktu

Historyjki użytkownika muszą obejmować zarówno właściwości funkcjonalne jak i niefunkcjonalne. Każda historyjka powinna zawierać kryteria akceptacji dla tych właściwości. Te kryteria powinny być definiowane we współpracy pomiędzy przedstawicielami biznesu, deweloperami i testerami. Kryteria te dostarczają deweloperem i testerom dokładniejszej wizji właściwości, którą reprezentanci biznesu będą sprawdzać. Zespół zwinny uważa zadanie za ukończone, gdy zbiór kryteriów akceptacyjnych jest spełniony.

### 1.2.3 Kandydat rozumie, jak spotkania retrospektywne mogą być wykorzystywane jako mechanizm do doskonalenia procesu w projektach zwinnych

W wytwarzaniu zwinnym, retrospektywa to spotkanie na końcu każdej iteracji, na którym dyskutuje się o tym, co się udało, co można poprawić, jak wdrożyć poprawki i powtórnie osiągnąć sukces w następnej iteracji. Retrospektywa obejmuje takie zagadnienia jak proces, ludzie, organizacja, relacje i narzędzia. Regularnie przeprowadzane spotkanie retrospektywne, po których następują odpowiednie działania, są krytyczne dla samoorganizacji i ciągłego doskonalenia wytwarzania oraz testowania.

### 1.2.4 Kandydat rozumie wykorzystanie i cele ciągłej integracji

Dostarczanie przyrostów produktu wymaga niezawodnego, pracującego, zintegrowanego oprogramowania na koniec każdego sprintu. Ciągła integracja podejmuje to wyzwanie poprzez regularne łączenie wszystkich zmian wykonanych w oprogramowaniu i integrację wszystkich zmienionych modułów przynajmniej raz dziennie. Zarządzanie konfiguracją, kompilacja, budowanie wersji, wprowadzanie i testowanie tworzą pojedynczy, zautomatyzowany, regularnie powtarzany proces. Ponieważ deweloperzy integrują swoją pracę stale, budują stale i testują stale, błędy w kodzie są wykrywane szybciej.

### 1.2.5 Kandydat zna różnice pomiędzy planowaniem iteracji i wydania, a także wie, w jaki sposób tester dodaje wartości każdej z tych aktywności

Planowanie wydania przewiduje wydanie produktu, często kilka miesięcy od rozpoczęcia projektu. Planowanie wydań definiuje i przedefiniowuje backlog produktu i może zawierać przerabianie dużych historyjek użytkownika w zbiór mniejszych historyjek. Planowanie wydania dostarcza podstawy do podejścia do testów oraz do planu testów i rozciąga się na wszystkie iteracje. Plany wydania są wysokopoziomowe.

Testerzy są zaangażowani w planowanie wydania będąc szczególnie użytecznymi przy następujących czynnościach:

- Definiowanie testowalnych historyjek użytkownika, włączając w to kryteria akceptacji,
- Branie udziału w analizie ryzyk projektowych i jakościowych,
- Szacowanie nakładu pracy związanego z historyjkami użytkownika,
- Definiowanie potrzebnych poziomów testów,
- Planowanie testów dla wydania.

Podczas planowania iteracji, zespół wybiera historyjki użytkownika z ustawionych według priorytetu w backlogu produktu, uszczegóławia historyjki użytkownika, wykonuje analizę ryzyka dla historyjek, oraz szacuje pracę potrzebną do wykonania każdej historyjki. Jeżeli jakaś historyjka użytkownika jest zbyt mglista i nie powiodą się próby jej rozjaśnienia, zespół może odrzucić tę historyjkę i wziąć następną historyjkę zgodnie z priorytetami. Reprezentanci biznesu mają obowiązek odpowiadać na pytania zespołu na temat każdej historyjki, tak by zespół wiedział jak implementować każdą historyjkę i jak ją testować.

Testerzy są zaangażowani w planowanie iteracji będąc szczególnie użytecznymi w następujących czynnościach:

- Udział w szczegółowej analizie ryzyka dla historyjek użytkownika,
- Określanie testowalności historyjek użytkownika,
- Tworzenie testów akceptacyjnych dla historyjek użytkownika,
- Dzielenie historyjek użytkownika na zadania (zwłaszcza zadania testowe),
- Szacowanie pracochłonności zadań testowych.
- Identyfikowanie funkcjonalnych i niefunkcjonalnych własności systemu, które trzeba przetestować,
- Wspieranie i udział w automatyzacji testów na różnych poziomach testowania.
