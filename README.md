# Text Similarity Checker

A browser-based plagiarism detection tool using the **Longest Common Subsequence (LCS)** algorithm implemented with Dynamic Programming.

## Features
- Compare two text documents by pasting or uploading .txt files
- Character-level and Word-level comparison modes
- Highlighted matched tokens in both documents
- Dynamic Programming table visualization
- Similarity percentage using Dice coefficient
- Export report as .txt file

## How to Use
1. Download `plagiarism_checker.html`
2. Open it in any browser (Chrome, Firefox, Edge)
3. Paste text or upload .txt files in both boxes
4. Click **Analyze Similarity**

## Algorithm
- **Problem:** Longest Common Subsequence (LCS)
- **Approach:** Dynamic Programming
- **Time Complexity:** O(m × n)
- **Space Complexity:** O(m × n)
- **Similarity Formula:** `2 × |LCS| / (|A| + |B|) × 100%`

## Course
Algorithm Design & Analysis — HITMS
