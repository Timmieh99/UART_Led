
UART-drivrutin för STM32F411x-plattformen, med inkluderad LED-funktion.

Detta projekt innehåller en UART-drivrutin skriven i C++ för mikrokontrollerplattformen STM32F411x. Drivrutinen tillhandahåller funktioner för att initialisera och konfigurera UART-periferin, överföra och ta emot data med hjälp av UART-gränssnittet samt hantera avbrott som genereras av UART-periferin. Den innehåller också en LED-funktion för demonstrationsändamål.

Krav

För att använda denna drivrutin behöver du följande:
````
STM32F411x utvecklingskort
  
STM32CubeIDE eller annan kompatibel IDE
  
UART-kabel eller USB till UART-omvandlare
````
Användning
````
Klona eller ladda ner källkoden som en ZIP-fil från detta repository.
  
Importera projektet till din IDE
  
Kör main.cpp filen
````
Funktioner

Följande funktioner tillhandahålls av UART-drivrutinen:
````
void USART2_Init()

int USART2_write()

int USART2_read()
````

