[ENG]
This is an implemented aMPC algorithm (for S7-1215C) that operates based on a predictive model in the form of an impulse response, adapting its parameters at each step of the algorithm. It is a multivariable version supporting 4 inputs and 3 outputs. It was used to control a plant consisting of a nonlinear three-tank cascade. The implementation was based on the use of a Scheduler framework, designed to control the load on the controller during each operating cycle.

Key parameters:
prediction horizon - 20,
control horizon - 1,
sampling time - 8 s.

[PL]
Jest to zaimplementowany algorytm aMPC (dla S7-1215C) opierający swoje działanie na modelu predykcyjnym w postaci odpowiedzi impulsowej adaptującym swoje parametry w każdym kroku algorytmu. Wersja wielowymiarowa obsługująca 4 wejścia/3 wyjścia. Posłużył on do sterowania obiektu w postaci nieliniowej kaskady trzech zbiorników. Implementacja opierała się na wykorzystaniu frameworku Schedulera - przeznaczonego do kontrolowanego obciążania sterownika w każdym cyklu jego pracy.

Kluczowe parametry:
horyzont predykcji - 20,
horyzont sterowania - 1,
czas próbkowania - 8 s.
