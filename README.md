# Vrtić

Jednostavan, responzivan sajt za vrtić napravljen u čistom HTML-u i CSS-u.

## Sadržaj

- Početna strana
- O nama
- Programi
- Galerija
- Struktura sajta
- Vesti i obaveštenja
- Kontakt

## Kako pokrenuti projekat lokalno

### Opcija 1: Otvaranje direktno u browseru

1. Kloniraj repozitorijum:

```bash
git clone https://github.com/spalekw/vrtic.git
cd vrtic
```

2. Dvoklikni na fajl `index.html`.

Ovo će otvoriti sajt u tvom podrazumevanom browseru.

---

### Opcija 2: Preko Live Server-a u VS Code-u

1. Otvori folder projekta u VS Code-u.
2. Instaliraj ekstenziju **Live Server**.
3. Desni klik na `index.html`.
4. Izaberi **Open with Live Server**.

Sajt će se otvoriti na lokalnom serveru, obično na adresi:

```text
http://127.0.0.1:5500
```

---

### Opcija 3: Preko Python servera

Ako imaš instaliran Python, pokreni:

```bash
python -m http.server 8000
```

Zatim otvori u browseru:

```text
http://localhost:8000
```

Ako koristiš Python 3 i komanda `python` ne radi, probaj:

```bash
python3 -m http.server 8000
```

---

### Opcija 4: Preko Node.js alata

Ako imaš Node.js, možeš pokrenuti:

```bash
npx serve .
```

ili:

```bash
npx http-server .
```

---

## Napomena o slikama

Galerija koristi spoljne ilustrativne slike sa interneta. Ako želiš da projekat radi potpuno offline, mogu da dodam lokalne slike u repo i da ih povežem iz `assets/` foldera.

## Tehnologije

- HTML5
- CSS3
- JavaScript za mobilni meni

## Autor

Napravljen za projekat vrtića.
