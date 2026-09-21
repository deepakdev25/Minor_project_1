# Minor_project_1
# GroupDNA – WhatsApp Chat Analytics

## About
GroupDNA is a Python-based chat analytics project that transforms an exported WhatsApp conversation into meaningful insights. It studies how members communicate, when the group is most active, which words are used most often, response patterns, silent periods, and different communication-based personality archetypes.

## Key Features

- Chat Parser – Extracts timestamps, members, and messages from the chat file.
- Group Overview – Summarizes total messages, members, and overall activity.
- Member Activity – Compares message contributions of different members.
- Word Analysis – Identifies frequently used words after basic text cleaning.
- Activity Heatmap – Shows member activity across different hours of the day.
- Response Analysis – Examines average response patterns between members.
- Silent Streaks – Finds the longest periods of inactivity for each member.
- Personality Archetypes – Assigns simple communication-based archetypes using rule-based analysis.
- Final Report – Combines the major findings into one readable report.

## Technologies Used

- Python
- NumPy
- Google Colab
- Python File Handling
- Lists, Dictionaries & Functions
- datetime

## Dataset

The project works with an exported WhatsApp chat file:

hostel_bois.txt

The dataset contains conversations from the Hostel Bois 4ever group and is used as the primary source for all analysis.

## What the Project Analyzes

GroupDNA extracts and studies:

- Total message volume
- Individual member contributions
- Most active members
- Active days and hours
- Frequently used words
- Average response patterns
- Longest silent periods
- Communication-based archetypes
- Overall group activity patterns

## Project Workflow

WhatsApp Chat Export
        ↓
Chat Parsing
        ↓
Data Cleaning
        ↓
Feature Extraction
        ↓
Group & Member Analysis
        ↓
Pattern Detection
        ↓
Final GroupDNA Report

## How to Run

1. Open the project notebook in Google Colab.
2. Upload hostel_bois.txt.
3. Run the notebook cells in sequence.
4. Check the individual analysis sections.
5. View the final GroupDNA report.

## Project Goal

The main goal of GroupDNA is to turn an ordinary WhatsApp chat into a structured set of insights. Instead of looking at thousands of messages individually, the project uses basic Python analysis to reveal who participates most, when conversations happen, what the group talks about, how members respond, and how communication patterns differ across the group.

## Project Outcome

GroupDNA demonstrates how fundamental programming concepts such as file handling, loops, lists, dictionaries, functions, string processing, datetime, and NumPy can be combined to build a practical data-analysis project from a real-world text dataset.🔗
