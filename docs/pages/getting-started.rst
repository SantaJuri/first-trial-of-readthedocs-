=================================================
Erstellen einer Doku für readTheDocks mit Sphinx:
=================================================

Lokal:
======

(Python Environment)
--------------------

- im Git-Repository:
    
* install sphinx:

.. code-block::

    pip install sphinx

.. code-block::

    sphinx-quickstart docs
    
* das "docs" erstellt automatisch einen Ordner "docs" in dem die Doku-Files und Make-Files (make.bat) liegen werden

        + ==> standards verwenden & Projektnamen (+ aktuelle Projektversion) eingeben (… Min. 33:27 (kurz) oder 17:00 (lang - mit erklärung) .. )

* Um nun aus den .txt oder .rst (restructuredtext) Dateien die fertige Doku-Seite (i.d.R. html) zu machen verwende:

.. code-block::

    cd docs
    make html

        + ==> das index.html file ist im /docs/build/html ordner verfügbar 
	  und kann z.B. mit Firefox geöffnet werden

* Nun im ReadTheDocs-Admin Center das Repo hinzufügen und die Branches verwalten (wenn noch nicht geschehen - WebHook im GitLab einrichten)

Diese Seite als "raw code":
===========================

.. code-block::

	=================================================
	Erstellen einer Doku für readTheDocks mit Sphinx:
	=================================================

	(Links to) StructuredText:
	============================
	* https://github.com/DevDungeon/reStructuredText-Documentation-Reference

	Lokal:
	======

	(Python Environment)
	--------------------

	- im Git-Repository:
		* install sphinx:

	.. code-block::

		pip install sphinx

	* "docs" erstellt automatisch einen Ordner "docs" in dem die Doku-Files und Make-Files (make.bat) liegen werden

	.. code-block::

		sphinx-quickstart docs

	* ==>
		    + standards verwenden & Projektnamen (+ aktuelle Projektversion) eingeben (… Min. 33:27 (kurz) oder 17:00 (lang - mit erklärung) .. )

	* Um aus den .txt oder .rst (restructuredtext) filies die fertige Doku-Seite (i.d.R. html) zu machen:

	.. code-block::

		cd docs
		make html

	* make html wird auch automatisch von readthedocks ausgeführt - aber so können wir das Ergebnis lokal anschauen..

	* ==>
		    + das index.html file ist im /docs/build/html     ordner verfügbar und kann z.B. mit Firefox geöffnet werden
