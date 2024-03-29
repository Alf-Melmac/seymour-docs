---
description: Kopiert eine Nachricht aus dem aktuellen Kanal in einen anderen Kanal.
---

# Kopieren

<figure><img src="../.gitbook/assets/Seymour-Copy.gif" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Berechtigungen**

Der Bot muss im Ausgangskanal über die Berechtigung **Kanal anzeigen** verfügen und zusätzlich im Zielkanal **Nachrichten senden**, damit eine Nachricht kopiert werden kann.
{% endhint %}

## Befehl

/kopieren `nachrichten-id` `neuer-kanal`

## Aktion

Kopiert die Nachricht mit der übergebenen id inklusive aller Anhänge in den angegebenen Kanal.

## Antwort

{% hint style="success" %}
Kopiert nach \<Kanal>
{% endhint %}

{% hint style="danger" %}
* Keine gültige Nachrichten-ID angegeben.
* Der Kanal \<Kanal> kann nicht erreicht werden.
* Fehlende Schreibrechte im Zielkanal.
* Nachricht nicht gefunden.
{% endhint %}
