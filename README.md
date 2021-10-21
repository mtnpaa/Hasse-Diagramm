# Hasse-Diagramm
https://user.phil.hhu.de/~petersen/WiSe1213_mathGrundl/Petersen_math_grundl_handout.pdf
Zeichnen Sie jeweils das Hasse-Diagramm dieser Teilbarkeitsrelation

 - für (N,+,0), eingeschränkt auf {0,1,…,4}

 - für (N,⋅,1), eingeschränkt auf {0,1,…,10}

 - für (2{p,q,r},∪,∅)

 - für ({a,b}∗,⋅,ϵ) auf {a,b}≤2

Geben Sie eine Halbordnung auf {0,1,2}2 an, deren Hasse-Diagramm ein auf der Spitze stehendes Quadratnetz ist.

Diese Halbordnung soll intensional angegeben werden (durch eine Formel), nicht extensional (durch Aufzählen aller Elemente).



-------------------------------------------------------------------------------------------------

Ein Hasse-Diagramm ist in der Mathematik eine graphische Darstellung für *endliche halbgeordnete Mengen*.

Was sind  endliche halbgeordnete Mengen?
- *endlich --> ist beschränkt*
 - N= {1,2,3,...} ist die Menge der natürlichen Zahlen, diese Menge ist unenedlich {1,2,4,...}
 - A = {0,1,2,3 ...5} -> diese Menge ist endlich, weil sie eingeschränkt auf 0 und 5 ist
 - Warum ist in der Aufgabenstellung im Universum N der natürlichen Zahlen und dieser eingeschränkt  bei 0?
- weil man die 0 dazu nehemen kann, dann wäre es das neutrale Element
- Ordnung "kleiner gleich", "größer gleich" --> Ordnungsrelationen
- **M ist eine Menge mit Relationen ~ ** oder anders gesagt: eine Menge mit einer Relation
- **Relationen haben Eigenschaften**
  - reflexiv --> =, <=, >=, + Teilmengenbeziehungn C=
  - irreflexiv --> <, >, ungleich, echte Teilmengenbeziehungen C
  - symetrisch
  - asymetrisch
  - transitiv -->  x < y {\displaystyle x<y} x<y und y < z {\displaystyle y<z} y<z folgt x < z {\displaystyle x<z} x<z.
