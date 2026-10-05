# Social Graph Recommender

A pure-Python social network analytics project: cleans messy user data and 
builds two recommendation features — "People You May Know" and "Pages You 
Might Like" — using collaborative filtering logic, no external libraries.

## Features
- **Data Loading & Cleaning**: Parses JSON user/page data, removes 
  duplicates, inactive users, and malformed records.
- **People You May Know**: Suggests friend connections based on mutual 
  friends, ranked by overlap count.
- **Pages You Might Like**: Recommends pages using collaborative 
  filtering based on shared page likes between users.

## Tech Stack
Python (built using only core/built-in modules, like `json`)

## How to Run
\`\`\`bash
python load_data.py
python clean_data.py
python people_you_may_know.py
python pages_you_might_like.py
\`\`\`

## What I Learned
- Writing clean, dependency-free Python for data processing
- Implementing basic collaborative filtering from scratch
- Structuring and deduplicating real-world-style messy JSON data

# social-graph-recommender
A pure-Python social network analytics project: cleans messy user data and builds two recommendation features  "People You May Know" and "Pages You Might Like"  using collaborative filtering logic, no external libraries.

