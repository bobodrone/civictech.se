---
title: Anmäl dig till meetup
excerpt: Integritetshäng i Stockholm
ref: integrity-register
ingress-text: Integritets-häng i Stockholm den 24/3
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
  description: Används endast för att kontakta dig om eventet tex ställs in på kort varsel.
- id: interest
  title: Vad är du intresserad av att göra på meetupen?
  type: textarea
  description: Du kan även komma och se vad som händer utan en färdig plan!
- id: allergies
  title: Allergier eller matpreferenser
  type: text
- id: _subject
  value: Anmälan integritet
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
