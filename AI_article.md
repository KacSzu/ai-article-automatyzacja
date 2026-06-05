# AI w służbie kodu – jak sztuczna inteligencja zmienia cykl życia oprogramowania

## Wstęp

Rozwój sztucznej inteligencji w ostatnich latach znacząco wpłynął na sposób tworzenia oprogramowania. Narzędzia wykorzystujące modele językowe przestały pełnić wyłącznie funkcję wyszukiwarek informacji lub chatbotów. Coraz częściej stają się integralną częścią środowiska pracy programistów, wspierając proces projektowania, implementacji, testowania oraz utrzymania aplikacji.

Szczególnie istotne zmiany można zaobserwować w obszarze systemów kontroli wersji oraz platform wspierających współpracę zespołową, takich jak GitHub czy GitLab. Narzędzia oparte na sztucznej inteligencji są obecnie zdolne do generowania kodu, analizy podatności bezpieczeństwa, tworzenia dokumentacji, a nawet samodzielnego wykonywania wybranych zadań programistycznych.

Celem niniejszego artykułu jest przedstawienie wpływu sztucznej inteligencji na współczesny proces wytwarzania oprogramowania. Omówione zostaną zarówno korzyści wynikające z wykorzystania AI, jak również wyzwania prawne, etyczne i technologiczne związane z jej dynamicznym rozwojem.

---

## ## 1. Agentic AI i inteligentna orkiestracja

Jednym z najciekawszych kierunków rozwoju sztucznej inteligencji jest Agentic AI. Termin ten odnosi się do systemów, które nie ograniczają się wyłącznie do generowania odpowiedzi na polecenia użytkownika, ale są zdolne do samodzielnego planowania oraz wykonywania określonych działań prowadzących do osiągnięcia wyznaczonego celu. W praktyce oznacza to przejście od roli cyfrowego asystenta do roli aktywnego uczestnika procesu wytwarzania oprogramowania.

W nowoczesnych środowiskach DevSecOps agenci AI mogą analizować zgłoszenia błędów, identyfikować obszary wymagające zmian, przygotowywać propozycje implementacji oraz wykonywać testy weryfikujące poprawność rozwiązania. Coraz częściej wykorzystuje się je również do monitorowania jakości kodu i wykrywania potencjalnych problemów bezpieczeństwa jeszcze przed wdrożeniem aplikacji na środowisko produkcyjne.

Przykładem zastosowania tego podejścia jest GitLab Duo, które umożliwia automatyczne przekształcanie zgłoszeń typu issue w gotowe merge requesty. System analizuje treść zgłoszenia, identyfikuje pliki wymagające modyfikacji, proponuje odpowiednie zmiany i generuje dokumentację opisującą wykonane działania. Dzięki temu programista może skoncentrować się na weryfikacji rozwiązania zamiast wykonywać wszystkie czynności ręcznie.

Istotnym zastosowaniem Agentic AI jest także obszar cyberbezpieczeństwa. Agenci mogą analizować zależności wykorzystywane przez aplikację, wykrywać podatności opisane w bazach CVE oraz automatycznie proponować aktualizacje bibliotek. W niektórych przypadkach możliwe jest również wygenerowanie gotowej poprawki eliminującej wykryty problem bezpieczeństwa.

Wraz ze wzrostem możliwości agentów AI pojawiają się jednak nowe wyzwania. Konieczne jest zachowanie odpowiedniego poziomu kontroli nad podejmowanymi decyzjami oraz zapewnienie pełnej przejrzystości wykonywanych działań. Z tego powodu większość współczesnych rozwiązań opiera się na modelu „human-in-the-loop”, w którym ostateczna decyzja o wdrożeniu zmian nadal należy do człowieka.

Można przypuszczać, że w kolejnych latach Agentic AI stanie się standardowym elementem środowisk programistycznych. Narzędzia te będą przejmować coraz większą liczbę powtarzalnych zadań, pozwalając zespołom deweloperskim skupić się na projektowaniu architektury systemów oraz rozwiązywaniu bardziej złożonych problemów biznesowych.

