# Shera

### Python Development · Telegram Automation · Web Interfaces · Applied AI

I build bots, APIs and web interfaces, with a focus on practical applications: automating interactions, connecting external services and turning data into useful results. Alongside application development, I study statistics, machine learning and computer vision.

My work spans asynchronous Python applications, database-backed tools, frontend development and educational data analysis.

## What I work on

| Area | Focus |
| --- | --- |
| **Python & backend** | Async applications, HTTP integrations, REST APIs and application logic |
| **Telegram automation** | Search flows, media processing, inline interactions, administration and bot workflows |
| **Web development** | React and Next.js interfaces, TypeScript, HTML and CSS |
| **Data analysis** | Exploratory analysis, visualization, hypothesis testing and regression |
| **Applied AI** | Learning how to prepare datasets, evaluate models and connect inference to applications |

## Selected public projects

### [Telegram Music Bot](https://github.com/SheraInf/shazam-telegram-bot)

A Python application for finding music, recognizing audio and working with media inside Telegram.

**Implemented features**

- Music search by title, artist or a text query through YouTube Music.
- Track selection, additional search results and MP3 delivery.
- Recognition of audio from voice messages, recordings, videos and video messages through ShazamIO.
- Public video downloads, recognition actions and links to music search services.
- Lyrics lookup through YouTube Music with an LRCLIB fallback.
- Inline search, Telegram audio caching and shareable links to tracks.
- Administrator tools for statistics, welcome messages, broadcast previews and referral links.
- SQLite storage, environment-based configuration and a Dockerfile for packaging.

**Stack:** Python, asyncio, aiogram, aiohttp, ytmusicapi, yt-dlp, ShazamIO, FFmpeg, SQLite and Docker.

**Validation:** 25 automated tests cover input validation, keyboards, handlers, caching, access checks, referral attribution and cancellation. Separate live service checks covered search, audio and video downloads, lyrics retrieval and music recognition.

**Status:** development and testing. Full Telegram integration, deployment and third-party availability still require validation in the target environment.

### [Boston Housing — Statistical Analysis](https://github.com/SheraInf/boston-housing-analysis)

An educational Jupyter Notebook exploring a historical dataset through statistical questions and visual analysis.

**Work covered**

- Exploratory plots using Matplotlib and Seaborn.
- A two-sample t-test comparing home values by proximity to the Charles River.
- One-way ANOVA across housing age groups.
- Pearson correlation between industrial land use and nitric oxide concentration.
- Ordinary least squares regression relating home values to distance from employment centres.

**Stack:** Python, Jupyter, Pandas, Matplotlib, Seaborn, SciPy and statsmodels.

**Status:** completed coursework notebook. The analysis is a statistics exercise using historical data.

### [AI-Based Industrial Defect Detection](https://github.com/SheraInf/Diplom-IITU-AI)

A diploma project proposal at **International Information Technology University (IITU)**, focused on automated visual inspection of industrial product surfaces.

**Planned work**

- Select a suitable industrial defect dataset and define an evaluation setup.
- Prepare images, apply preprocessing and augmentation, and establish a baseline.
- Compare deep learning approaches for defect detection and classification.
- Evaluate detection quality alongside inference speed.
- Connect model inference to a backend API and an image-upload interface.
- Store inspection history and present prediction results.

The proposal considers datasets such as NEU and MVTec AD, with candidate approaches including CNNs, ResNet, EfficientNet, YOLO and Vision Transformers.

**Status:** specification and planning. Model training, the API and the web interface are planned; evaluation results have not been published.

## Technology toolkit

| Category | Tools |
| --- | --- |
| **Primary language** | Python |
| **Backend & integrations** | asyncio, FastAPI, aiogram, python-telegram-bot, aiohttp, HTTP / REST APIs |
| **Frontend** | JavaScript, TypeScript, React, Next.js, HTML, CSS |
| **Data & statistics** | Pandas, NumPy, Matplotlib, Seaborn, SciPy, statsmodels, Jupyter |
| **Storage & tooling** | SQLite, Git, GitHub, Docker, PyCharm |
| **Media applications** | FFmpeg, yt-dlp, ShazamIO, YouTube Music integrations |

## How I approach projects

- Build a clear user flow before adding more features.
- Separate configuration and credentials from source code.
- Validate input and handle external-service failures.
- Test meaningful behaviour: permissions, callbacks, state changes and data handling.
- Document setup steps, dependencies, current limitations and project status.
- Keep implemented functionality distinct from research goals and planned work.

## Current learning focus

I am developing my understanding of machine learning and computer vision, especially dataset preparation, experimental comparisons and model evaluation. I am also interested in reliable asynchronous applications, API design, agent architectures and the integration of AI into usable software.

## Explore my work

Browse the projects above for implementation details, setup instructions and the current scope of each application.

[GitHub profile](https://github.com/SheraInf) · [Public repositories](https://github.com/SheraInf?tab=repositories)
