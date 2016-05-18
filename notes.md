# Barrierefreie Mathematik im Netz

Ein Vortrag zum World Accessibility Day 2016 an der Fernuniversität Hagen.

## Zur Person

DONE

## Zum Web als Medium

## Mathematik vs Formeln

* Mathmeatik vs MINT vs Formeln
* Ein tragendes Beispiel? Aus Wikipedia?

## Wie schreibt man Mathematik digital?

* Bild: Tastatur mit #fail
* wysiwyg editor (MS Word youtube video / WIRIS / Wikipedia)
  * cf to Photoshop
* Handwriting (Windows, MyScript)
* Code
  * ascii
  * TeX
  * computing (MathJS)

## Wie stellt man Mathematik visuell dar?

* Binaerbilder / Vektorgrafik
* PDF
  * glyphs on a canvas
* Web
  * MathML => failed
  * HTML/CSS, SVG, Canvas
  * computing (MathJS)

## Wie liest man Mathematik vor?

### Herausforderungen

* Mathematische Notation ist meist hoch komprimiert
  * man muss also dekomprimieren
    * e.g., $\frac{\mathscript{d}^2 x}{\mathscript{d}^3y}$, Euler-Lagrange gleichungen etc
  * killMath
* Mathematische Notation ist sehr visuell
  * 1. Isomorphiesatz
* Mathematische Notation ist extrem kontexabhängig
  * (a,b)
  * "Man betrachte den Kreis um (a,b) mit Radius r"
  * "Für $a, b \in H$, H  Hilbertraum, gilt  (a,b) = (b,a)."
  * $$\sigma_x \cdot \sigma_p \ge \frac{\hbar}{2}$$
    * "Die Streuung des Ortes x multipliziert mit der Streuung des Impuls p ist größer oder gleich Hälfte der reduzierten Plank'schen Konstante "

### Lösungsansätze

* "Visuell" vorlesen
  * MathSpeak
* Problem: Qualität der Quelle
  * Mathematik schreiben ist schwer genug, extra arbeit "nur" für Barrierefreiheit fällt den meisten schwer
  * Aber auch: kaum Möglichkeiten, weder semantisch zu schreiben, noch motivieren zum Altttext
* Semantische Analyse


## Lösungen

* BITV / WCAG
* NVDA, JAWS, VoiceOver, ORCA
* MathJax

## Ungeloeste Probleme

* Localizaiton
* Testen
* Resourcen


https://de.wikipedia.org/wiki/Heisenbergsche_Unsch%C3%A4rferelation
https://de.wikibooks.org/wiki/Vektoranalysis:_Teil_I


## Take home messages

* Mathematik ist schwer, aber nicht unloesbar
* PDF ist keien Loesung
* "Unsere Doezenten wollen nicht web"
 *  Nicht nur web. Mobil, apps etc
* Don't throw anything away (LaTeX etc)
 * loest viele Probleme
   * speech
   * copy&paste
   * future options
* What about diagrams, ad-hoc drawings in class, lecture notes
  * show of hands: Word, LaTeX, Something different?


* Accessibility means
 * Not just blind!
   * dyslexia => sync highlighting
   * motor disabilities
   * high (or low!) contrast
 * voicing
 * re-use
   * copy&paste
 * search
 * machine-readability
