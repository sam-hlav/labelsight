# LabelSight Preflight – prototyp

Webový prototyp z případové studie **Produktový management** (VŠTE, 2026, Sam Hlaváčik).

**Spuštění:** https://sam-hlav.github.io/labelsight/

Nástroj kontroluje čitelnost, přístupnost a povinné údaje na obalu potraviny:

- **Check** – kontrast (WCAG) a výška písma pro danou vzdálenost čtení,
- **Vision** – simulace 7 zrakových vad (presbyopie, šedý zákal, VPMD, glaukom, deuteranopie, protanopie, diabetická retinopatie),
- **Comply** – povinné údaje podle nařízení (EU) č. 1169/2011,
- **AI návrh** – automaticky upravený obal (kontrastní plochy, přesazba povinných údajů na x-výšku 1,3 mm, QR s přístupnou etiketou).

Ukázkové obaly: A = Emco Mysli na zdraví Křupavé jahody a mandle 750 g, B = Bona Vita Müsli Hazelnuts Crunchy 375 g.
Tlačítkem **Analyzovat jiný obal** lze nahrát fotografii libovolného obalu – text se čte pomocí OCR (Tesseract.js) přímo v prohlížeči, nic se neodesílá na server.

LabelSight s.r.o. je fiktivní firma vytvořená pro účely studie.
