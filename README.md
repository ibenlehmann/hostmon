# Teknisk dokumentation - Grp. 5

---

## Om Projekt

I dette projekt har vi lavet et redesign af Høst Møns hjemmeside. Vi har udviklet sitet med astro. I implementeringen har vi brugt HTML, CSS og javascript til opbygning og styling af projektet.

---

### Links

- GitHub repository:
- GitHub Pages:
- Figma: https://www.figma.com/design/8vLMxzgLEyU5IuNchbyVXw/Team-5---Tema-9?node-id=0-1&t=IeCo6EEgYlmWzZji-1
- Trello: https://trello.com/b/8sOZb4Qs/tema-9-team-5

---

## Projektstruktur

```
project/
├── public/
│   ├── favicon.ico
│   ├── favicon.svg
│   └── img/
├── src/
│   ├── components/
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   └── Kunstner.astro
│   ├── layouts/
│   │   └── Layout.astro
│   ├── pages/
│   │   ├── faellesspisning.astro
│   │   ├── frivillige.astro
│   │   ├── index.astro
│   │   ├── om.astro
│   │   └── program.astro
├── .env
└── README.md
```

---

## Filbeskrivelser

- index.astro – Forsiden
- faellesspisning.astro – statisk side
- frivillige.astro – statisk side
- om.astro - statisk side
- program.astro – viser en liste med data fra API'et, samlet i kunstner cards
- Layout.astro ─ styrer hovedlayoutet for alle sider og global style
- Footer.astro & Header.astro - komponenter til navigation og bund af siden

---

# Data og JSON-struktur

Igennem supabase henter vi data fra et API i JSON-format.

#### Et af vores objekter kan fx se sådan ud:

```
{
    "id": 1,
    "created_at": "2026-04-17T07:19:14.559321+00:00",
    "name": "SNUGGLE",
    "info": "Det meget omtalte og roste samarbejde mellem Andrea Thuesen fra Baby in Vain (Høst Møn 2024) og Vilhelm Strange fra Liss har sparket døren ind til alt og alle med albummet Goodbyehouse i 2025.",
    "date and time": "2026-08-28T18:30:00",
    "img": ""
  },
```

---

# Felter vi bruger

- name - kunstnernavn
- info - beskrivelse af kunstner
- date and time - dato og tid artist spiller
- img - billede af kunstner

## Navngivning

Vi har prøvet at navngive vores filer, variabler og funktioner så tydeligt som muligt.

Eks.
frivillige.astro - er siden om at være frivillige.

---

## Git og Branches

Vi har brugt Github til at samarbejde om projektet.

Vi arbejder i branches, så vi ikke ændre i det samme samtidig

### Workflow

1. Lave en branch med et beskrivende feature-navn eller med eget navn
2. Kode en feature
3. Committe ændringer
4. Pushe til GitHub
5. Merge til main når det virkede

---

## Bæredygtighed

Vi har tænkt bæredygtighed ind i projektet, ved at arbejde med astro, som er komponentbaseret, så vi genbruger kode, frem for at gentage samme kode flere steder. Vi har også benyttet billedeoptimereing, ved at filstørrelserne er mindre, så der bliver brugt mindre data.

## Udfordringer undervejs

## Mulige forbedringer

---

## Gruppemedlemmer:

- Iben
- Laura
- Sofie
