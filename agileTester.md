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

## 2.1 Różnice pomiędzy tradycyjnym i zwinnym podejściem do testowania

### 2.1.1 Kandydat potrafi opisać różnice pomiędzy testowaniem w projektach zwinnych i tradycyjnych (nie zwinnych)

Jedną z podstawowych różnic pomiędzy tradycyjnymi a zwinnymi cyklami życia jest idea bardzo krótkich iteracji, z których każda kończy się działającym oprogramowaniem dostarczającym interesariuszom biznesowym wartościowej funkcjonalności. Na początku projektu następuje okres planowania wydania. Następnie mamy ciąg iteracji. Na początku każdej iteracji występuje okres jej planowania. Po wypracowaniu zakresu iteracji, wybrane historyjki użytkownika są wytwarzane, integrowane z systemem oraz testowane. Tego typu iteracje są wysoce dynamiczne, z czynnościami wytwarzania, integracji i testowania trwającymi przez cały czas iteracji, z istotnym zrównolegleniem i zachodzeniem na siebie tych czynności. Czynności testowe wykonywane są przez cały czas (np. codziennie), a nie tylko jako końcowe czynności iteracji.

### 2.1.2 Kandydat potrafi opisać, w jaki sposób czynności kodowania i testowania są zintegrowane w podejściu zwinnym

Projekty zwinne często bardzo mocno wykorzystują narzędzia automatyzujące tworzenie, testowanie oraz zarządzanie tworzeniem oprogramowania. Deweloperzy wykorzystują narzędzia do analizy statycznej, testów jednostkowych i do mierzenia ich pokrycia. Programiści ciągle komitują kod i testy jednostkowe do systemów zarządzania konfiguracją przy użyciu struktur budowania i testowania. Takie struktury umożliwiają ciągłą integrację oprogramowania z systemem; analiza statyczna i testy jednostkowe są powtarzane, gdy tylko nowe oprogramowanie zostanie wprowadzane.

### 2.1.3 Kandydat potrafi opisać rolę niezależnego testowania w projektach zwinnych

Niezależni testerzy są często bardziej efektywni w znajdowaniu defektów. W niektórych zespołach zwinnych, deweloperzy wytwarzają większość testów w formie testów automatycznych. Jeden lub więcej testerów może być członkiem zespołu, wykonując wiele zadań testowych. Jednakże umieszczenie testera w zespole rodzi pewne ryzyko utraty jego niezależności i braku obiektywnej oceny.

Inne zespoły zwinne utrzymują w pełni niezależny, wydzielony zespól testerski i angażują testerów „na żądanie” na końcu każdego sprintu. Taki proces pozwala na zachowanie niezależności, co sprawia, że testerzy mogą dokonywać obiektywnej, bezstronnej oceny oprogramowania. Jednakże brak czasu, brak zrozumienia nowych właściwości produktu oraz problemy w relacjach z interesariuszami biznesowymi i deweloperami mogą często powodować kłopoty przy takim podejściu.

Trzecia opcja to posiadanie niezależnego, oddzielonego zespołu testowego, gdzie testerzy są przydzieleni do zespołu zwinnego na zasadzie długoterminowej na początku projektu, co umożliwia im utrzymanie niezależności z jednoczesnym poznaniem produktu i nawiązaniem mocnych relacji z innymi członkami zespołu. Dodatkowo, niezależny zespół testowy może utrzymywać kilku wyspecjalizowanych testerów (poza zespołem zwinnym) pracujących nad zadaniami długoterminowymi lub nienależącymi do sprintu, jak np. tworzenie narzędzi do automatycznego testowania, wykonywanie testów niefunkcjonalnych, tworzenie i utrzymywanie środowisk i danych testowych oraz zajmowanie się poziomami testów, które trudno wpasować w sprinty (np. testy integracji systemów).

## 2.2 Status testowania w projektach zwinnych

### 2.2.1 Kandydat potrafi opisać podstawowy zbiór produktów używanych do informowania o statusie testów w projekcie zwinnym, włączając w to postęp testów i jakość produktu

By zapewnić stałe, szczegółowe wizualne przedstawienie aktualnego statusu całego zespołu, włączając w to status testów, zespoły mogą wykorzystywać zwinną tablicę zadań (ang. Agile task board). Karty historyjek, zadania deweloperskie, zadania testowe i inne zadania powstałe podczas planowania iteracji (patrz sekcja 1.2.5) są prezentowane na tablicy zadań, często przy pomocy kolorowych kart, gdzie kolor określa typ zadania. Podczas iteracji, zarządzanie postępem prac odbywa się poprzez przesuwanie odpowiednich kart zadań na tablicy miedzy kolumnami takimi jak: „do zrobienia”, „w toku”, „weryfikacja” oraz „zrobione”. Zespoły zwinne mogą używać narzędzi do obsługi kart historyjek oraz tablicy zadań, które to narzędzia mogą automatyzować uaktualnianie tablicy rozdzielczej i statusu.

