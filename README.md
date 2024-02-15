# Lego Sets Analysis Project
![R](https://github.com/Ayushmi-Adh/LegoDataAnalysis/assets/132826306/28df819c-8c8c-4a1f-adec-9a9e4732fe51)

## Overview:
This project explores a pivotal development in the history of Lego: the introduction of licensed sets, including popular themes like Star Wars, Super Heroes, and Harry Potter. Lego, facing challenges in the late 90s, found success with its first licensed series, Star Wars, which played a crucial role in the company's survival.

## Datasets:
Two datasets are utilized for this analysis:

### Lego Sets Dataset:
- **set_num:** A unique code for each set.
- **set_name:** Name of the set.
- **year:** Release date of the set.
- **num_parts:** Number of parts in the set.
- **theme_name:** Sub-theme of the set.
- **parent_theme:** Parent theme to which the set belongs.

### Parent Themes Dataset:
- **id:** Unique code for each theme.
- **name:** Name of the parent theme.
- **is_licensed:** Boolean indicating whether the theme is licensed.

## Analysis Steps:

1. **Merging Datasets:**
   - Merged the Lego Sets and Parent Themes datasets based on the 'parent_theme' column.

2. **Handling Missing Values:**
   - Checked for missing values in 'set_num' to identify duplicate or invalid sets.

3. **Filtering Licensed Sets:**
   - Extracted licensed sets and filtered out any remaining null values in 'set_num'.

4. **Star Wars Analysis:**
   - Focused on the Star Wars theme within licensed sets.
   - Calculated the percentage of Star Wars sets among all licensed sets.

5. **Sorting and Grouping:**
   - Sorted licensed sets by year and added a count column.
   - Grouped sets by year and parent theme, summing up the counts.

6. **Identifying Dominant Themes Each Year:**
   - Identified the dominant theme each year by sorting and selecting the top entry for each year.

7. **New Era Analysis:**
   - Analyzed sets released in 2017 and later, marking the beginning of a new era.

## Results:

### Star Wars Dominance:
- Star Wars accounted for [the_force]% of licensed sets, showcasing its significant impact.

### Dominant Themes Over the Years:
- Explored the dominant themes each year, providing insights into the evolution of popular Lego themes.

### New Era:
- Analyzed sets released in 2017 and beyond, highlighting potential shifts or trends in Lego themes during this period.

## Instructions for Replication:

1. **Dataset Files:**
   - Ensure the presence of the "lego_sets.csv" and "parent_themes.csv" files in the specified locations.

2. **Code Execution:**
   - Execute the provided Python code in a suitable environment, considering any required dependencies.

3. **Interpretation:**
   - Review the results and visualizations to gain insights into the trends and dynamics of Lego licensed sets.

## Conclusion:
This analysis provides a comprehensive overview of the impact of licensed sets on Lego's success, along with insights into the evolution of popular themes over the years. The exploration of themes post-2017 offers a glimpse into the ongoing trends shaping the Lego product line.

Feel free to explore, modify, and build upon this analysis for a deeper understanding of Lego sets' historical development.
