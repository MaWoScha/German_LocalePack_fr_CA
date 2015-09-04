# Französisches Sprachpaket für Magento (CE)
(Magento Community Modules - French (Canada) Language Pack)<br />
(Módulos de Magento Community - Paquete de idioma francés)

Ce paquet de langue est géré par MaWoScha.<br />
This language package is managed by MaWoScha.<br />
Dieses Sprachpaket wird von MaWoScha verwaltet.

* See also: [Internationalization – Magento in several languages](http://blog.siempro.co/?p=105&lang=en)
* Siehe auch: [Internationalisierung – Magento in mehreren Sprachen](http://blog.siempro.co/?p=105&lang=de)
* Véase también: [Internacionalización – Magento en varios idiomas](http://blog.siempro.co/?p=105&lang=es)


# Instructions d'installation / Installation instructions / Installationshinweise

Vous devez installer les éléments suivants / You should install the following / Sie sollten Folgendes installieren:

*  [German LocaleFallback](https://github.com/MaWoScha/German_LocaleFallback)
*  [German LocalePack fr_CA](https://github.com/MaWoScha/German_LocalePack_fr_CA) (Preferred language / Langue préférée)
*  [German LocalePack fr_FR](https://github.com/MaWoScha/German_LocalePack_fr_FR) (Fallback language / Langue secondaire)
*  [German LocalePack en_US](https://github.com/MaWoScha/German_LocalePack_en_US) (Contains ONLY e-mail templates, NO csv files are included)

Logout from the backend once, if not already done. Then in the configuration under "Locale Options" set the "locale" as "fr_CA". The extension [German LocaleFallback](https://github.com/MaWoScha/German_LocaleFallback) now allows you, in addition set "Fallback language" as "fr_FR". Next, enable the static blocks "eMail Template Say Hello fr", "eMail Template Contact fr" and "eMail Template Say Bye fr" in the CMS-Manager and set them up according to your needs. The extension [German LocalePack en_US](https://github.com/MaWoScha/German_LocalePack_en_US) provides you with this enhanced ability to configure the e-mail templates for the English language. If you are using the English language, you also enable the static blocks "eMail Template Say Hello en", "eMail Template Contact en" and "eMail Template Say Bye en".

Melden Sie sich zunächst einmal aus dem Backend ab, falls nicht schon geschehen. Danach stellen Sie in der Konfiguration unter "Optionen für Lokalisierungen" für die "Sprachumgebung" "fr_CA" ein. Die Erweiterung [German LocaleFallback](https://github.com/MaWoScha/German_LocaleFallback) erlaubt Ihnen nun, zusätzlich als "Ausweichsprache" "fr_FR" festzulegen. Aktivieren Sie als nächstes in der CMS-Verwaltung die statischen Blöcke "eMail Template Say Hello fr", "eMail Template Contact fr" und "eMail Template Say Bye fr" und richten diese nach Ihren Bedürfnissen ein. Die Erweiterung [German LocalePack en_US](https://github.com/MaWoScha/German_LocalePack_en_US) stellt Ihnen diese verbesserte Konfiguriermöglichkeit auch für die englische Sprache bereit. Wenn Sie auch die englische Sprache verwenden, aktivieren Sie ebenfalls die statischen Blöcke "eMail Template Say Hello en", "eMail Template Contact en" und "eMail Template Say Bye en".

Déconnexion du backend fois, si pas déjà fait. Ensuite, dans la configuration sous «Options locale" définir la "locale" comme "fr_CA". L'extension [German LocaleFallback](https://github.com/MaWoScha/German_LocaleFallback) vous permet désormais, en plus de régler "la langue de repli" comme "fr_FR". Ensuite, activez les blocs statiques "eMail Template Say Hello fr", "eMail Template Contact fr" et "eMail Template Say Bye fr" dans le CMS-Manager et les configurer selon vos besoins. L'extension [German LocalePack en_US](https://github.com/MaWoScha/German_LocalePack_en_US) vous fournit cette capacité accrue pour configurer les modèles de courrier électronique pour la langue anglaise. Si vous utilisez la langue anglaise, vous activez également les blocs statiques "eMail Template Say Hello en", "eMail Template Contact en" et "eMail Template Say Bye en".


# Utilisez le dépôt Git / Use of Git repository / Git-Verwaltung

Dieses Git-Repository kann genutzt werden für:

* Reine Informationszwecke
* Entwicklung aktueller Versionen
* Behebung von Fehlern in bereits veröffentlichten Versionen
* Alternative Downloads (unabhängig von den offiziellen Quellen)
* Eigene Sprachversion basierend auf fr_FR
* Melden von Fehlern und PullRequests
* Aktives Mitwirken am Sprachpaket

## Rapporter des bugs / Reporting bugs / Melden von Fehlern

Des erreurs peuvent être signalés sur GitHub / Errors may be reported on GitHub / Fehler können auf GitHub gemeldet werden
<a href="https://github.com/MaWoScha/German_LocalePack_fr_CA/issues">https://github.com/MaWoScha/German_LocalePack_fr_CA/issues</a>

Wir freuen uns, wenn dieses Repository aktiv dazu genutzt, wird Fehler zu melden (Issue) und zu beheben (PullRequest im _preview_-Branch).

Oben dann einfach auf "Issues" klicken -> "New Issue", um ein Anliegen zu übermitteln. Bestehende Anliegen hingegen können auch ohne GitHub-Account eingesehen werden, inklusive deren Bearbeitungsstand.

_Beachten Sie dazu bitte:_ Wenn hier in den Versionen Veränderungen eingepflegt werden, dann entsprechen diese nicht mehr dem Stand des Sprachpakets, welches Sie über Magento Connect installieren können. Es ist leider nicht möglich dort veröffentlichte Releases nachträglich zu bearbeiten. :-)

_Hinweis:_ PullRequests sind bitte immer im Preview-Branch zu senden.

## Aktives Mitwirken am Sprachpaket

Lust am Sprachpaket mitzuwirken und einen (zumindest kostenlosen) Github- und/oder Crowdin.net-Account? Dann einfach MaWoScha kontaktieren und wir stimmen eine eventuelle Zusammenarbeit ab.

Viel Spaß mit dem frankokanadisch Magento Sprachpaket!

MaWoScha


# Conseils / Hints / Hinweise / Avisos

Ceci est un travail dérivé de [German LocalePack de_CH](https://github.com/MaWoScha/German_LocalePack_de_CH),<br />
refactured et internationalisé par MaWoScha.

Cette extension est testé avec Magento 1.6.2, 1.7.0, 1.8.1, 1.9.0 et 1.9.1. <br />
Le pack de langue est adapté pour Magento 1.6.x jusqu'à 1.9.1.x

Tant que les fichiers de langue de cette extension sont vides, ce pack de langue ne fait rien (encore). <br />
Mais dès que vous entrez dans une partie spécifique, dans la partie française de mots et expressions courantes au Canada, vous pourrez bénéficier de toutes les fonctionnalités de "langue de repli".


This is a derived work of [German LocalePack de_CH](https://github.com/MaWoScha/German_LocalePack_de_CH),<br />
refactured and internationalized from MaWoScha.

This extension is tested with Magento 1.6.2, 1.7.0, 1.8.1, 1.9.0 and 1.9.1. <br />
The language pack is suitable for Magento 1.6.x until 1.9.2.x

As long as the language files of this extension are empty, this language pack does nothing (yet).
But as soon as you enter some specific, in French-speaking part of Canada common words and phrases, you will benefit from the functionality of "Fallback language".


Dies ist eine abgeleitete Arbeit von [German LocalePack de_CH](https://github.com/MaWoScha/German_LocalePack_de_CH),<br />
überarbeitet und internationalisiert von MaWoScha.

Diese Erweiterung ist mit Magento 1.6.2, 1.7.0, 1.8.1, 1.9.0 und 1.9.1 getestet. <br />
Das Sprachpaket ist für Magento 1.6.x bis 1.9.2.x

Solange die Sprachdateien dieser Erweiterung leer sind, tut dieses Sprachpaket (noch) nichts.
Sobald Sie aber einige spezielle, im französischsprachigen Teil Kanadas gebräuchliche Wörter und Phrasen eintragen, profitieren Sie von der Funktionalität der "Ausweichsprache".


Se trata de una obra derivada de [German LocalePack fr_FR](https://github.com/MaWoScha/German_LocalePack_fr_FR),<br />
revisado e internacionalizado de MaWoScha.

Esta extensión se prueba con Magento 1.6.2, 1.7.0, 1.8.1, 1.9.0 y 1.9.1. <br />
El paquete de idioma es adecuado para Magento 1.6.x hasta 1.9.2.x

Mientras los archivos de idioma de esta extensión están vacías, este paquete de idioma (todavía) no hace nada.
Pero tan pronto como entras en alguna específica, común en las palabras y frases de en la parte francófona de Canadá, que se beneficiarán de la funcionalidad de "Idioma segunda opción".
