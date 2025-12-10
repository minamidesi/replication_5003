# Structure
![Screen Shot 2025-12-09 at 3.43.39 PM](https://raw.githubusercontent.com/minamidesi/blog_img_markpeng/main/Screen%20Shot%202025-12-09%20at%203.43.39%20PM.png)

# Dependencies
- Docker Desktop(4.28.0 (139021) or higher)
- Python numpy<2

# Procedure

-   Clone this project.
-   Install prequisite.
-   Generate pollution by run `docker compose up pollution`.
-   1)For testing all database, just run`chmod +x benchmark.sh; ./benchmark.sh`
-   2)For Run Specific databse(sample as `Pandas`) `docker compose up pandas-client`.
-   Get score: `docker compose up evaluate`.
-   See result in `results/aggregate_results_polluted_files.csv`.

