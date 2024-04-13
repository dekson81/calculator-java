



								README fajl:


Assignment - Metrika, pregled i statička analiza

Ovaj projekat sadrži dve Java datoteke:Calculator.java,Start.java. i Oba fajla se analiziraju da bi se identifikovali potencijalni problemi i rešenja..

## Calculator java: 188 linija koda

- **Start Line:24
- **End Line:26
- **Lines of Code koda:3
- **Cyclomatic Complexity:1
- 

Analiza složenost napravljena upotrebom ekstenzije "Codalyze"u VCS okruzenje

Function Name:Calculator::Operations Start Line:15 End line:16 Cyclomatic Complexity (Threshold: 10):1 
Lines of Code (Threshold: 50):2 Parameter Count (Threshold: 4):0

Function Name: Calculator::Operations::ToString Line:18 End line:20 Cyclomatic Complexity (Threshold: 10):1
Lines of Code (Threshold: 50):3 Parameter Count (Threshold: 4):0

Function Name:Calculator::Run Start Line:24 End line:26 Cyclomatic Complexity (Threshold: 10):1
Lines of Code (Threshold: 50):3 Parameter Count (Threshold: 4):1

Function Name: Calculator::evaluateExpression Start Line:28 End line:72 Cyclomatic Complexity (Threshold: 10):12
Lines of Code (Threshold: 50):77 Parameter Count (Threshold: 4):1

Function Name:Calculator::Calculate Start Line:74 End Line:186 Cyclomatic Complexity (Threshold: 10):12
Lines of Code (Threshold: 50):77 Parameter Count (Threshold: 4):2

Function Name:Start::main Start Line:5 End lin:24 Cyclomatic Complexity (Threshold: 10):3 
Lines of Code (Threshold: 50):16 Parameter Count (Threshold: 4):1

Staticka analiza koda napravjlena uz pomoc SonarLint alata:
Calculator.java - 4 - Dodati private konstruktor Calculator.java - 18 - Preimenovati metodu "To string",
moguca kolizija sa drugom metodom is superklase Calculator.java - 24 - Preimenovati,bez velikog procentnog slova,
nije u skladu sa konvecijom pisanja Calculator.java - 70 - Doraditi kod,lokalna varijabla je suvisna Calculator.java - 74 -
Preimenovati,bez velikog procentnog slova Calculator.java - 183 - Void metoda,moze se izbrisati
Start.java - 6 - Preimenovati varijablu start.java - 8 i 19 - Lint nudi klasu Loggeri logging metode,umesto System.out   
