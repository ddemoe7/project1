# project1
First group project - visualizations

## Rough Breakdown of Tasks:
1. Housekeeping
* Create github repository for team to collaborate in
2. Data exploration/planning
3. Load and clean datasets
* ETL steps - filtering
  * Filter on just 5 years (sale_date)
  * Keep only Single Family, Multi-Family, Mixed Use category types
  * Filter out records with “unfinished” equal to U
* ETL steps - remove extraneous columns
* ETL steps - reformat date fields (sale_date)
4. Create visualizations to tell the story - Target Wed 4/28
  * Summary table - yearly level - Jeremy
    * Avg sale price
    * Total # of Sales
    * Median, Mode, Std Dev, Etc.
  * Summary box and whiskers for sale price - review outliers and determine  threshold to filter out outliers -> DeAngelo
  * Heatmap # of sales by ZIP -> Dominique
    * Layer in demographic information
  * 5 year trend of prices - break out by any dim - Anthony
    * Potentially superimpose interest rates
  * Pie chart - bucket # of sales by age - Anjanette
  * Scatter Plot - Jeremy
    * Sq. Footage vs Sale Price
    * Market Price vs Sale Price
    * Incorporate linear regression/correlation calculations
5. Summary writeup/conclusion
