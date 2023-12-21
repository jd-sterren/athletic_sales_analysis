# athletic_sales_analysis
Finished later than expected due to medical reasons.
The code within and naming conventions could be cleaned up a little more than
what is currently in there but everything should be as requested.
Added join='inner' to athletic_sales_df = pd.concat([as_2020_df, as_2021_df], axis="rows", join="inner")

Added .sort_values('Total_Products_Sold', ascending=False) to Total_Products_Sold to see the proper results.

Updated the code to reflect consistency by replacing [['total_sales']].sum() for an aggregate.

Added the .sort_values to the section as well.

Corrected the resampling issues

Added a summary below:
December 12 to December 25 2021 are the most sales week in 2021 for Women’s 
Athletic Footwear most likely due to the Christmas holiday.  The top week sale 
right into Christmas was 3,098,970 with December 16, 2021 being the second to 
highest sales day for Women's Athletic Footwear at 1,473,497.  The highest 
sales day was July 16, 2021 at 1,521,825.
