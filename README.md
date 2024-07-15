# Plant-Death-Preventer

Data needed:
 - User's Plants
 - Plant Diseases
 - Plant Watering Schedules
 - Plant Hardiness Zone
 - Plant Fertilizer Schedules

Steps to seed data to DB:
 1. Make DB on Google Cloud.
 2. Download data to folder.
 3. Run the following command: mysql -u root -h "INSERT DB IP HERE" -p < database-file.sql
