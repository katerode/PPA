# PPA
MVC Model (onto), View (widok, aplikacja, formatka, ekrany z danymi), Controller (logika, co się dzieje, gdy..)
Refleksja - narzędzie mówiące, że język programowania wie coś o kodzie. Ma dostęp do metadanych w trakcie uruchomiania np. do klasy. 
Pozwala na rozdzielenie warstw aplikacji. Kod zawierający niewypełnione dane np. controller z polami odp elementom formularza. 
Nie musimy ręcznie stwarzać formatki i uzupełniać ręcznie pól. Framework robi to za nas. Controller z oznczonymi polami załatwia sprawę.   

#PPA 8.11
Debugatory
błędy krytyczne i błędy logiczne
debugery błędy run-time error, widac w konsoli, niewidac graficznie
kropka po lewej str- zatrzymuje tam gdzie chcemy, mozna jej podać wyjątki, odpalanie aplikacje w trybie debug, f5 f7 f8, po liniejce, wskocz do środka, podglad wartości zmiennych aktualnych, wywolanie dowolnego wyrażenia zeby zobaczyć jego wartość 

paradygmant oparty na zdarzeniach 
aplikacje nie robią rzeczy krok po kroku, rejestrujemy przwne rzeczy, a aplikacja reaguje. 
niedodajemy komorka po komorce, tylko obiekt semantyczny jako wiersz, a odpowiednie generatory wartosci generuja wypelnienie, preksztalca na dane do komorek. podajemy obiekt, ktore wypluwaja dane. przygotowujemy najpierw generatory wartości. programowanie sterowane zdarzeniowo, podajemy jakies dane i odpowiedie narzędzia przekształcają je. 
 
Fabryki a generatory 
wypluwa obiekty na podstawie parametrów np. zawartość komórki 
produkuje inne obiekty a nie robi rzeczy
wszytsko atomowe, niezalezne od siebie, spajane w mechanizmie, ktory je wykorzystuje
fabryka bierze i tworzy fabrykę na rządanie, jaksciowo nowy obiekt
generator - na podstawie jednego obiektu tworzy inny obiekt
2 rozne cele 
fabryki ---> opakowanie tworzenia nowych obiektów, w miejscu gdzie aplikacja wymaga tworzenia nowych obiektó∑
generatory ---> tam gdzie musimy przetwarzac jedne obiekty na inne obiektyfor (Ta

lambdy i klasy wewnętrzne

delegaci - obiektu, ktore mają jeden cel - jedna funkcja, klasy z 1 metodą 
public void initialize(){
for (TableColumn<String,?> column: table.getColumns()) {
if ("napis".equals(column.getId()))}
column.setCellValueFactory();
) else if ("dlugosc".equals(column.getId())) {
duzo roboty go to  lambda
zrobić klasę w miejscu, lokalnie, która jest podklasą , nie ma nazwy nazywa się klasa anonimową "
tam gdzie mamy funkcję, interfejs funkcyjny, tam gdzie mamy tylko 1 niezaimplementowaną metodę,
mozna zastąpic klasę anonimową(za każdym razem jest to nowa klasa) lambdą, która nie ma stanu. 
fabryka : 2 metody, tez się nie da. 

