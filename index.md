---
layout: default
title: IT4us — Wsparcie IT dla biznesu
---

<link rel="stylesheet" href="{{ '/assets/css/custom.css' | relative_url }}">

<div class="hero">
  <h1>IT4us</h1>
  <p>Informatyka dla biznesu: zarządzanie IT, bezpieczeństwo i chmura.</p>
  <p class="cta">
    <a href="{{ '/blog' | relative_url }}" class="btn btn-tertiary">Dowiedz się więcej</a>
    <a href="{{ '/uslugi' | relative_url }}" class="btn">Usługi</a>
    <a href="{{ '/kontakt' | relative_url }}" class="btn btn-secondary">Kontakt</a>
    <a href="{{ '/en/' | relative_url }}" class="btn btn-tertiary">English</a>
  </p>
</div>

## Jak pracujemy
Łączymy otwartą komunikację z analitycznym podejściem. Wspólnie z Klientami oceniamy przydatność danych i dbamy o ich dostępność. Efekt: bezpieczeństwo informacji, ciągłość działania i zrozumiała technologia.

## Co robimy
- Zarządzamy zasobami IT i infrastrukturą.
- Zabezpieczamy i archiwizujemy dane.
- Doradzamy i prowadzimy projekty modernizacyjne.
- Zapewniamy stałe wsparcie użytkowników (helpdesk).

> „Dbamy o to, by Klienci rozumieli wykorzystywaną technologię.”

---

### Obszary
- [Chmura]({{ '/chmura' | relative_url }}) — M365, bezpieczeństwo, backup.
- [On‑premise]({{ '/onprem' | relative_url }}) — sieci, serwery, wirtualizacja.
- [Konsultacje]({{ '/konsultacje' | relative_url }}) — audyty, strategia, zgodność.
- [Helpdesk]({{ '/helpdesk' | relative_url }}) — wsparcie bieżące i SLA.

---

### Nowości
{% assign posts = site.posts | slice: 0, 3 %}
<ul>
{% for post in posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> <small>— {{ post.date | date: "%Y-%m-%d" }}</small></li>
{% endfor %}
</ul>


