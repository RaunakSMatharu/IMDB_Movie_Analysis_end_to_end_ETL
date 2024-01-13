# IMDB
<img width="983" alt="Screenshot 2024-01-12 at 11 23 54 PM" src="https://github.com/RaunakSMatharu/IMDB/assets/114725836/d39b1382-1f7f-4768-975e-c02aad50cfb9">


IMDB Movies Project using Talend, MSSQL Server, Altreyx, PowerBI, MySQL, Tableau.
Tools Used: Altreyx, Talend, SSIS, MySQL,Azure DataBase
Visualization Tools: PowerBi and Tableau 


Process of the project :
1) Orchestrated data amalgamation from varied repositories including MySQL (IMDb datasets), TSV files (box office revenue), and JSON formats (film titles and performer identities), achieving an all-encompassing data union.
2) Undertook thorough data examination and profiling with Alteryx, generating comprehensive reports and discernments, accompanied by a detailed mapping ledger in Excel.
3) Forged a sophisticated data architecture emphasizing a Slowly Changing Dimension (SCD) Type 2 for Movie Titles Dimension table, fortifying data precision and historical traceability with ER Studios.
4) Engineered and executed ETL blueprints in Talend, employing metadata-driven linkages, contexts, and settings to refine data management procedures.
5) Crafted interactive and adaptable dashboards within Power BI and Tableau, validating the consistency of SQL script outcomes with visualized analytics, adeptly presenting pivotal metrics and patterns.

<h1>Observation </h1>

<h4>Alteryx Data Profiling Findings</h4>
- Rank: The film's position oscillated between 1 to 55 throughout its box office tenure, inclusive of “-” values.
- Gross: Variances in daily gross takings spanned from a low of $357 to a peak nearing $28.27 million.
- Per Theater: Earnings for each cinema fluctuated from $60 to $8,181.
- Total Gross: Aggregate gross takings progressively ascended, topping around $760.51 million.
- Days: The dataset spans 336 days post the film's debut.
- %LW and %YD exhibited null entries.

<h4>Insights and Deductions:</h4>
- Initial Box Office Surge: The film "Avatar" showcased a robust inaugural showing, as evidenced by the initial daily and per-theater gross figures.
- Sustained Cinema Presence: The film's extended presence in cinemas (336 days) underlines its enduring popularity.
- Persistent High Ranks: Despite variances, the film maintained high box office ranks during its cinematic cycle.
- Revenue Equilibrium: Post-initial surge, the total gross demonstrated equilibrium, suggesting a continuous audience flow over a protracted timeline.

<h2>PowerBI Visualisations</h2>
[Power_BI_IMDB.pdf](https://github.com/RaunakSMatharu/IMDB/files/13926788/Power_BI_IMDB.pdf)

<h2>Link for tableau</h2>
https://public.tableau.com/app/profile/raunak.singh.matharu4709/viz/Imdb_Dashboard_17018930700460/IMDB_Dashboard
