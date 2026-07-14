## 1. Git Workflow
- **Sviluppo e deploy diretti:** Lavora, committa e fai push sempre direttamente sul branch `main`. Questo è fondamentale per permettere a GitHub Pages di aggiornarsi immediatamente e mostrare le modifiche in tempo reale.

## 2. Spotify API (Regole Auree)
- **MAI usare endpoint deprecati:** L'endpoint `GET /v1/playlists/{playlist_id}/tracks` è stato deprecato e rimosso a febbraio 2026. Usa SEMPRE `GET /v1/playlists/{playlist_id}/items`.
- **Creazione Playlist:** Usa SEMPRE `POST /v1/users/{user_id}/playlists` e NON `POST /v1/me/playlists` (non supportato).
