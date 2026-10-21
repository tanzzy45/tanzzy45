## Hi, I'm Tanmay Surve

I'm a backend and machine learning engineer. I build Python services that deal with messy real-world data, like weather forecasts, scraped storefronts and broadcast video, and I make sure they're tested and deployed.

**Looking for:** backend or ML engineering roles · **Email:** tanzzyy45@gmail.com

---

### What I've built

**🏏 [Cricket pitch maps from broadcast video](https://github.com/tanzzy45/sports/tree/feat/cricket-pitch/examples/cricket)** · *computer vision, contributing to [roboflow/sports](https://github.com/roboflow/sports/issues/74)*
Finds where each delivery bounced using only TV footage. A YOLOv8 ball detector I trained, pitch calibration from keypoints, camera-motion compensation with optical flow, and a physics fit of the ball's flight.
→ Finds **8 of 9 bounces within 1 m on broadcasts the model never saw**, with a median error of **21 cm**.

**🚚 [Weather-aware truck routing](https://github.com/tanzzy45/weather-truck-routing)** · *Django, React, Docker, CI* · [live demo](https://weather-truck-routing-kn0b.onrender.com)
Compares three truck routes using the weather forecast for the hour the truck reaches each point on the way, adjusted for load weight. Includes a rules engine with full test coverage, a 48-hour weather heatmap over the route corridor, and "leave later" re-planning.

**🛍️ [Shoppers: multi-store product search](https://github.com/tanzzy45/shopper)** · *FastAPI, async Redis, React*
Searches five Indian stores at once with async scrapers. Uses Redis caching with background prefetch, Redis-based rate limiting, and fuzzy search for a seller marketplace.

### Open source

- [roboflow/sports#72](https://github.com/roboflow/sports/pull/72): fixed `draw_paths_on_pitch` drawing only the first path, and added the repo's first tests
- [roboflow/sports#74](https://github.com/roboflow/sports/issues/74): proposal and working implementation for cricket support

### Stack

**Backend:** Python, FastAPI, Django REST Framework, Flask, Redis, asyncio, pytest
**ML / CV:** PyTorch, YOLOv8 (Ultralytics), OpenCV, supervision, NumPy
**Infra:** Docker, GitHub Actions, Render, Linux
**Frontend (when needed):** React, TypeScript
