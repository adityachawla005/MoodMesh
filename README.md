# In Progress

```
┌──────────────────────────────┐
│ React Frontend (client/)     │
│ - Login & mood selector      │
│ - Recommendation dashboard   │
│ - Watch party room           │
│ - Chat + reactions           │
└───────┬──────────────────────┘
        │
        ▼
┌──────────────────────────────┐
│ Express Backend (server/)    │
│ - Auth, mood update API      │
│ - Recommendation endpoint    │
│ - Watch party socket hooks   │
└───────┬────────────┬─────────┘
        │            │
        ▼            ▼
┌──────────────┐  ┌────────────────────┐
│ MongoDB      │  │ WebSocket Server   │
│ - user data  │  │ - chat sync        │
│ - mood logs  │  │ - playback control │
│ - party meta │  │ - emoji reactions  │
└──────────────┘  └────────────────────┘
        │
        ▼
┌──────────────────────────────┐
│ FastAPI AI Engine (future)   │
│ - Mood detection (text/audio)│
│ - Time-context filtering     │
│ - Hybrid reco logic          │
└──────────────────────────────┘

```

# TODO

## TODO :
- [ ] testing WebSocket

---

- [ ] /recommend
    - [x] Mood selector UI (manual)
    - [x] GET /recommend endpoint (mock content)
    - [ ] Hybrid recommendation (mood+history)
    - [ ] Python FastAPI microservice
        - [ ] model
        - [ ] scikit-learn + content embeddings

---

- [ ] Watch Party Engine
    - [x] Host / Join room via frontend
    - [ ] Socket.IO +chat
    - [ ] Video playback sync and HLS ffmpeg
    - [ ] Host controls (lock/start)
    - [ ] Public vs private rooms
    - [ ] Invite links

---

- [ ] Chat 
    - [x] Chat box + UI
    - [ ] Keyword-based spoiler blur
    - [ ] "Spoiler ahead" +moderation
    - [ ] Sentiment color bar (mood tone of chat)

---

- [ ] Dashboard
    - [x] User mood picker
    - [ ] Daily mood + genre heatmap
    - [ ] Per-user subtitle/audio setting
    - [ ] Preference learning from skips + likes
    - [ ] Suggested watch time for each show 

---

- [ ] UI / UX 

---


---

- [ ] Deployment
