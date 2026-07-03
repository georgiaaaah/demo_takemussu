# Takemussu Aiki — Atago Dojo (Demo)

Demo de landing page em forma de **pergaminho japonês antigo** para o **Atago Dojo**
(Takemussu Aiki). Uma única tela, viva e animada no navegador.

## Como abrir

Abra `demo/index.html` num navegador — ou sirva a pasta `demo/` localmente:

```bash
cd demo
python -m http.server 8777
# depois acesse http://localhost:8777/index.html
```

## O que a demo tem

- **App-shell**: moldura de bambu fixa + miolo (preparado para virar navegação real).
- **Papel washi envelhecido**, moldura de bambu com volume, cantos limpos.
- **Menu de 7 tabuletas ema** (kanji + PT) — fila no desktop, gaveta no mobile.
- **Caligrafia 合気 que se pinta na abertura** (traço a traço, via KanjiVG).
- **Selo hanko 和** com textura de carimbo (SVG + filtro).
- Ilustração sumi-e do Sensei, montanha, cerejeira, citação e logo do dojo.
- **Pétalas** caindo (discretas; no mobile param após 15s) e névoa estática.
- **Responsivo**: desktop = quadro emoldurado · mobile = pergaminho vertical.
- Respeita `prefers-reduced-motion`.

## Stack

HTML/CSS/JS autocontido, sem dependências externas. Assets em `demo/assets/`.

## Roadmap

1. **Demo** (este repo) — prova de conceito.
2. **Landing real** — navegação funcional, conteúdo, WhatsApp, Next.js + PWA, deploy na Vercel.
3. **Site institucional** — seções internas + CMS.

---

Créditos de traços de caligrafia: [KanjiVG](http://kanjivg.tagaini.net) (CC BY-SA 3.0).
