# 🌐 AIway

> **Impara, applica, crea: l’intelligenza artificiale al tuo servizio**

**AIway** è una piattaforma web educativa e interattiva pensata per chi vuole imparare a usare l'intelligenza artificiale in modo pratico, creativo e personalizzato.

---

## ✨ Funzionalità

- ✅ Quiz interattivi con punteggio e salvataggio
- 🤖 Domande personalizzate con risposta automatica da AI
- 📁 Esportazione e importazione dati utente (JSON)
- 👤 Gestione profilo locale (nickname, storico)
- ⚙️ Sezione impostazioni personali
- 📚 Sezioni tematiche: scuola, lavoro, social, guadagno, creatività

---

## 📂 Struttura progetto

```
src/
├── components/
│   └── AILandingPage.jsx
├── App.jsx
├── main.jsx
├── index.css
public/
└── index.html
```

---

## 🚀 Deploy

Puoi distribuire il sito facilmente usando [Vercel](https://vercel.com) o [Netlify](https://netlify.com).

---

## 🔐 API KEY (facoltativa)

Per abilitare le risposte dell'intelligenza artificiale tramite OpenAI, crea un file `.env` e inserisci:

```
VITE_OPENAI_API_KEY=la_tua_api_key
```

Nel codice, assicurati di usare:

```js
Authorization: `Bearer ${import.meta.env.VITE_OPENAI_API_KEY}`
```

---

## 👨‍💻 Autore

Realizzato con passione e attenzione ai dettagli per essere una guida completa e inclusiva all'uso dell'IA.

---

## 📜 Licenza

© 2025 AIway. Tutti i diritti riservati.

---

### 👉 Provalo ora! Pubblicalo su Vercel e condividi con il mondo.
