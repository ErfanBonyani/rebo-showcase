# REBO — Shop-Anwendung und Verwaltungsdemo

**[Shop-Demo öffnen](https://rebo-boutique.nc321201.chatgpt.site)** · **[Verwaltungsdemo ohne Anmeldung](https://rebo-boutique.nc321201.chatgpt.site/admin/preview)**

Ein Mode-Shop-Projekt mit persischer RTL-Oberfläche, Produktvarianten, Outfit-Zusammenstellung und einer Verwaltung für nichttechnische Benutzer.

**Portfolio von Erfan Bonyani · Ausbildungsziel: Fachinformatiker für Anwendungsentwicklung.**

## Was sich ansehen lässt

Die öffentliche Verwaltungsdemo arbeitet mit getrennten Beispieldaten. Sie zeigt Produktbearbeitung, gegenseitige Outfit-Empfehlungen, Auftragsbearbeitung, Finanzansichten und Diagnose. Ein Neuladen setzt die Beispiele zurück.

| Bereich | Inhalt und Lernbezug |
| --- | --- |
| Oberfläche | Responsiver Katalog, persische Rechts-nach-links-Darstellung und verständliche Formulare |
| Geschäftslogik | Produktvarianten, Gastwarenkorb, Outfit-Zusammenstellung und wechselseitige Produktempfehlungen |
| Verwaltung | Produkteditor, Lagerbewegungen, Rollen, Finanzansichten, Retouren und Kundenverwaltung |
| Fehlersuche | Strukturierte Diagnose, Anfragezuordnung und isolierte Integrationsprüfungen |
| Medien | 3D-Referenzmodell, optionale GLB-Dateien je Produkt und vorbereiteter Foto-Anprobe-Ablauf |

## Erweiterungen in Version 12

- Schwebende Outfit-Auswahl mit konkreter Farb- und Größenvariante sowie Empfehlungen der Shop-Verwaltung.
- Teilbare Katalogfilter für Angebote, ausgewählte Produkte und Kollektionen.
- Entwürfe und veröffentlichte Kollektionen mit sortierbaren Produkten.
- Pflegehinweise und Angaben zur Größe des Fotomodells im Produkteditor.

Die Produktions-Builds für Sites und den unabhängigen Betrieb sowie 245 technische Prüfungen waren erfolgreich. Eine visuelle Browserprüfung der neuen Oberfläche war in dieser Arbeitsumgebung nicht verfügbar. Der Zahlungs- und Anprobe-Anschluss bleibt im unten beschriebenen Demo-Umfang.

## Erweiterung in Version 13

Mehrere Kleidungsstücke bleiben gleichzeitig im Outfit: beispielsweise T-Shirt, Hemd, Hoodie und Jacke mit Hose und Schuhen. Varianten, Kauf-Auswahl, Entfernen und Reihenfolge werden je Produkt verwaltet; ältere lokale Entwürfe bleiben erhalten. 257 technische Prüfungen und beide Produktions-Builds waren erfolgreich. Exakte 3D-Schichten benötigen passende Kleidungsmodelle; eine Stoff-Kollisionssimulation ist nicht enthalten.

## Technologie

TypeScript, React, Vinext/Vite, Three.js, Cloudflare Workers, D1, R2 und Drizzle. Die aktuelle Demo wird über Sites bereitgestellt; das vollständige Entwicklungsprojekt liegt in einem privaten Repository.

## Meine Rolle

Anforderungen und Abläufe für Shop und Verwaltung ausarbeiten, Funktionen praktisch prüfen, Korrekturen beschreiben und die Bereitstellung begleiten. Implementierung und Dokumentation erfolgten mit KI-gestützten Werkzeugen. Die Fallstudie beschreibt das Projekt, ohne eine vollständig selbstständige Implementierung jeder Funktion zu behaupten.

## Klarer Demo-Umfang

- Kein angeschlossener echter Zahlungsanbieter oder SnappPay-Zahlungsfluss.
- Auftrags-SMS und E-Mails sind nicht eingerichtet.
- Ein aktives FASHN-Konto ist nicht konfiguriert; Anbietertests verwenden simulierte Antworten.
- Aus Produktfotos entstehen keine automatisch rekonstruierten, exakt drehbaren 3D-Kleidungsstücke. Der vorbereitete Anprobe-Ablauf erzeugt Bilder.
- Medien, Preise und Bestände sind Demonstrationsdaten und kein echter Warenbestand.

Dieses öffentliche Repository enthält die Projektbeschreibung, keine Kundendaten, Produktionsschlüssel oder vollständige Anwendung. Es ist eine Portfolio-Präsentation, keine Freigabe des privaten Shop-Codes.

## English summary

A Persian RTL fashion-commerce demo with product variants, an outfit builder and an isolated anonymous admin preview. Real payments, order notifications and a live photo try-on provider are not connected. Development used AI-assisted tools; source code remains private.

## فارسی

ریبو نمونه‌کار فروشگاه پوشاک با رابط فارسی و پنل مدیریت است. لینک‌های بالا فروشگاه و پنل نمونه با دادهٔ آزمایشی را نشان می‌دهند. کد کامل خصوصی است و محدودیت‌های نسخهٔ نمایشی در همین صفحه مشخص شده‌اند.

**[پروفایل / Profil](https://github.com/ErfanBonyani)** · **[E-Mail](mailto:erfan.bonyaniapp@gmail.com)**
