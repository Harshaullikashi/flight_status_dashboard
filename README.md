## Flight Status Dashboard

An interactive Power BI dashboard to monitor and analyze flight status information, including on‑time performance, delays, and cancellations. This project is intended as a portfolio‑ready example to showcase data visualization and reporting skills using Microsoft Power BI.

### Project Overview

- **File**: `Flight Status Dashboard.pbix`
- **Tool**: Microsoft Power BI Desktop
- **Goal**: Provide a quick, visual summary of flight operations so users can identify trends, problem routes, and peak delay periods.

### Key Features

- **Overall KPIs**: Total flights, on‑time flights, delayed flights, and cancellation counts/percentages.
- **Delay Analysis**: Breakdown of delays by airline, route, and time period.
- **Route Performance**: Comparison of on‑time performance across routes and destinations.
- **Time Trends**: Daily/weekly/monthly views to spot patterns over time.
- **Interactive Filters**: Slicers for date ranges, airlines, routes, and other key dimensions.

> Note: The exact visuals and filters may vary depending on the dataset and any customizations you make.

### Requirements

- **Microsoft Power BI Desktop**
  - Download from the Microsoft Store or from the official Power BI download page.

### How to Use

1. **Clone or download this repository**  
   - If using Git:  
     ```bash
     git clone <your-github-repo-url>
     cd flight_status_dashboard
     ```
   - Or download the ZIP from GitHub and extract it.

2. **Open the dashboard in Power BI Desktop**  
   - Double‑click `Flight Status Dashboard.pbix`, or  
   - Open Power BI Desktop → `File` → `Open` → select `Flight Status Dashboard.pbix`.

3. **Refresh data (optional)**  
   - If your `.pbix` is connected to an external data source (e.g., CSV, SQL database, API), go to `Home` → `Transform data` or `Refresh` and update connection details as needed.

4. **Explore the visuals**  
   - Use the slicers and filters to explore on‑time performance, delays, and cancellations.
   - Hover over visuals for tooltips and detailed data points.

### Repository Structure

- `Flight Status Dashboard.pbix` – Main Power BI report file.
- `README.md` – Project documentation (this file).

### Customization

- **Change data source**: Update query connections in Power BI (`Transform data`) to point to your own flight dataset.
- **Modify visuals**: Add/remove charts, adjust measures, or create new calculated columns and DAX measures as needed.
- **Branding**: Apply your own theme, colors, and logo to match your style or organization.

### How to Publish This Project to GitHub

From a terminal or PowerShell window, run the following commands in the project directory (`flight_status_dashboard`):

```bash
cd "C:\Users\dell\Downloads\flight_status_dashboard"

# If this folder is not already a Git repo, initialize it:
git init

# Add files
git add README.md "Flight Status Dashboard.pbix"

# Commit your changes
git commit -m "Add Flight Status Dashboard Power BI project and README"

# Create a new empty repository on GitHub (via the GitHub website), e.g.:
#   https://github.com/<your-username>/flight_status_dashboard

# Add the GitHub remote (replace <your-username> with your GitHub username)
git remote add origin https://github.com/<your-username>/flight_status_dashboard.git

# Push the code to GitHub
git branch -M master
git push -u origin master
```

After this, your dashboard and README will be available in your GitHub repository.

### License

You can add a license of your choice (for example, MIT) depending on how you want others to use this project.


