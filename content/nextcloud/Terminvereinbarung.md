Mit Hilfe einer Nextcloud und der kostenlosen Erweiterung "Appointments" kann man in wenigen Schritten ein DSGVO-konformes Buchungssystem für Termin (z.B. Elternsprechtag oder Schulanmeldung) installiert werden. In diesem Video erkläre ich die einzelnen Schritte:

<div class="video-container">
<iframe sandbox="allow-same-origin allow-scripts allow-popups" src="https://tube.foss-schule.de/videos/embed/d9ac3e21-e0b0-4da8-8b20-452d4ab77e41?warningTitle=0" frameborder="0" allowfullscreen></iframe>
</div>

# Ressourcen und Hinweise
{{< button href="https://apps.nextcloud.com/apps/appointments" >}}Appointments-App{{< /button >}}

Code zur Einbindung eines Datenschutzhinweises:
```
<label for="appt_gdpr_id">Die Hinweise zum </label><a href="LINK_ZUR_DATENSCHUTZERKLÄRUNG">Datenschutz</a><label for="appt_gdpr_id"> habe ich gelesen und akzeptiert.</label>
```