---

## 2. Ekosystem AI na platformie GitHub

GitHub jest obecnie jedną z najważniejszych platform wspierających rozwój oprogramowania. W ostatnich latach firma znacząco inwestuje w rozwiązania wykorzystujące sztuczną inteligencję, tworząc rozbudowany ekosystem narzędzi wspierających pracę programistów.

Najbardziej znanym rozwiązaniem jest GitHub Copilot. Narzędzie zostało opracowane przez GitHub we współpracy z OpenAI i działa jako tzw. AI pair programmer. Oznacza to, że podczas pisania kodu użytkownik otrzymuje podpowiedzi generowane w czasie rzeczywistym przez model sztucznej inteligencji.

Copilot potrafi generować pojedyncze linie kodu, całe funkcje, testy jednostkowe, a nawet fragmenty dokumentacji technicznej. Dzięki analizie kontekstu projektu narzędzie jest w stanie proponować rozwiązania dopasowane do aktualnie realizowanego zadania.

Według danych prezentowanych przez GitHub, w projektach wykorzystujących Copilot znaczna część nowego kodu powstaje przy udziale sztucznej inteligencji. W przypadku języka Python udział ten sięga około 40%. Wyniki badań wskazują również na wzrost produktywności programistów korzystających z tego rozwiązania.

Oprócz Copilota GitHub rozwija także inne narzędzia związane z AI. GitHub Models umożliwia porównywanie modeli językowych oraz testowanie promptów bezpośrednio w środowisku GitHub. Z kolei GitHub Spark pozwala tworzyć inteligentne aplikacje wykorzystujące modele generatywne.

Rozwój tych rozwiązań wskazuje, że platformy hostingowe przestają być jedynie miejscem przechowywania kodu. Coraz częściej stają się kompleksowymi środowiskami wspierającymi cały proces tworzenia oprogramowania.

---

## 3. Kontrowersje prawne i kwestia własności intelektualnej

Pomimo licznych korzyści wynikających z wykorzystania sztucznej inteligencji, rozwój tego typu technologii budzi wiele kontrowersji natury prawnej i etycznej.

Jednym z najgłośniejszych sporów ostatnich lat jest postępowanie sądowe dotyczące GitHub Copilot. Powodem konfliktu stał się sposób trenowania modeli AI na ogromnych zbiorach publicznie dostępnego kodu źródłowego.

Krytycy wskazują, że wiele projektów open source zostało wykorzystanych podczas trenowania modeli bez wyraźnej zgody autorów. Pojawiają się również zarzuty dotyczące naruszania warunków licencji open source, które często wymagają zachowania informacji o autorstwie lub udostępniania kodu na określonych zasadach.

Dodatkowym problemem jest możliwość generowania przez AI fragmentów kodu bardzo podobnych do istniejących rozwiązań. W takiej sytuacji powstaje pytanie, kto jest faktycznym autorem wygenerowanego kodu oraz kto ponosi odpowiedzialność za ewentualne naruszenia praw autorskich.

Istotnym zagadnieniem pozostaje również odpowiedzialność za błędy. Jeżeli programista wykorzysta kod wygenerowany przez AI, który zawiera podatność bezpieczeństwa lub prowadzi do awarii systemu, trudno jednoznacznie określić zakres odpowiedzialności poszczególnych stron.

Niektórzy eksperci zwracają także uwagę na ryzyko nadmiernego uzależnienia programistów od narzędzi AI. Korzystanie z gotowych rozwiązań może prowadzić do ograniczenia samodzielnego rozwoju kompetencji technicznych, szczególnie wśród początkujących programistów.

W związku z tym wiele organizacji pracuje obecnie nad stworzeniem nowych regulacji prawnych określających zasady wykorzystania sztucznej inteligencji w procesie tworzenia oprogramowania.

---

## 4. Przyszłość kontroli wersji i Git 3.0

