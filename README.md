1.Creați un proiect elementar. Urmăriți exemplul furnizat cu titlu de
demonstrație - OpenTK_console_sample01 și
OpenTK_console_sample02. Atenție la setarea viewport-ului.
Modificați valoarea constantei „MatrixMode.Projection”. Ce
observați?

R : Schimbarea modului matricei de proiecție ne permite să ajustăm perspectivele și să controlăm cum sunt afișate obiectele pe ecran.

2. Ce este un viewport?
   R: Un viewport reprezintă fereastra sau regiunea specifică a unei suprafețe de desenare cum ar fi ecranul.

3.Ce reprezintă conceptul de frames per seconds din punctul de
vedere al bibliotecii OpenGL?
R: Conceptul de frames per seconds se referă la numărul de cadre sau imagini pe secundă care sunt generate și afișate pe ecran.

4.Când este rulată metoda OnUpdateFrame()?
R: OnUpdateFrame() este apelată în fiecare cadru.

5.Ce este modul imediat de randare?
R: Modul imediat de randare reprezintă o abordare în OpenGL asociată cu funcționalitățile mai vechi ale bibliotecii. În acest mod, instrucțiunile de desenare sunt specificate direct în codul aplicației, fără a recurge la utilizarea de buffer-e sau alte structuri intermediare.

6.Care este ultima versiune de OpenGL care acceptă modul imediat?
R: OpenGL 3.0

7.Când este rulată metoda OnRenderFrame()?
R: Metoda OnRenderFrame() este apelată automat în fiecare cadru în cadrul buclei principale a aplicației grafice.

8.De ce este nevoie ca metoda OnResize() să fie executată cel puțino dată?
R: "Metoda OnResize() este esențială în cadrul aplicațiilor grafice care utilizează OpenGL, deoarece gestionează modificările de dimensiune ale ferestrei de vizualizare. În această metodă, se ajustează viewport-ul, se setează raportul de aspect și se actualizează matricea de proiecție pentru a asigura coerența și corectitudinea afișării grafice."

9.Ce reprezintă parametrii metodei CreatePerspectiveFieldOfView() ?
R: Această metodă este folosită pentru a construi o matrice de proiecție care modelează un con de vedere perspectivic în spațiul 3D.
