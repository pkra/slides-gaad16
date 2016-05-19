# Barrierefreie Mathematik im Netz

Ein Vortrag zum Global Accessibility Awareness Day 2016 an der Fernuniversität Hagen.

## Zur Person

## Zum Web als Medium

## Mathematik vs Formeln

* Mathmeatik vs MINT vs Formeln
* Ein tragendes Beispiel

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

* pre-web
  * glyphs on a canvas
* Binaerbilder / Vektorgrafik
* Web
  * MathML => failed
  * HTML/CSS, SVG, Canvas

## Wie stellt man barrierefrei dar?

### Fuer wen und was?

### standards and AT fail

* Standards: BITV / WCAG
  * NVDA, JAWS, VoiceOver, ORCA all fail

### Was ist so schwer daran?

* Formeln sind meist hoch komprimiert
  * man muss also dekomprimieren
    * e.g., $\frac{\mathscript{d}^2 x}{\mathscript{d}^3y}$, Euler-Lagrange gleichungen etc
  * killMath
* Formeln sind sehr visuell
  * 1. Isomorphiesatz
* Formeln sind extrem kontexabhängig
  * (a,b)
  * "Man betrachte den Kreis um (a,b) mit Radius r"
  * "Für $a, b \in H$, H  Hilbertraum, gilt  (a,b) = (b,a)."
  * $$\sigma_x \cdot \sigma_p \ge \frac{\hbar}{2}$$
    * "Die Streuung des Ortes x multipliziert mit der Streuung des Impuls p ist größer oder gleich Hälfte der reduzierten Plank'schen Konstante "

* Formeln sind schlecht geschrieben
  * fokussiert auf (print) layout
  * kaum tools
  * Problem: Qualität der Quelle
    * Mathematik schreiben ist schwer genug, extra arbeit "nur" für Barrierefreiheit fällt den meisten schwer
    * Aber auch: kaum Möglichkeiten, weder semantisch zu schreiben, noch motivieren zum Altttext

### Lösungsansätze

* "Visuell" vorlesen
  * MathSpeak
* Semantische Analyse


## Neue Ansätze

* Bei Erstellung ansetzen
  * Pearson
* Das beste draus machen
  * MathJax
    * l10n/i18n


## Recap

* Mathematik ist schwer, aber nicht unloesbar
* PDF ist keine Lösung, das Web ist immer besser.
  * "Unsere Doezenten wollen nicht" => Nicht nur web. Mobil, apps, ebooks etc
* Don't throw anything away (LaTeX etc)
 * löst viele Probleme
   * speech
   * copy&paste
   * future options
* Think beyond.
  * What about diagrams, ad-hoc drawings in class, lecture notes
  * show of hands: Word, LaTeX, Something different?
