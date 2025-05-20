
# 📦 Inventory Management System

Ein modernes webbasiertes Inventarverwaltungssystem zur effizienten Verwaltung von Produkten, Lagerbeständen und Transaktionen. Dieses Projekt wurde mit **TypeScript**, **Node.js**, **React** und **MongoDB** realisiert.

---

## 🌐 Live-Demo

👉 [Jetzt ansehen](https://inventory-delta-khaki.vercel.app)

---

## 🚀 Hauptfunktionen

- ✅ Produktverwaltung mit Name, SKU, Beschreibung, Menge und Preis
- 📦 Übersicht über alle Lagerbestände mit Such- und Filterfunktion
- ➕📤 Ein- und Ausgang von Waren mit Datum und Bemerkung
- 🔐 Authentifizierung (Login/Logout mit JWT)
- 👤 Benutzerverwaltung (Admin/Benutzer)
- 📊 Dashboard mit Statistik und Übersicht
- ⬇️ CSV-Export für Berichte
- 🎨 Responsive Design für Desktop und Mobilgeräte

---

## 🛠️ Technologien

**Frontend:**
- React.js (TypeScript)
- Tailwind CSS
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB & Mongoose
- JSON Web Token (JWT)

**Tools:**
- Vercel (Deployment)
- Git & GitHub

---

## ⚙️ Lokale Installation

### Voraussetzungen

- Node.js >= 14
- MongoDB (lokal oder MongoDB Atlas)

### Schritte

1. 📥 Repository klonen:

```bash
git clone https://github.com/almarzouk/inventory.git
cd inventory
```

2. 📁 Backend einrichten:

```bash
cd server
npm install
```

3. 🔐 `.env` Datei im `server` Verzeichnis erstellen:

```
MONGO_URI=mongodb+srv://<user>:<pass>@cluster.mongodb.net/inventory
JWT_SECRET=deinGeheimesToken
```

4. 🚀 Backend starten:

```bash
npm run dev
```

5. 📁 Frontend einrichten:

```bash
cd ../client
npm install
npm start
```

6. 🌐 App im Browser öffnen:

```
http://localhost:3000
```

---

## 📁 Projektstruktur

```
inventory/
├── client/            # React Frontend
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.tsx
├── server/            # Express Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.ts
└── README.md
```

---

## 🧪 Beispiel-Nutzer

> Für Testzwecke können Sie diesen Dummy-Account verwenden:

```
E-Mail: demo@inventory.com
Passwort: password123
```

---

## 📸 Screenshots

> *(Füge bei Bedarf Screenshots des Dashboards, der Produktliste usw. ein)*

---

## 📄 Lizenz

MIT License © [almarzouk](https://github.com/almarzouk)

---

## 🤝 Mitwirken

Beiträge und Verbesserungsvorschläge sind willkommen!

1. Fork dieses Repos
2. Erstelle einen neuen Branch `feature/neues-feature`
3. Committe deine Änderungen `git commit -m 'Neues Feature'`
4. Push auf deinen Fork `git push origin feature/neues-feature`
5. Stelle einen Pull Request

---

## 🙋‍♂️ Kontakt

📧 E-Mail: jumaa.almarzouk@gmail.com  
🌐 GitHub: [almarzouk](https://github.com/almarzouk)

---

> Erstellt mit Leidenschaft von [almarzouk](https://github.com/almarzouk)
