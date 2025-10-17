
*/Ocena końcowa = ocena z ćwiczeń
UPeL = wykłady w .pdf/*


**Outline:**
1) literatura
2) Arytmetyka modularna
3) Wprowadzenie do kryptografii
4) Kryprtografia klucza prywatnego
	- Szyfr Cezara
	- Kryptografia z użyciem mnożenia *mod* a

---

**Literatura**
- Discrete Mathematics for Computer Scientists (C. Stein)
- Discrete Mathematics and Its Applications (Rosen)
- Mateamtyka Dyskretna. Niezbędnik dla informatyków
-- uzupełniająca --
- Księga szyfrów, Od starożytnego Egiptu do kryptografii kwantowej (S. Singh)
- Tajemne przekazy. Szyfry, Enigma i karty chipowe (R. Kippenhahn)
- Kryptografia. W teorii i praktyce
- Nowoczesna kryptografia. Praktyczne wprowadzenie do szyfrowania

---

**Arytmetyka modularna**

Definicja (1.0)
*Jeżeli m,n są dodatnimi liczbami całkowitymi, to m mod n jest resztą z dzielenia m przez n.*

Przykład.
- 25 mod 4 = 1, 25 mod 5 = 0, 27 mod 5 = 2.

Definicja (2.0)
*Jeżeli m jest liczbą całkowitą, a n dodatnią liczbą całkowitą, to m mod n jest najmniejszą nieujemną liczbą całkowitą r, taką że dla liczby całkowitej q, spełniona jest zależność...*

Tw. (Euklidesa)
*Jeżeli n będzie dodatnią liczbą całkowitą, to dla każfej nieujemnej liczby całkowitej m istnieją jednoznacznie wyznaczone liczby całkowite q i r takie, że m = n * q + r, oraz 0 <= r < n.*

Lemat (2.2)
*i mod n = (i + kn) mod n, dla każdej liczby całkowitej k.*
/okresowa!/

Dowód
- Z tw. Euklidesa, i = nq + r.
- Z definicji mod, r = i mod n.
- i + kn = n(q+k) + r.
- Z tw. Euklidesa i definicji mod, r = (i+kn) mod n.
- Skoro r = i mod n i r = (i+kn) mod n, to i mod n...

--RSA??--

Mod ogranicza rozmiar liczb z którymi pracujemy

prawo łączności

*Kryptologia - dziedzina wiedzy..*
Kryptologia dzieli się na:
- kryptografię
- kryptoanalizę

Szyfr Cezara

