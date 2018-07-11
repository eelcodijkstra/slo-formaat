****************
Formaat-voorstel
****************

Sphinx
======

Wij stellen voor om als publicatieformaat Sphinx (https://sphinx-doc.org) te gebruiken:
het systeem dat gebruikt wordt voor de documentatie van Python en allerlei Python-gerelateerde projecten.

Dit formaat heeft de volgende voordelen/eigenschappen:

* relatief eenvoudig uit te breiden

    * met componenten van elders (o.a. Runestone);
    * met eigen componenten (o.a. voor feedback).

* tekst-gebaseerd

    * goed te combineren met versiebeheer (git, GitHub),
    * daardoor geschikt voor het samenwerken aan een volgende versie,
    * en voor het maken van afgeleide versies/arrangementen;
    * **nadeel** voor beginnende gebruikers: geen WYSIWYG

* resultaat is een *statische website*

    * eenvoudig/goedkoop te hosten (evt. GitHub, )

* gebaseerd op reStructuredText: iets complexer dan Markdown, maar met meer (uitbreidings)mogelijkheden.

* naast online/website ook andere uitvoermogelijkheden:

    * PDF/papier (via LaTeX)
    * ePub (HTML)

* Sphinx wordt veel gebruikt en heeft een grote ondersteunende community.


Voorbeelden
===========

Enkele websites die Sphinx gebruiken:

* https://readthedocs.org

    * http://docs.godotengine.org/en/3.0/
    * http://docs.python-requests.org/en/master/
    * https://bbcmicrobitmicropython.readthedocs.io/en/latest/

* https://sphinx-doc.org

Runestone
---------

Runestone Academy biedt een platform voor het publiceren van interactief lesmateriaal,
vooral voor informatica- en programmeeronderwijs.

* https://runestone.academy/runestone/default/courses

    * N.B.: zie het Book Links menu

* https://runestone.academy/runestone/static/thinkcspy/index.html
* https://runestone.academy/runestone/static/pythonds/index.html
* https://runestone.academy/runestone/static/StudentCSP/index.html

Runestone Academy heeft een verzameling Sphinx-componenten gedefinieerd voor programmeeronderwijs en interactief onderwijsmateriaal.

* https://runestone.academy/runestone/static/overview/overview.html
* https://github.com/RunestoneInteractive/RunestoneComponents

Jupyter Notebook
================

Jupyter Notebook (https://jupyter.org) biedt interactieve notebooks voor allerlei programmeertalen,
o.a. Python, R, shell, JavaScript.
Deze notebooks worden veel gebruikt door onderzoekers in de wereld van Data Science en Computational Science.
Met deze notebooks kan de afstand tussen onderzoek (programmeren/rekenen) en publicatie aanmerkelijk ingekort worden.
Ook voor (informatica)onderwijs hebben deze notebooks grote voordelen,
onder andere omdat opdrachten voor leerlingen op elk gewenst niveau van scaffolding voorzien kunnen worden.

  Het team voor het thema Programmeerparadigma's/Functioneel Programmeren werkt momenteel met Jupyter Notebooks,
  voor de programmeertaal Elm.

Jupyter Notebooks zijn te gebruiken in combinatie met Sphinx:

* zie: https://nbsphinx.readthedocs.io/en/0.3.3/

Het lijkt ons belangrijk om de ontwikkelingen rond Jupyter Notebooks te volgen,
en waar relevant met dit hulpmiddel te experimenteren.

GitHub
======

.. todo::

   Gebruik van git/GitHub voor versiebeheer;
   en voor projectdoeleinden zoals feedback/issues, planning, documentatie, enz.

.. todo::

   Licentie-wensen en -consequenties bespreken (bijv. CC-BY-SA, als in Wikipedia)

.. todo::

   Bestudeerde alternatieven bespreken, o.a. Wikiwijs.
   Dit voorstel formuleren als (aanzet tot) "Wikiwijs 2.0".
   HTML als alternatief?