System Git od wielu lat stanowi podstawę współpracy programistów na całym świecie. Pomimo ogromnej popularności technologia ta również podlega zmianom wynikającym z rozwoju sztucznej inteligencji oraz rosnącej skali projektów informatycznych.

Jednym z najważniejszych kierunków rozwoju jest zwiększenie bezpieczeństwa repozytoriów poprzez wykorzystanie algorytmu SHA-256. Ma to na celu ograniczenie ryzyka kolizji identyfikatorów oraz poprawę bezpieczeństwa przechowywanych danych.

Kolejnym wyzwaniem jest obsługa bardzo dużych repozytoriów wykorzystywanych przez globalne organizacje technologiczne. Wraz ze wzrostem liczby plików i współpracujących programistów konieczne staje się opracowywanie nowych metod zarządzania historią zmian.

Coraz większą rolę odgrywa również sztuczna inteligencja wspierająca proces code review. Już obecnie możliwe jest automatyczne wykrywanie potencjalnych błędów, problemów wydajnościowych oraz naruszeń standardów kodowania jeszcze przed analizą przeprowadzaną przez człowieka.

W przyszłości AI może przejąć część zadań związanych z zarządzaniem repozytorium. Możliwe stanie się automatyczne rozwiązywanie konfliktów, grupowanie powiązanych zmian czy sugerowanie optymalnej struktury projektu.

Pojawiają się także alternatywne koncepcje wykorzystujące technologię blockchain do przechowywania historii zmian. Rozwiązania te mają zapewnić większą transparentność oraz odporność na manipulacje. Obecnie pozostają jednak głównie na etapie eksperymentalnym.

Pomimo dynamicznego rozwoju nowych technologii trudno wyobrazić sobie całkowite zastąpienie Gita w najbliższych latach. Bardziej prawdopodobny wydaje się scenariusz, w którym sztuczna inteligencja stanie się dodatkową warstwą wspierającą istniejące systemy kontroli wersji.

---

## Podsumowanie

Sztuczna inteligencja w coraz większym stopniu wpływa na sposób tworzenia i utrzymywania oprogramowania. Narzędzia takie jak GitHub Copilot, GitHub Models czy GitLab Duo pozwalają automatyzować wiele czynności wykonywanych dotychczas przez programistów.

Szczególnie interesującym kierunkiem rozwoju jest Agentic AI, w którym sztuczna inteligencja nie tylko wspiera użytkownika, ale samodzielnie realizuje określone zadania w procesie deweloperskim. Rozwiązania tego typu mogą znacząco zwiększyć produktywność zespołów oraz skrócić czas potrzebny na dostarczanie nowych funkcjonalności.

Jednocześnie rozwój AI wiąże się z licznymi wyzwaniami dotyczącymi bezpieczeństwa, odpowiedzialności prawnej oraz ochrony własności intelektualnej. Problemy te wymagają dalszych analiz oraz dostosowania obowiązujących regulacji do nowych realiów technologicznych.

W naszej ocenie sztuczna inteligencja nie zastąpi programistów w najbliższej przyszłości. Zmieni jednak charakter ich pracy, przejmując zadania rutynowe i wspomagając proces podejmowania decyzji. Ostateczna odpowiedzialność za jakość, bezpieczeństwo i rozwój oprogramowania nadal będzie należeć do człowieka.

---

# Bibliografia

1. GitLab – Finally, AI for the entire software lifecycle.
2. GitLab Duo Documentation.
3. GitLab AI Features Overview.
4. GitHub Documentation – AI Tools.
5. GitHub Copilot Documentation.
6. GitHub Copilot Productivity Research.
7. GitHub Copilot Litigation Information.
8. United States Court Documents regarding Copilot Litigation.
9. Open Source Initiative – Licensing Resources.
10. Git Project Documentation.
11. Git Rev News.
12. Research on Version Control Systems and Monorepositories.
13. Studies on Blockchain-based Version Control Systems.
14. Reports concerning the future of AI-assisted software development.
