========================
Preemptivní multitasking
========================

V preemptivním multitaskingu rozhoduje o spouštění úloh (procesů) výhradně systém. V pravidelných intervalech pohybujících se okolo 100x až 1000x za sekundu dostane procesor přerušení od časovače a přeruší aktuálně prováděnou úlohu. Procesor nyní zváží priority úloh a jiné aspekty a na základě nich se rozhodne, zda spustí jinou úlohu, či nechá pokračovat stávající. Hlavní výhodou je, že i když se úloha zacyklí, tak po příznaku přerušení od daného časovače může tuto úlohu pozastavit a spustit jinou.

