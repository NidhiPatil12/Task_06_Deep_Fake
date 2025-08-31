README – ICC Cricket Dataset Deep Fake Video Project

1. Objective

The aim of this project was to analyze an ICC cricket dataset and convert key statistical insights into an AI-generated interview video using Google Flow. The concept was to simulate a news anchor interviewing a cricket coach, where the coach explains the data-driven findings.

2. Dataset Insights Used

From the ICC dataset, I created scripts for these questions:

Highest total runs in a single year – 973 runs (2016).

Most dismissals (catches + stumpings) – 186 dismissals.

Distribution of strike rates – most between 110–150, a few explosive outliers above 180.

Most all-round value (batting + bowling + fielding) – top score of 7986.

Biggest year-to-year decline in performance – a player dropping 859 runs between seasons.


3. Workflow

Narrative to Script

Converted dataset results into an interview script with anchor questions and coach answers.

Example: “Coach, who had the highest total runs in a single year?” → “A star batter scored 973 runs in 2016, the most in a single season.”

Video Creation in Google Flow

Entered scripts as prompts into Flow, describing scenes like “Anchor in studio” and “Coach with chart graphic.”

Used overlays such as “973 Runs – Record Season” or “186 Dismissals – Wicketkeeping Record.”

Policy Challenges

Google Flow flagged scripts mentioning real players by name (Virat Kohli, MS Dhoni, Shubman Gill).

To comply, I rewrote scripts using neutral terms like “star batter”, “legendary wicketkeeper”, or “young top-order batter.”

7-Second Limit

Flow auto-limited clips to around 7 seconds.

To adjust, I shortened scripts into single-question, single-answer exchanges.

For longer explanations, I planned multiple short clips and stitching them together.

Post-Production Option

To create a full episode, I could export all 7-second clips and merge them in DaVinci Resolve or CapCut, adding transitions and subtitles.

4. Challenges & Learnings

Policy Restrictions: Directly naming ICC players caused blocked generations.

Length Restriction: Had to adapt scripts into concise “micro-analyses.”

Creative Visualization: Flow responded well when I added data visual elements like bar charts and overlays.

5. Final Outcome

Produced multiple short clips (≈7s each) covering ICC cricket insights.

Each clip highlighted one data point (e.g., runs record, strike rate distribution).

Videos clearly labeled as “AI-Generated Data Insights” for transparency.
