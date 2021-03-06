---
title: Anmäl dig till hackathonet
excerpt: Anmälan till hackathon
ref: participant
ingress-text: Vi har nu fyllt antal deltagare för hacket! Anmäl dig gärna ändå så skriver vi upp dig på reserv-lista och hör av oss om något avhopp sker. Anmälan sker via formuläret nedan.
form:
- id: namn
  title: Ditt namn
  type: text
  required: required
- id: _replyto
  title: Din mailadress
  required: required
  type: email
- id: phone
  title: Ditt telefonnummer
  type: text
  required: required
- id: sep
  title: Identifierar du dig som kvinna eller icke-binär?
  type: radio
  options:
  - option:
    name: Ja
    id: ja
  - option:
    name: Nej
    id: nej
- id: desc
  title: Beskriv dig själv lite kort!
  type: textarea
  description: Till exempel intressen, vad du kan bidra med till projekten du är intresserad av, utbildning eller jobb. Om du har någon specifik kompetens så nämn gärna den!
- id: mat
  title: Har du några allergier eller matpreferenser?
  type: text
- id: project
  title: Vilket/vilka projekt är du intresserad av?
  type: checkbox
  required: required
  description: Läs mer om <a href="/projects/mdgh"> Vem äger staden </a>, <a href="/projects/handlingar"> Handlingar </a>, <a href="/projects/mangfaldsdata"> Öppna mångfaldsdata </a> eller <a href="/projects/civilkurage">Släktmiddag och civilkurage</a>!
  options:
  - option:
    name: Vem äger staden?
    id: vem-ager-staden
  - option:
    name: Handlingar
    id: handlingar
  - option:
    name: Öppna mångfaldsdata
    id: oppnamangfaldsdata
  - option:
    name: Släktmiddag och civilkurage
    id: kurage
- id: pre-meetup
  title: Vill du delta i en förträff?
  type: radio
  required: required
  description: För att installera mjukvara, sätta upp projekt lokalt etc. Datum är den 22/1!
  options:
  - option:
    name: Ja
    id: ja
  - option:
    name: Nej
    id: nej
- id: needs
  title: Har du några önskemål inför eller under eventet, eller några frågor?  
  type: textarea
- id: fragar
  title: Är det något du gärna vill höra presentatörerna, Vanessa eller Rebecca, prata extra om?
  type: textarea
- id: anvandare
  title: Vad är ditt användarnamn på civictech-chatten?
  description: Om du har ett och vill vara med i chatten
- id: lat
  title: Skriv en låt du tycker är bra just nu!
  type: text
- id: var
  title: Hur fick du höra om hacket?
  type: text
- id: _subject
  value: Anmälan
  type: hidden
- id: redirect_to
  value: http://civictech.se/tack/
  type: hidden
- id: _after
  value: http://civictech.se/
  type: hidden
- id: _honeypot
  value: ''
  type: hidden
- id: send
  type: submit
  title: Skicka
---
