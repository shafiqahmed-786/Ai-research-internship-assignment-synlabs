TASK 2 — SEO BLOG CREATION TOOL  
--------------------------------

Overview:
This task automates the creation of SEO-optimized blog posts for trending or
best-selling e-commerce products using:
- Product scraping (Amazon / Flipkart / eBay)
- Keyword research automation (optional via tools or heuristic extraction)
- AI / fallback template for blog generation (150–200 words)
- Optional automatic posting to WordPress / Medium

Directory Contents:
- task2_notebook.ipynb         → Complete implementation notebook
- task2_report.md / .pdf       → Step-by-step explanation of pipeline
- scraped_products.json         → Output of product scraping
- blog_posts/
    ├── product_post_1.md       → SEO blog post #1
    ├── product_post_2.md       → SEO blog post #2
- README_Task2.txt             → This file

How to Run:
1. Open the notebook in Google Colab.
2. Install required dependencies (Requests, BeautifulSoup, lxml, Pandas).
3. Fill `.env` with:
   - OPENAI_API_KEY (optional)
   - WordPress credentials (optional)
4. Run each cell in sequence.
5. Generated blog posts are saved in `blog_posts/`

Optional:
- If WordPress credentials are provided, blogs are automatically posted via REST API.
- If no API keys are provided, fallback SEO templates are used.

Important Notes:
- Only public product pages are scraped (HTML only, no violating JS rendering).
- Each blog post naturally includes 3–4 SEO keywords extracted in the notebook.

