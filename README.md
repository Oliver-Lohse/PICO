# PICO Breadcrumb Twig Modul #

Das Breadcrumb-Modul für *Pico CMS*, ist vollständig in der Templatesprache `Twig` geschrieben und sollte in ein beliebiges Template eingebunden werden, in dem am oberen Rand (ideal) eine Brotkrumen-Navigation erscheinen soll. Das Modul wird mit Hilfe des Bootstrap-CSS gestaltet, jedes andere CSS ist natürlich auch leicht nutzbar und kann einfach eingefügt werden.

## Installation ##

Das Twig-Modul kann entweder direkt in das Template-Verzeichnis kopiert werden und mittels:

    {% include 'breadcrumb.twig' %}

regulär eingebunden werden. Ich empfehle jedoch innerhalb des Templates solche einzelnen Module in einem eigenen Unterordner `modules` zu sammeln:

    {% include 'modules/breadcrumb.twig' %}

und von dort in die Haupttemplates einzubinden, das schafft etwas mehr Ordnung und Übersicht.

## CSS ##

Das Twig-Modul ist für das CSS-Framework `Bootstrap` angepasst, kann aber auch mit jedem anderen CSS-Framework verwendet werden. Im Falle von Bootstrap, werden kleine einzelne klickbare Buttons in grau oben unter dem Titel eingeblendet.

>Hinweis: Kommentare in Templates sollten im Twig-Style erfolgen, um die interne Struktur der Webseite nicht öffentlich zu machen.

## Webseite ##

- [Beitrag auf CMSWorkbench](https://cmsworkbench.de/pico/twig/breadcrumb-navigation-3)
- [CMSWorkbench.de](https://cmsworkbench.de)
- [Oliver-Lohse.de](http://oliver-lohse.de)
