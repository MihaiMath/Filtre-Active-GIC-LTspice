# Proiect: Analiza și Simularea Filtrelor Active Trece-Jos
1. Descriere Generală
Acest proiect prezintă proiectarea și validarea unor filtre active Trece-Jos (TJ) cu frecvența de tăiere de 400 Hz, utilizând aproximațiile Butterworth și Chebyshev. Proiectul urmărește tranziția de la calcule matematice ideale la circuite electronice funcționale.

2. Conținutul Proiectului
Calcul Teoretic: Determinarea polilor și a factorilor de calitate (Q) pentru modelarea Laplace.

Implementare Biquad: Realizarea filtrelor folosind structurile Tow-Thomas (TT) și Multiple Feedback (MFB).

Sinteză de Inductanță (GIC): Utilizarea Convertorului de Impedanță Generalizat (Antoniou) pentru a înlocui bobinele din prototipurile LC, demonstrând echivalența acestora.

Optimizare E24: Adaptarea circuitelor la componente comerciale din seria standard E24.

3. Validare și Simulare
Toate schemele atașate sunt realizate în LTspice și pot fi deschise sau utilizate direct în acest software pentru:

Analiza AC: Verificarea răspunsului în frecvență și a pantei de tăiere.

Analiza Transient: Observarea răspunsului la impuls și a regimului tranzitoriu (overshoot).

Comparație: Validarea faptului că modelul cu componente reale (E24) respectă specificațiile modelului matematic.

4. Concluzii
Proiectul confirmă faptul că un circuit activ de tip GIC poate simula fidel o inductanță ideală, permițând realizarea unor filtre precise fără utilizarea componentelor magnetice voluminoase.
