TASK 1 — AI VIDEO GENERATION TOOL  
---------------------------------

Overview:
This task implements a pipeline that automatically converts a trending news article
into a 30–60 second video using:
- Web scraping for trending news data
- AI or fallback logic for script generation
- Pexels/Unsplash for image sourcing
- TTS (Text-to-Speech) for narration
- MoviePy + Pillow for video creation

Directory Contents:
- task1_notebook.ipynb          → Full implementation notebook
- task1_report.md / .pdf        → Explanation of approach, methods, and results
- task1_outputs/
    ├── article.json            → Scraped news article data
    ├── script.json             → Generated script + overlay text
    ├── images/                 → All downloaded images used in the video
    ├── audio.wav               → Generated narration audio
    ├── out.mp4                 → Final 30–60 second video output
- README_Task1.txt              → This file

How to Run:
1. Open the notebook in Google Colab.
2. Install required dependencies (MoviePy, Pillow, Requests, BeautifulSoup).
3. Add your API keys to `.env` (optional).  
   If no OpenAI key is present, the notebook uses fallback script generation.
4. Run all cells from top to bottom.
5. The final video will be saved at:  
   `task1_outputs/out.mp4`

Important Notes:
- ImageMagick is not used to avoid Colab restrictions; Pillow is used instead.
- If OpenAI quota is unavailable, fallback script generation ensures the task still works.
- All output files are saved automatically in the `task1_outputs/` folder.

