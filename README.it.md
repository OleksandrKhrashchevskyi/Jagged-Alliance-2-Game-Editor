# Jagged Alliance 2 Game Editor

Editor di salvataggi, dati di gioco e mappe per **Jagged Alliance 2** in un'unica finestra.

> [!NOTE]
> **La traduzione italiana è in arrivo.** Nel frattempo, tutte le informazioni sono nella [versione inglese](README.md).

## 🌐 Lingue disponibili

<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/EN-English-30363d?style=for-the-badge&labelColor=21262d&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCA2MCAzMCc%2BPGNsaXBQYXRoIGlkPSd0Jz48cGF0aCBkPSdNMzAsMTVoMzB2MTV6djE1aC0zMHpoLTMwdi0xNXp2LTE1aDMweicvPjwvY2xpcFBhdGg%2BPHBhdGggZD0nTTAsMHYzMGg2MHYtMzB6JyBmaWxsPScjMDEyMTY5Jy8%2BPHBhdGggZD0nTTAsMCA2MCwzME02MCwwIDAsMzAnIHN0cm9rZT0nI2ZmZicgc3Ryb2tlLXdpZHRoPSc2Jy8%2BPHBhdGggZD0nTTAsMCA2MCwzME02MCwwIDAsMzAnIGNsaXAtcGF0aD0ndXJsKCN0KScgc3Ryb2tlPScjQzgxMDJFJyBzdHJva2Utd2lkdGg9JzQnLz48cGF0aCBkPSdNMzAsMHYzME0wLDE1aDYwJyBzdHJva2U9JyNmZmYnIHN0cm9rZS13aWR0aD0nMTAnLz48cGF0aCBkPSdNMzAsMHYzME0wLDE1aDYwJyBzdHJva2U9JyNDODEwMkUnIHN0cm9rZS13aWR0aD0nNicvPjwvc3ZnPg%3D%3D" alt="English"></a>
  <a href="README.es.md"><img src="https://img.shields.io/badge/ES-Espa%C3%B1ol-30363d?style=for-the-badge&labelColor=21262d&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAzIDInPjxwYXRoIGZpbGw9JyNBQTE1MUInIGQ9J00wIDBoM3YySDB6Jy8%2BPHBhdGggZmlsbD0nI0YxQkYwMCcgZD0nTTAgLjVoM3YxSDB6Jy8%2BPC9zdmc%2B" alt="Español"></a>
  <a href="README.de.md"><img src="https://img.shields.io/badge/DE-Deutsch-30363d?style=for-the-badge&labelColor=21262d&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCA1IDMnPjxwYXRoIGQ9J00wIDBoNXYzSDB6Jy8%2BPHBhdGggZmlsbD0nI0QwMCcgZD0nTTAgMWg1djJIMHonLz48cGF0aCBmaWxsPScjRkZDRTAwJyBkPSdNMCAyaDV2MUgweicvPjwvc3ZnPg%3D%3D" alt="Deutsch"></a>
  <a href="README.fr.md"><img src="https://img.shields.io/badge/FR-Fran%C3%A7ais-30363d?style=for-the-badge&labelColor=21262d&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAzIDInPjxwYXRoIGZpbGw9JyMwMDIzOTUnIGQ9J00wIDBoMXYySDB6Jy8%2BPHBhdGggZmlsbD0nI2ZmZicgZD0nTTEgMGgxdjJIMXonLz48cGF0aCBmaWxsPScjRUQyOTM5JyBkPSdNMiAwaDF2MkgyeicvPjwvc3ZnPg%3D%3D" alt="Français"></a>
  <a href="README.it.md"><img src="https://img.shields.io/badge/IT-Italiano_%E2%9C%93-2ea44f?style=for-the-badge&labelColor=1a7f37&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAzIDInPjxwYXRoIGZpbGw9JyMwMDkyNDYnIGQ9J00wIDBoMXYySDB6Jy8%2BPHBhdGggZmlsbD0nI2ZmZicgZD0nTTEgMGgxdjJIMXonLz48cGF0aCBmaWxsPScjQ0UyQjM3JyBkPSdNMiAwaDF2MkgyeicvPjwvc3ZnPg%3D%3D" alt="Italiano (selected)"></a>
  <a href="README.pt.md"><img src="https://img.shields.io/badge/PT-Portugu%C3%AAs-30363d?style=for-the-badge&labelColor=21262d&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0naHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmcnIHZpZXdCb3g9JzAgMCAzMCAyMCc%2BPHBhdGggZmlsbD0nI0RBMjkxQycgZD0nTTAgMGgzMHYyMEgweicvPjxwYXRoIGZpbGw9JyMwNDZBMzgnIGQ9J00wIDBoMTJ2MjBIMHonLz48Y2lyY2xlIGN4PScxMicgY3k9JzEwJyByPSc1JyBmaWxsPScjRkZFOTAwJy8%2BPGNpcmNsZSBjeD0nMTInIGN5PScxMCcgcj0nMy4yJyBmaWxsPScjREEyOTFDJy8%2BPHBhdGggZmlsbD0nI2ZmZicgZD0nTTEwLjYgOC4yaDIuOHYyLjhhMS40IDEuNCAwIDAgMS0yLjggMHonLz48L3N2Zz4%3D" alt="Português"></a>
</p>

## 💬 Comunità

Domande, idee, mod e chiacchiere su Jagged Alliance 2 — unisciti ai fan:

<p align="center">
  <a href="https://thepit.ja-galaxy-forum.com/"><img src="https://img.shields.io/badge/The_Bear%27s_Pit-JA_Galaxy_Forum-8b5a2b?style=for-the-badge" alt="The Bear's Pit — JA Galaxy Forum"></a>
  <a href="https://discord.com/invite/Ku2H9Hf"><img src="https://img.shields.io/badge/Discord-Join_the_chat-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
</p>

- **[The Bear's Pit — JA Galaxy Forum](https://thepit.ja-galaxy-forum.com/)** — la casa del modding di Jagged Alliance 2 e 1.13: mod, mappe, strumenti e aiuto.
- **[Discord](https://discord.com/invite/Ku2H9Hf)** — chatta con altri giocatori e modder.
