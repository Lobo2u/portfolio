# JO EUNSOO — Data & AI Portfolio

Pencil 포트폴리오 PDF(`portfolio-1440.pdf`)의 편집 레이아웃을 반응형 HTML/CSS/JS로 옮긴 정적 사이트입니다.

Live: [https://lobo2u.github.io/portfolio/](https://lobo2u.github.io/portfolio/)

PDF iframe이 아니라 실제 웹페이지입니다. 크림 배경, 검은 타이포, 빨간 악센트, 다크 Clasq 밴드, 케이스 스터디 다이어그램은 PDF에서 추출한 정적 에셋을 사용합니다.

## Open locally

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## GitHub Pages

Settings → Pages → Deploy from a branch → `main` / `/` (root).

Published URL: `https://lobo2u.github.io/portfolio/`.

## What’s on the page

- **Hero / Profile** — Data to Working Systems, skill rows
- **Selected Works** — Clasq, KHNP, 37.5 SmartCare, PANASIA, RAPHAS
- **Other Projects / Experience / Stack**
- **Contact footer** — email, GitHub, blog, [Download PDF](portfolio-1440.pdf)

Company work is described at the same public level as the PDF. The only project repository link is the public Clasq repo already contributed to.

## Files

| File | Description |
| --- | --- |
| `index.html` | Portfolio page |
| `css/styles.css` | Pencil-matched layout and theme |
| `js/main.js` | Mobile nav and active-section highlighting |
| `assets/` | Screenshots and diagrams extracted from the PDF |
| `portfolio-1440.pdf` | Downloadable Pencil snapshot |
