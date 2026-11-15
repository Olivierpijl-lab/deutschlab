# DeutschLab

React + TypeScript + Vite + Tailwind CSS-app voor Duits begrijpend lezen.

## Starten
1. Installeer Node.js (LTS).
2. Open deze map in een terminal.
3. Voer `npm install` uit.
4. Voer `npm run dev` uit en open de lokale URL die Vite toont.

## Bouwen
`npm run build`

## Functies
- Vier ingebouwde teksten (A1 t/m B2)
- Klikbare woorden, woordenlijst en waarschuwingen voor valse vrienden
- MyMemory als online vertaalfallback
- Persoonlijke vocabulaire in localStorage
- Duitse voorleesfunctie via Web Speech API
- Direct of achteraf nakijken
- Lokale tekstgenerator en optionele OpenAI-compatible API

Let op: API-sleutels in localStorage zijn alleen bedoeld voor lokaal testen. Gebruik voor een openbare productie-app een beveiligde backend-proxy.
