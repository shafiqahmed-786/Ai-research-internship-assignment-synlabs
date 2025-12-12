# Task 2 Report — SEO Blog Post Creation Tool

## Data Source
- Demo scraping: books.toscrape.com (safe demo site)

## Steps followed
1. Scraped product title, price, description and URL.
2. Extracted candidate SEO keywords using YAKE.
3. Generated a 150-200 word SEO-friendly blog for each product using OpenAI (fallback if no key).
4. Saved blog markdown files in task2_outputs/blogs/.

## Outputs (saved files):

- blog_1.md

- blog_2.md

- blog_3.md

- blog_4.md

- blog_5.md

- blog_6.md


## Notes & Limitations
- Real search-volume for keywords not fetched (requires Google Keyword Planner/SerpAPI).
- Amazon / other sites often disallow scraping; use APIs or explicit permission.
- OpenAI usage may incur token costs.
