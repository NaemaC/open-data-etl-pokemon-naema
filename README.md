Extract:

* Requested data for Pokémon 1-20
* Used requests. get()
* Stored all JSON responses in a list

Transform:

* Converted JSON into a pandas DataFrame
* Renamed columns
* Checked for missing values
* Dropped missing rows
* Sorted Pokémon by base experience
* Created a small report table

Load:

* Saved cleaned dataset to: data/processed/output.csv
* Saved report to:
pokemon_simple_report.csv Analyze
* Created simple charts (base XP, height, weight)