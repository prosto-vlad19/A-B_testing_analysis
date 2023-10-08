# A/B testing analysis
## Description 
The data was generated based on a casual game project in the m3 genre and a fairy-tale setting.
An A/B test was carried out in the project. Cohort A - control, cohort B - cohort,
whose recovery time for one life was reduced by 10 times from 30 minutes.

## Task
As part of the assignment, it was necessary to analyze how the project metrics were affected
Reducing life recovery time.

## Initial data

The data contains the following fields:
Retention - day of the user's life;
 - MaxLevelPassed - maximum m3 level passed;
 - User_id - user identifier;
 - AB_Cohort - test cohort;
 - SumRevenue - income from the user;
 - CountBuy - number of purchases;
 - CountAllStart - number of all starts of m3 levels;
 - CountAllFinish - the number of all victories at m3 levels;
 - CountCleanStart - number of starts of m3 levels without using all types of assistance (buying additional moves, using bonuses
and boosters);
 - CountCleanFinish - the number of victories in m3 levels without using all types of help (buying additional moves, using
bonuses and boosters);
 - Get_Ads - receiving gold for viewing advertisements;
 - Get_Chapter - receiving gold as a reward for completing chapters;
 - Get_Buy - receiving gold from a purchase;
 - Get_Faceb - receiving gold for logging into Facebook;
 - Get_TeamL - receiving gold for sending lives in a team;
 - Get_TeamT - receiving gold for completing the tutorial for teams;
 - Spend_BonLives - spending gold to buy lives for bonus chapters;
 - Spend_Bonus - spending gold to buy bonuses;
 - Spend_Boost - spending gold on buying boosters;
 - Spend_Lives - spending gold to buy lives;
 - Spend_Moves - spending gold to buy moves;
 - Spend_TeamC - spending gold on creating a team.

This is user data for 7 full days of life (the installation day is considered day zero).

## Structure of project
## Files and Modules and What They Do

| Name                   | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| `./data/data.csv`      | Initial data                                                                |
| `./data_proc`          | Folder containing supporting files.                                         |
| `activity.ipynb`       | File containing code for analyzing a group of player activity metrics.      |
| `involvement.ipynb`    | File containing code for analyzing a group of player engagement metrics.    |
| `revenue.ipynb`        | File containing code for analyzing a group of player profitability metrics. |
| `other_analysis.ipynb` | File containing code for additional analysis of test results.               |
| `report.pdf`           | File containing a report on the analysis performed.                         |

