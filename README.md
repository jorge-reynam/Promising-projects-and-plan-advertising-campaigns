# Video Game Sales Analysis

## Project Overview
This project analyzes historical video game sales data to identify trends across platforms, genres, and regions. The goal is to uncover patterns that can support **data-driven decision-making** in the gaming industry, particularly in marketing and product strategy.


## Objectives
- Analyze the lifecycle of gaming platforms  
- Identify top-performing platforms and genres  
- Evaluate regional differences in sales  
- Explore the relationship between user reviews and sales  
- Validate statistical hypotheses about user ratings  


## Dataset
The dataset includes information on:
- Game titles  
- Platforms (e.g., PS2, Xbox, PC)  
- Release years  
- Sales (global and regional)  
- User and critic scores  
- Genres  


## Methodology
The analysis was carried out in the following steps:

1. **Data Cleaning & Preparation**
   - Handling missing values  
   - Standardizing column names  
   - Filtering relevant time periods  

2. **Exploratory Data Analysis (EDA)**
   - Platform lifecycle analysis  
   - Sales distribution using boxplots  
   - Identification of top-selling games and genres  

3. **Statistical Analysis**
   - Correlation analysis (sales vs user reviews)  
   - Hypothesis testing for:
     - Platform ratings (Xbox One vs PC)  
     - Genre ratings (Action vs Sports)  

4. **Regional Analysis**
   - Comparison of platform and genre performance across regions  


## Key Visualizations

### Global sales distribution by platform 
![Global sales distribution by platform](Images/Number_of_total_sales_of_different_video_games_platforms.png)
The chart shows the PS2 leading historical software sales with over $1.2 billion, followed by a high-performing cluster of the X360, PS3, and Wii.

### Annual Sales Performance by Video Game Platform (2000–2016)
![Sales for each platform per year](Images/Sales_for_each_platform_per_year.png)
This grouped bar chart tracks the lifecycle of major consoles, showing the transition from the PS2 era to the peak dominance of the Wii, PS3, and X360.
It highlights how each platform typically sustains a 7 to 10-year market presence before being phased out by next-generation hardware like the PS4 and XOne.


### Impact of Critic and User Reviews on X360 Global Sales
![Impact of Critic and User Reviews on X360 Global Sales](Images/Scatter_plot.png)
These scatter plots illustrate a stronger positive correlation between high critic scores and total sales compared to user ratings, which show more dispersion.
While top-rated games by critics consistently drive higher revenue, user scores demonstrate that commercial success is less dependent on audience sentiment alone.

### Global Sales Distribution and Variance by Platform
![Global sales distribution by platform](Images/Global_sales_distribution_by_platform.png)
This box plot visualizes the distribution of sales per game across different platforms, highlighting the NES and GB as having the highest median sales and greatest variance.
While most modern platforms show a lower median with numerous outliers, these classic systems maintained a higher "average" performance per title during their market lifespan.

### Heatmap: Cross-Platform Sales Performance per Title
![Heatmap: sales per video game and platform](Images/Heatmap_sales_per_video_game_and_platform.png)
This heatmap visualizes sales for specific game titles across different hardware, highlighting the PS3 and X360 as the primary revenue drivers for multi-platform releases.
By identifying "hot spots" (dark red), businesses can pinpoint which platforms offered the highest return on investment for specific franchises and global sporting events.



### Platform Trends
- Older platforms (pre-2000) tend to have longer life cycles.  
- Modern platforms show shorter but more dynamic market presence.  

### Top Platforms
- Leading platforms: **PS2, X360, PS3, Wii, GBA, PS4, PSP, 3DS, XB, GC**  
- **PS3, Wii, and X360** showed strong growth and profitability potential (2000–2011).  

### Sales Distribution
- Sales are unevenly distributed across platforms.  
- A few games generate extremely high sales (**outliers**), while most remain average.  

### Sales vs Reviews
- Weak correlation between **user reviews and sales**.  
- Sales cannot be reliably predicted based on ratings alone.  

### Platform-Specific Performance
- Game success varies significantly by platform.  
- Example: *007: Quantum of Solace* performs differently depending on the platform.  

### Top Genres
- Highest-selling genres:
  - Action  
  - Sports  
  - Shooter
  

## Regional Insights
- Platform and genre popularity vary across regions.  
- Some platforms dominate specific markets but not others.  
- Differences likely driven by **availability and user preferences**.  

---

## Hypothesis Testing

- H0: User ratings for **Xbox One vs PC** are **not statistically equal**  
- H1: User ratings for **Action vs Sports genres** are **statistically similar**  


## Business Recommendations
- Use **regional insights** to design targeted marketing campaigns  
- Focus on **top-performing genres and platforms per region**  
- Avoid relying solely on **user ratings** for sales predictions  
- Prioritize platforms with **sustained growth trends**  


## Skills Demonstrated
- Data Cleaning & Preprocessing (Pandas, NumPy)  
- Exploratory Data Analysis (EDA)  
- Data Visualization (Matplotlib / Seaborn)  
- Statistical Testing  
- Business Insight Generation  

## Future Work
- Build predictive models for sales forecasting  
- Incorporate critic reviews and external factors  
- Analyze trends for newer platforms (post-2015)  


## How to Run
```bash
# Clone the repository
git clone https://github.com/your-username/video-game-sales-analysis.git

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook



