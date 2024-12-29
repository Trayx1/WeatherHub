# WeatherHUB

Ein modernes Wetter-Dashboard, das Wetterdaten aus mehreren zuverlässigen Wetter-APIs abruft, den Durchschnitt der Daten berechnet und präzise Wetterinformationen anzeigt. Dieses Projekt kombiniert eine ansprechende grafische Oberfläche mit einem robusten Backend, um die Genauigkeit der Wettervorhersage zu verbessern.

## Funktionen

- **Mehrere Wetter-APIs:** OpenWeatherMap, WeatherAPI.com und MetaWeather
- **Durchschnittsberechnung:** Temperatur und Luftfeuchtigkeit werden aus den verschiedenen APIs gemittelt
- **Moderne Benutzeroberfläche:** Ähnlich wie die Wetter-Apps von Apple oder Samsung
- **Responsives Design:** Funktioniert auf verschiedenen Geräten und Bildschirmgrößen
- **Animationsunterstützung:** Sanfte Übergänge und Animationen für eine bessere Benutzererfahrung

## Technologien

- **Backend:**
  - Node.js
  - Express.js
  - Axios
  - dotenv
  - CORS
- **Frontend:**
  - HTML5
  - CSS3 (inkl. Flexbox und Animationen)
  - JavaScript (ES6)

## Installation

### Voraussetzungen

- **Node.js** und **npm** installiert
- API-Schlüssel von [OpenWeatherMap](https://openweathermap.org/api) und [WeatherAPI.com](https://www.weatherapi.com/)

### Schritte

1. **Klone das Repository:**

    ```bash
    git clone https://github.com/dein-benutzername/weather-dashboard.git
    cd weather-dashboard
    ```

2. **Backend Setup:**

    Navigiere zum `backend`-Ordner:

    ```bash
    cd backend
    ```

    Installiere die Abhängigkeiten:

    ```bash
    npm install
    ```

    Erstelle eine `.env`-Datei und füge deine API-Schlüssel hinzu:

    ```env
    PORT=5000
    OPENWEATHER_API_KEY=dein_openweathermap_api_schlüssel
    WEATHERAPI_API_KEY=dein_weatherapi_com_api_schlüssel
    ```

    Starte den Backend-Server:

    ```bash
    npm start
    ```

    Der Server läuft auf `http://localhost:5000`.

3. **Frontend Setup:**

    Öffne ein neues Terminal und navigiere zum `frontend`-Ordner:

    ```bash
    cd ../frontend
    ```

    Starte einen einfachen HTTP-Server. Du kannst dazu `http-server` verwenden. Installiere es global, falls noch nicht geschehen:

    ```bash
    npm install -g http-server
    ```

    Starte den Server:

    ```bash
    http-server -c-1
    ```

    **Alternativ:** Öffne einfach die `index.html`-Datei im Browser.

    **Hinweis:** Stelle sicher, dass der Backend-Server läuft, da das Frontend Daten von `http://localhost:5000` abruft.

## Nutzung

1. **Starte den Backend-Server:**

    ```bash
    cd backend
    npm start
    ```

2. **Öffne das Frontend:**

    Öffne die `frontend/index.html`-Datei in deinem Browser oder starte einen lokalen HTTP-Server.

3. **Wetterdaten abrufen:**

    - Gib den Namen einer Stadt in das Suchfeld ein.
    - Klicke auf "Suchen" oder drücke die Enter-Taste.
    - Die Anwendung zeigt die durchschnittliche Temperatur, Luftfeuchtigkeit und eine Wetterbeschreibung an.

## Beitrag leisten

Beiträge sind willkommen! Bitte folge diesen Schritten:

1. **Fork** das Repository.
2. **Erstelle** einen neuen Branch (`git checkout -b feature/NeuesFeature`).
3. **Commit** deine Änderungen (`git commit -m 'Füge neues Feature hinzu'`).
4. **Push** zum Branch (`git push origin feature/NeuesFeature`).
5. **Erstelle** eine Pull-Request.

## Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert. Siehe die [LICENSE](LICENSE) Datei für Details.
