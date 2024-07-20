# PICO Breadcrumb Twig Modul #

Das Breadcrumb-Modul ist vollständig in `Twig` geschrieben und sollte in ein beliebiges Template eingebunden werden, in dem am oberen Rand (ideal) eine Brotkrumen-Navigation erscheinen soll. Das Modul wird mit Hilfe der Bootstrap-Classes gestaltet, jedes andere CSS ist natürlich auch leicht nutzbar

## Installation ##

Das Twig-Modul kann in das Template-Verzeichnis kopiert werden und mittels:

    {% include 'modules/breadcrumb.twig' %}

eingebunden werden (ich empfehle zusätzlich den Unterordner `modules`). Sofern Sie keinen weiteren Unterordner verwenden, reicht es mit:

    {% include 'breadcrumb.twig' %}

einzuhängen.

## CSS ##

Das Twig-Modul ist für das CSS-Framework `Bootstrap` angepasst, kann aber auch mit jedem anderen CSS-Framework verwendet werden. Im Falle von Bootstrap, werden kleine einzelne klickbare Buttons in grau oben unter dem Titel eingeblendet.

>Hinweis: Kommentare in Templates sollten im Twig-Style erfolgen, um die interne Struktur der Webseite nicht öffentlich zu machen.

## Webseite ##

- [Beitrag auf CMSWorkbench](https://cmsworkbench.de/pico/twig/breadcrumb-navigation-3)
- [CMSWorkbench.de](https://cmsworkbench.de)
- [Oliver-Lohse.de](http://oliver-lohse.de)
