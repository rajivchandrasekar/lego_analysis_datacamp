# lego_analysis_datacamp
Let's look at Lego sets! Lego is a household name across the world, supported by a diverse toy line, hit movies, and a series of successful video games. In this project, we are going to explore a key development in the history of Lego: the introduction of licensed sets such as Star Wars, Super Heroes, and Harry Potter.

let's become familiar with the two datasets that will help you with this project:

datasets/lego_sets.csv
set_num: A code that is unique to each set in the dataset. This column is critical, and a missing value indicates the set is a duplicate or invalid!
set_name: A name for every set in the dataset (note that this can be the same for different sets).
year: The date the set was released.
num_parts: The number of parts contained in the set. This column is not central to our analyses, so missing values are acceptable.
theme_name: The name of the sub-theme of the set.
parent_theme: The name of the parent theme the set belongs to. Matches the name column of the parent_themes csv file.
datasets/parent_themes.csv
id: A code that is unique to every theme.
name: The name of the parent theme.
is_licensed: A Boolean column specifying whether the theme is a licensed theme.
Goals
1. Basic exploration of the dataset
2. What percentage of all licensed sets ever released were Star Wars Themed?
3. In which year was Star Wars not the most popular licensed theme?
4. Bonus : How many unique sets were released each year 1955-2017?
