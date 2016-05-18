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

* Standards: BITV / WCAG
  * NVDA, JAWS, VoiceOver, ORCA all fail
* "Visuell" vorlesen
  * MathSpeak
* Problem: Qualität der Quelle
  * Mathematik schreiben ist schwer genug, extra arbeit "nur" für Barrierefreiheit fällt den meisten schwer
  * Aber auch: kaum Möglichkeiten, weder semantisch zu schreiben, noch motivieren zum Altttext
* Semantische Analyse


## Neue Ansätze

* Bei Erstellung ansetzen
  * Pearson
* Das beste draus machen
  * MathJax
    * l10n/i18n


## Recap

* Mathematik ist schwer, aber nicht unloesbar
* PDF ist keine Lösung, das Web ist
* "Unsere Doezenten wollen nicht" => Nicht nur web. Mobil, apps etc
* Don't throw anything away (LaTeX etc)
 * löst viele Probleme
   * speech
   * copy&paste
   * future options
* Think beyond.
  * What about diagrams, ad-hoc drawings in class, lecture notes
  * show of hands: Word, LaTeX, Something different?
