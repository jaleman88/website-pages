---
title: Hilfe
layout: default-de
---

# Hilfe

- [Allgemein](#allgemein)
- [Nachrichten an mehrere Personen](#broadcast)
- [Gruppen](#gruppen)
- [Speicherung der Nachrichten](#speicherung)
- [Mehrere Geräte verwenden](#multiclient)



# Allgemein

## Wie funktioniert Delta Chat?

- Zunächst sieht Delta Chat wie jeder andere Messenger aus und funktioniert auch so und bietet dieselben Funktionen.
  Unter der Haube verwendet das Programm aber keinen gekapselten Server, sondern das offene IMAP-Protokoll - wie es auch für E-Mail verwendet wird -
  allerdings haben wir hier einige Zusatzfunktionen, wie z.B. Gruppen, nachgerüstet.

## Welche Vorteile hat Delta Chat gegenüber anderen Messengern?

- Unabhängigkeit von irgendwelchen Firmen. _Sie_ besitzen Ihre Daten
- Ihre Daten landen nicht auf zentralen Servern. So schützt Delta Chat im Gegensatz zu den meisten anderern Messengern, sogar die Metadaten, d.h. wer mit wem kommuniziert
- Sie geben die Inhalte Ihres Adressbuches nicht weiter - was auch illegal ist, wenn Sie sich nicht die Zustimmung aller Ihrer Freunde, Bekannten und Geschäftspartner eingeholt haben.
- Schnell und Zuverlässig, auch für den professionellen Einsatz
- Riesige Nutzerbasis - Sie können auch Leute erreichen, die Delta Chat _nicht_ verwenden!
- Kompatibel, überprüfbar, Open Source
- Elegante und einfach zu bedienende Benutzeroberfläche
- Verteiltes, föderales System
- Kein Spam
- [...](features)

## An wen kann ich schreiben?

- Mit Delta Chat können Sie an Benutzer, die Delta Chat verwenden, schreiben - 
  und an Benutzer, die irgend einen anderen E-Mail-Client verwenden!
  Dies ist einer der größten Unterschiede zu anderen Messengern:
  Ihre Kontakte müssen _nicht_ denselben Messenger wie Sie verwenden.

## Was, wenn der Empfänger kein Delta Chat verwendet?

- Der Empfänger erhält dann eine normale E-Mail, auf die er auch antworten kann.
  Seine Antwort erscheint dann wie gewohnt im Delta Chat Messenger

## Was ist mit Spam?

- Sie werden in Delta Chat keine unerwünschten Nachrichten sehen, _Sie_ entscheiden mit wem Sie kommunizieren wollen.

## Unterstützt Delta Chat Bilder, Videos und Dateianhänge?

- Ja.

## Können mit Delta Chat Sprachnachrichten verschickt werden?

- Ja.

## Unterstützt Delta Chat HTML-E-Mails?

- Ja.

## Gibt es eine iOS, Mac, Windows, Linux oder XYZ-Version?

- Gibt es Delta Chat noch nicht für Ihr Wunschsystem? Delta Chat ist Open Source - [unterstützen Sie uns bei unserer Arbeit](support)!





# Nachrichten an mehrere Personen {#broadcast}

## Wie kann ich eine Nachricht an mehrere Personen schicken?

- Entweder über [Gruppen](#gruppen) oder Sie senden die Nachricht zunächst normal an eine Person, drücken die Nachricht dann lang und wählen "Weiterleiten". 





# Gruppen

## Wie kann ich eine neue Gruppe erstellen?

- Öffnen Sie das **Hauptmenü** und wählen Sie dort **Neue Gruppe** (Alternativ drücken Sie auf "+" und wählen dann dort oben rechts _Neue Gruppe_ aus).
- Wählen Sie dann alle **Gruppenmitglieder** aus und klicken auf den Haken oben rechts; auf der nächsten Seite können Sie noch einen **Gruppennamen** vergeben.
- Sobald Sie eine **erste Nachricht** in der Gruppe schreiben, werden alle Gruppenmitglieder über die neue Gruppe informiert und können auch dort schreiben (solange Sie in der neuen Gruppe keine Nachricht geschrieben haben, ist sie für die anderen Mitglieder noch nicht sichtbar).


## Wer kann Mitglieder hinzufügen oder löschen?

- Jedes Gruppenmitglied hat **dieselben Rechte** wie jedes andere. Jeder kann daher jeden löschen oder weitere Mitglieder hinzufügen.
- Um die Mitglieder zu verwalten einfach in der Gruppe auf den Gruppennamen klicken.

## Ich habe mich selbst versehentlich gelöscht.

- Da Sie selbst nun kein Gruppenmitglied mehr sind, können Sie sich auch nicht selbst wieder hinzufügen.  Bitten Sie ein anderes Gruppenmitglied in einem normalen Chat, Sie wieder hinzuzufügen.

## Ich möchte keine Nachrichten einer Gruppe mehr empfangen.

- **Löschen** Sie entweder sich selbst als Gruppenmitglied oder den Chat selbst. Möchten Sie später wieder an der Gruppe teilnehmen, müssen Sie von einem noch aktiven Mitglied hinzugefügt werden.
- Alternativ können Sie eine Gruppe auch nur **Stummschalten** - Sie erhalten dann alle Nachrichten und können bei Bedarf auch noch schreiben; es erfolgt dann aber keine Benachrichtigung mehr bei neuen Nachrichten.





# Speicherung der Nachrichten {#speicherung}

## Benötige ich für Delta Chat ein eigenes Konto?

- Nein, verwenden Sie einfach Ihr bestehendes E-Mail-Konto zum Messaging mit Delta Chat.

## Kann ich Delta Chat und ein anderes E-Mail-Programm gleichzeitig verwenden?

- Ja, kein Problem. Mit einem anderen E-Mail-Programm versandte Nachrichten erscheinen nach etwas Verzögerung sogar in Delta Chat.

## Gibt es ein Backup der verschickten und empfangenen Nachrichten?

- Ja. Und zwar ganz normal im verwendeten E-Mail-Konto.  Mit Delta Chat versendete Nachrichten landen dabei im Ordner "Chats" (Ausnahme: Googlemail, hier bitte bei Bedarf eine Regel im Webinterface anlegen).

## Kann ich nach einer Neuinstallation Nachrichten wiederherstellen?

- Aktuell noch nicht, dies ist aber für eine der folgenden Versionen geplant. Das Backup gibt es aber bereits jetzt.





# Mehrere Geräte verwenden {#multiclient}

## Kann ich Delta Chat auf mehreren Geräten gleichzeitig verwenden?

- Ja.  Wenn Sie **verschiedene Konten** verwenden, gibt es dabei gar nichts zu beachten. 
- Wenn Sie auf **dasselbe Konto** von verschiedenen Geräten zugreifen möchten (Multi-Client), tragen Sie einfach auf allen Geräten dieselben Kontoeinstellungen ein. _Eingehende_ Nachrichten werden dabei auf allen Geräten sofort angezeigt, _ausgehende_ Nachrichten werden über Gerätegrenzen hinweg aktuell alle ca. 30 Minuten synchronisiert. Wenn wir genügend [Unterstützung](support) bekommen, ist geplant, dies noch weiter zu verbessern.

## Kann ich auf einem Gerät Delta Chat verwenden und auf dem nächsten einen anderen Client?

- Ja. Sie können sogar auf demselben Gerät verschiedene Clients verwenden.

## Funktioniert die kommende Ende-zu-Ende-Verschlüsselung auch mit Multi-Client?

- Ja. Es wird eine Möglichkeit geben, die privaten Schlüssel von Gerät zu Gerät zu kopieren.  Für die Standardanwendung von Delta Chat - _ein_ Endgerät pro Konto, ähnlich wie bei den meisten anderen Messengern - ist dies nicht notwendig.