### 2.2.2 Kandydat potrafi opisać proces ewoluowania testów w czasie wielu iteracji i potrafi wyjaśnić, dlaczego automatyzacja testów jest istotna przy zarządzaniu ryzykiem regresji w projektach zwinnych

W projektach zwinnych, produkt rośnie po zakończeniu każdej iteracji. Tym samym zwiększa się zakres testów. Wraz z testami zmian kodu dokonanych w czasie bieżącej iteracji, testerzy sprawdzają także, czy nie obniżono jakości właściwości, które były wytworzone iprzetestowane w poprzednich iteracjach. Ryzyko regresu właściwości jest wysokie w wytwarzaniu zwinnym, ze względu na rozległe zmiany w kodzie (dodawanie, modyfikowanie i usuwanie linii kodu z wersji na wersję). Ponieważ reagowanie na zmiany jest podstawową zasadą zwinności, dlatego też, w celu zaspokojenia potrzeby biznesowej, zmianom mogą podlegać uprzednio dostarczone właściwości. By utrzymać prędkość wytwarzania bez zaciągania dużego długu technicznego, krytyczna staje się jak najwcześniejsza inwestycja zespołu w automatyzację testów na wszystkich poziomach testów. Krytyczne jest także, by wszystkie produkty testowe takie jak: testy automatyczne, manualne przypadki testowe, dane testowe i inne artefakty testowe były aktualizowane w każdej iteracji. Dlatego też zaleca się, by wszystkie produkty testowe były zarządzane przy użyciu narzędzia do zarządzania konfiguracją. Zapewnia to kontrolę wersji, ułatwia dostęp wszystkim członkom zespołu, ułatwia zmiany wymagane przez zmieniającą się funkcjonalność, a równocześnie ciągle zachowuje historyczne informacje o produktach testowych.

## 2.3 Rola i umiejętności testera w zespole zwinnym

### 2.3.1 Kandydat rozumie umiejętności (ludzkie, dziedzinowe i testowe) testera w projekcie zwinnym

Testerzy w zespołach zwinnych powinni:

- Być pozytywni i zorientowani na rozwiązywanie problemów we współpracy z członkami zespołu i interesariuszami,
- Wykazywać krytyczne, zorientowane na jakość, sceptyczne myślenie o produkcie,
- Aktywnie zdobywać informacje od interesariuszy (nie polegać wyłącznie na spisanej specyfikacji),
- Dokładnie sprawdzać i raportować wyniki testów, postęp testów i jakość produktu,
- Skutecznie pracować z przedstawicielami klienta i interesariuszami definiując
  testowalne historyjki użytkownika (przede wszystkim kryteria akceptacyjne),
- Współpracować w zespole, pracując w parach z programistami lub innymi członkami
  zespołu,
- Szybko reagować na zmiany, przez np. zmienianie, dodawanie i poprawianie
  przypadków testowych,
- Planować i organizować swoją własną pracę.

### 2.3.2 Kandydat rozumie rolę testera w projekcie zwinnym

Rola testera w zespole zwinnym obejmuje czynności, które generują i dostarczają informacje zwrotne dotyczące nie tylko statusu testów i jakości produktu, ale także jakości procesu. Poza czynnościami opisanymi w innych miejscach tego sylabusa, czynności te obejmują:

- Zrozumienie, implementowanie i poprawianie strategii testów,
- Mierzenie i raportowanie pokrycia testowego względem wszystkich dostępnych wymiarów pokrycia,
- Zapewnienie poprawnego użycia narzędzi testowych.
- Konfigurowanie, używanie i zarządzanie środowiskiem testowym i danymi testowymi,
- Raportowanie defektów i współpraca z zespołem przy ich rozwiazywaniu,
- Trenowanie (coaching) innych członków zespołu w różnych aspektach związanych z testowaniem.
- Zapewnienie, że odpowiednie zadania testowe są harmonogramowane podczas planowania wydania i iteracji,
- Aktywna współpraca z deweloperami, interesariuszami biznesowymi i właścicielami produktu, by poprawnie interpretować wymagania, zwłaszcza w zakresie ich
  testowalności, spójności i kompletności,
- Proaktywne uczestnictwo w retrospektywach zespołu, sugerowanie i implementowanie udoskonaleń.
