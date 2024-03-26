---
name: Frontend Checklist
about: Frontend checklist to check project before release
title: ""
labels: ""
assignees: ""
---

# Frontendowa Checklista ogólna

- [ ] Performance
  - [ ] > 90% i brak errorów, w poniższych narzędziach:
    - [ ] [Google Page Speed](https://pagespeed.web.dev/)
    - [ ] Lighthouse
- [ ] Accessibility
  - [ ] Możliwa nawigacja bez użycia myszki
  - [ ] Kompatybilność z czytnikiem ekranu
  - [ ] ARIA tags
  - [ ] > 90% i brak errorów, w poniższych narzędziach:
    - [ ] Lighthouse
    - [ ] [Wave](https://wave.webaim.org/)
- [ ] RWD - poprawność wyświetlania każdej z podstron dla breakpointów:
  - [ ] 320px
  - [ ] 375px
  - [ ] 425px
  - [ ] 640px
  - [ ] 768px
  - [ ] 1024px
  - [ ] 1280px
  - [ ] 1440px
  - [ ] 1536px
- [ ] Bezpieczeństwo
  - [ ] protokół HTTPS
  - [ ] brak możliwości ataku XSS
  - [ ] brak możliwości SQL injection (optional)
- [ ] SEO
  - [ ] Favicon
  - [ ] Sitemap + robots.txt
  - [ ] Brak errorów w konsoli
  - [ ] Poprawna semantyka HTML
  - [ ] Obecne meta tagi
    - [ ] Title
    - [ ] Description
    - [ ] Social Media Tags
- [ ] Obrazki na stronie
  - [ ] Lazy loading
  - [ ] Skompresowane do rozsądnych rozmiarów
  - [ ] Alt tagi
  - [ ] CDN (optional)
- [ ] Poprawne działanie na każdej z popularnych przeglądarek
  - [ ] Google Chrome
  - [ ] Firefox
  - [ ] Safari
- [ ] Poprawne działanie na urządzeniach mobilnych
  - [ ] Iphone
  - [ ] Android
- [ ] Analityka
- [ ] obsługa błędów jak 404 czy 500 - dedykowane error pages

# Frontendowa Checklista techniczna

- [ ] Wszystkie environment variables zawarte i opisane komentarzami w pliku .env.example
- [ ] .gitignore
- [ ] README zawierające:
  - [ ] Nazwę aplikacji
  - [ ] Opis aplikacji (rozwinięty proporcjonalnie do złożoności aplikacji)
  - [ ] Instrukcję uruchomienia oraz wymagania + wersje oprogramowania (jeśli nie ma docker-compose)
- [ ] Unit testy
- [ ] E2E testy
- [ ] Linter & Formatter
- [ ] Dependency audit
- [ ] Docker-compose (optional)
