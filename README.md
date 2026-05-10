🎌 UniTrack — AI-Powered Unified Media Tracking Platform
UniTrack is a unified media tracking web application for users who consume stories across multiple formats — anime, manga, manhwa, books, K-dramas, and movies. While existing platforms focus on only one or two media types, UniTrack brings all forms of storytelling into a single, organized personal library.
---
✨ Features
Unified library — Track anime, manga, manhwa, K-dramas, movies, and books in one place
AI metadata fetch — Type a title and the app automatically retrieves episode count, genre, year, and airing status using AI
Episode & chapter tracking — Mark individual episodes or chapters as completed with a single click
Visual progress bars — See at a glance how far you are through any series
Status management — Mark entries as Watching, Completed, Planning, Paused, or Dropped
Cover image support — Add cover art via URL for quick visual recognition
Search & filter — Search your library or filter by category and status
Grid and list views — Switch between compact list view and visual grid view
Persistent storage — All data saved locally, nothing lost on refresh
Polished dark UI — Designed for comfortable long-session use
---
🧠 Design Philosophy
UniTrack addresses a real problem faced by modern media consumers: fragmentation. Anime is tracked on one platform, books on another, K-dramas nowhere at all. The result is lost progress, forgotten series, and decision fatigue.
UniTrack centralizes everything under a clean, consistent interface. The AI metadata system reduces manual effort — users shouldn't have to Google how many episodes a show has just to set up tracking. The episode-level granularity ensures users never lose their place even across long-running series with 100+ chapters.
The project also identifies platform synchronization (automatically pulling watch progress from Netflix, Crunchyroll, etc.) as a future extension, demonstrating awareness of real-world API constraints and ethical considerations around third-party data access.
---
🛠 Technologies Used
HTML, CSS, JavaScript (vanilla — no frameworks)
Claude API (Anthropic) — AI-assisted metadata retrieval
localStorage — client-side data persistence
---
🚀 How to Run
Clone or download this repository
Open `unitrack.html` in any modern browser
Click + Add Media to add your first entry
Type a title — AI will automatically fetch metadata
Set your status and start tracking episode by episode
> **Note:** AI metadata fetch requires an internet connection to call the Claude API.
---
🗺 Roadmap (Planned Features)
[ ] External platform sync (Crunchyroll, Netflix, Anilist API integration)
[ ] Custom user-defined media categories
[ ] Import from MyAnimeList or AniList
[ ] Reading/watching statistics and yearly wrap-up
[ ] Mobile app version
[ ] User accounts with cloud sync
---
👩‍💻 About
Built as part of a personal project portfolio focused on user-centered application design, data organization, and applied artificial intelligence. The motivation was personal — managing watchlists and reading lists across five different platforms manually is genuinely chaotic, and no single app solved it. So this one was built instead.
---
> *Somewhere between episode 47 and chapter 203, you needed a better system. This is it.*
