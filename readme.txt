===========================================================================================================
PROJECT: Digital Discourse on Climate Security: Structural Resilience and Emotional Paradoxes during COP27
COURSE:  Social Media Analytics (Academic Year 2025/2026)
AUTHORS: Any Das (922710), Arnab Biswas (925349) & Summan Gul (925663)
===========================================================================================================

1. PROJECT OVERVIEW
-------------------
This project performs an integrated Social Network Analysis (SNA) and Social Content Analysis (SCA) to identify structural patterns and emotional 
shifts in climate security discussions on Twitter/X surrounding the COP27 summit. The analysis covers the period from June 2022 to May 2023.

Key Findings (Paradoxes):
- The Resilience Paradox: The Global South maintains a more positive/constructive 
  tone compared to the skepticism found in the Global North.
- The Structural Thematic Paradox: The network topology is democratic/connected, 
  yet the content remains segregated in echo chambers.
- The Dilution Effect: High tweet volume during the COP27 summit coincided with 
  a 57.4% collapse in network density.

2. SUBMITTED FILES
------------------
The submission folder contains the following files:

[A] Main Documents:
1. SMA_Report_Das_Biswas_Gul.pdf         : The complete project report.
2. SMA_Project_Das_Biswas_Gul.ipynb      : Jupyter Notebook containing all analysis code.
3. SMA_Presentation_Das_Biswas_Gul.pdf   : Presentation slides summary.
4. README.txt                            : This file.

[B] Raw Input Datasets (REQUIRED to run the code):
5. CS-co-hashtags-net_dynamic_NODES.csv      : Raw Nodes Dataset.
6. CS-co-hashtags-net_dynamic_EDGES.csv      : Raw Edges Dataset.
7. cs_tweets_annotated.csv                   : Raw Content/Sentiment Dataset.

[C] Processed/Generated Datasets (Outputs):
The code generates these files during execution. They are included as backups.
8. nodes_June2022toMay2023_FINAL.csv         : Cleaned Node Data.
9. edges_June2022toMay2023_FINAL.csv         : Cleaned Edge Data.
10. cs_annotated_June2022toMay2023_FINAL.csv : Cleaned Sentiment Data.
11. sna_communities_June2022toMay2023.csv    : Community Detection Results.
12. sna_centrality_June2022toMay2023.csv     : Centrality Scores.

3. HOW TO RUN THE CODE
----------------------
The project is hosted on a shared Google Drive folder. To ensure the code runs correctly in Google Colab, please follow these steps precisely:

1.  Access the Shared Folder:
    Open the shared folder link:

2.  ADD SHORTCUT TO YOUR DRIVE:
    Since the code uses absolute file paths, you MUST add this folder as a 
    shortcut to your own "My Drive" before mounting.
    - Right-click the folder name 'SMA_Das_Biswas_Gul'.
    - Select "Organize" > "Add shortcut".
    - Choose "My Drive" and click "Add".
    
    *Reason: This allows the Colab script to find the datasets at:*
    '/content/drive/MyDrive/SMA_Das_Biswas_Gul/Climate_Security_Datasets/'

3.  Open the Notebook:
    Open 'SMA_Project_Das_Biswas_Gul.ipynb' and select "Open with Google Colab".

4.  Execute the Cells:
    - Run the first cell: drive.mount('/content/drive') and authorize 
      access to your own Google Drive account.
    - Go to "Runtime" > "Run all".
    
    The script will automatically install required libraries, access the shortcut folder in your Drive, and display all visualizations and metrics.

===========================================================================================================