- **Dann ist ~ eine Halbordnung, wenn gilt Reflexivität, Antisymetrie und Transitivität**
- Halbordnung (partialordnung) der Unterschied zu Totalen Ordnung ist. Die Totalität ist abgeschwächt. Jedes Element steht zu sich selbst in Relation (Reflexivität)
  - Reflexivität (Für alle Elemente einer Menge gilt, dass diese Elemente zu sich selbst in Beziehung stehen x~x)
  - Antisymeterie
  - Transitivität (Wenn ein Element(x) in Relation zu einem Anderen(y) steht und dieses Andere Element in Relation zu einem Weitern Element steht(z) x~y , y~z --> x~z

________________________________________________________________________________________
- Menge "eine Zusammenfassung von bestimmten wohlunterschiedenen Objekten/Elementen, zu einem Ganzen" (frei nach G.Cantor)
- Mengen werden  durch Auflistung ihrer Elemente in geschweiften Klammern dargestellt.
-  --> Die Menge A = {2,3,5,7}
-  Reihenfolge der Elemente ist egal, auch mehrfachnennung ist erlaubt
-   Unendlichen Zahlenmengen können so formal dargestellt werden A = { 2,3,5,7,...}
-   Elemente werden für ihre Menge mit kleinen Buchstaben beschrieben
-   **a ist  Element von Menge A**

- ein Objekt a ist ein Element einer Menge A  --> 
- ![ein Obj a ist Element einer Menge A](https://latex.codecogs.com/gif.latex?a%20%5Cin%20A)


- gebräuchliche Darstellungsform beruht auf dem Abstraktionsprinzip, nach dem man Mengen durch  wohlbestimmten Eigenschaften definiert. (Cantorschen Definition)
- Dafür werden Prädikate P für einen Individuenbereich festgelegt x --> P(x)

*"Die Menge hat Eigenschaften, welche mit P beschrieben werden können."*

Dann wird mit {x | P(x)} oder (wenn der Bereich B explizit genannt werden soll) mit
{x ∈ B | P(x)} die Menge bezeichnet, die sich aus allen Individuen aus dem Bereich
zusammensetzt, für die P(x) wahr ist.

*am besten in Kreisen denken*
Eine Menge A ist **Teilmenge(Untermenge)** einer Menge B, wird so ausgedrückt
![A ist Teilmenge von B](https://latex.codecogs.com/gif.latex?A%5Csubseteq%20B)

- Wenn A Teilmenge von B ist und B ist Teilmenge von A, dann ist A=B

- Zwei Mengen sind **disjunkt**, wenn sie keine gemeinsamen Elemente haben

- Die **Vereinigung** von A und B ![AUB](https://latex.codecogs.com/gif.latex?A%5Ccup%20B) besteht aus allen Elementen von A und B

- **Durchschnitt** ![AOB](https://latex.codecogs.com/gif.latex?A%5Ccap%20B), ist die Menge wo alle Elemente in A un bV sind

- **Differenz** ![A\B](https://latex.codecogs.com/gif.latex?A%20%5Csetminus%20B), Ergbenis ist eine Menge aus Elementen, die aus A besteht, aber nicht aus Elementen die ebenfalls in B enthalten sind
z.B A = {3,4,5} und B={4,5} dann A\B = {3}

Eine Menge die kein Element enthält nennt man leere Menge A = {}
Der betrachtet Individuenbereich wird festgelgt, diesen Bereich nennt man Universum.
Ein Universum kann natürlich auch Teilmengen haben.

Identitäten
 - Kommutativtät
 - Assoziativtät
 - Distributivität
 - Idempotenz
 - Dominanz
 - Identität
 - Absorbtion
 - De Morgan'sche Regel
 - Komplementierung


http://www.inf.fu-berlin.de/lehre/WS08/mafi1/skript2.pdf

---------------------------------------------------------------------------------------------------------------------------------------

**Monoid**
- ist eine Halbgruppe mit einem neutralen Element

1. Untersuchung auf Abgeschlossenheit
2. Untersuchung auf Assozität
3. Untersuchung nach ein neutrales Element
4. Untersuchung nach Inversen
5. Untersuchung nach Kommuntativität

- wenn gilt 1, 2, 3, 4, 5, dann Abelsche Gruppe
-1, 2, 3, 4 --> Gruppe
- 1, 2, 3 --> Monoid
- 1,2 --> Halbgruppe



(N0, +)
(sprich: wenn man die Natürlichen Zahlen nimmt mit der 0 in  der Verknüpfung mit der Addition)
dann untersuchen wir diese
nach 
- Abgeschlossenheit (verknüpfung von a o b --> a o b --> 2+o=6) o ist bei uns die Addition , 6 ist Element der natürlichen Zahlen -->es gilt die abgeschlossenheit 
- Assozität ??
- neutrales Element = 0 denn alles in der Addition was ich plus 0 nehme ändert nichts.
- - ein Inverses gibt es nicht ?? (weil Natürliche Zahlen)




Ja. (N_0, +, 0) ist ein Monoid und kommutativ. Dafür gibt es aber keinen besonderen Namen, außer vielleicht abelscher Monoid oder sowas.



**Algebraische Strukturen/Elementares  Rechnen**

- Mengen,            Rechenoperationen                Gruppe/Ring/Körper
- Z={0,-1,1,-2,2..}          +                     Gruppe=  Ist eine Menge und eine Rechenoperation in Verknüpfung  G (Z, 0)                     

................


Gruppen sind Mengen mit Verknüpfungen


**Gruppenaxiome**
o := Platzhalter für Verknüpfungen
G := Menge von der Gruppe

- Asoziativität
- Neutrales Element
- Inverses Element



**Legende der mathematischen Symbole**

- ![forall](https://latex.codecogs.com/gif.latex?%5Cforall) -- für alle
- 






