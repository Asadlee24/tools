# 🚀 Instagram Analytics & AI Insights Tool

InstaPulse is a premium, self-contained single-page Instagram Analytics Dashboard that fetches public profile data, computes core engagement metrics, and uses the Claude API to provide strategic growth insights.

## ✨ Features

- **Hero Search Area:** Search by username or run instantly using **Demo Mode** (pre-loaded profile dataset).
- **Core Statistics Profile:** Followers, following, total posts, bio content, verification state, and website links.
- **Engagement Analytics:** Computes average likes, comments, estimated weekly posting cadence, and calculates a color-coded engagement rate.
- **Top Content Grid:** View top 6 posts sorted by likes, featuring hover overlays with dates, full captions, and post types (Photo, Reel, Carousel).
- **Reels Performance:** Highlights average views and likes across reels alongside the top 3 videos by views.
- **Stories & Highlights:** Tracks active story counts and displays highlights with titles and circular cover images in a horizontal scroll row.
- **Hashtag & Mention extraction:** Parses text content from recent posts to chart top 10 hashtags (horizontal bar chart) and map account `@mentions`.
- **Bio & Niche Scorer:** Extracts contact details, detects niche classifications (Fashion, Tech, Gaming, Food, Fitness, Travel, Beauty, Business, Music, Photography), and runs a bio keywords extractor.
- **Historical Engagement Chart:** Features a responsive dual-dataset lines chart mapping likes and comments (scaled x10) of the last 12 posts.
- **Circular Quality Score:** Grade computed dynamically based on engagement rates, upload consistency, follower ratio, and profile completeness.
- **AI growth recommendations:** Sends JSON payload summarizing creator metrics to Claude (`claude-3-5-sonnet-20241022`) directly from the browser to receive growth recommendations, best times to post, interest audits, and caption templates. Has a fallback mockup intelligence engine when API keys are not supplied.
- **Report Sharing:** Click to copy a text summary of the dashboard statistics directly to the clipboard.
- **Premium Themes:** Toggle seamlessly between Light Mode and a low-contrast, dark mode.

## 🛠️ Tech Stack

- **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+)
- **Styling:** Tailwind CSS (via CDN)
- **Icons:** FontAwesome v6
- **Typography:** Playfair Display (headings) & Inter (body)
- **Charts:** Chart.js (via CDN)

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Asadlee24/tools.git
   ```
2. Navigate into the folder and open `instagram-analytics.html` directly in any web browser.
3. Click **"Try with Demo Data"** to preview the full dashboard experience, or configure your **RapidAPI Key** and **Claude API Key** via the settings icon (sliders) in the header to run live lookups!

---

*Data sourced from public Instagram profiles. Developed for educational use.*
