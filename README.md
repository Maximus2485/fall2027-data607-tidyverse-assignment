# DATA 607 Tidyverse Vignette Assignment




## Overview




In this assignment, you will practice collaborating on a code project with GitHub while helping build a shared collection of examples that demonstrate Tidyverse functions in R.




## Part 1: Create an Example (25 points)


**Due:** Your first vignette must be added by Monday, 11/2/2026.




Create a programming-sample **vignette** that demonstrates one or more capabilities of one or more Tidyverse packages using a dataset of your choice.




Your vignette should:




- Use one or more Tidyverse packages (for example, **dplyr**, **tidyr**, **ggplot2**, **readr**, **stringr**, or **lubridate**).
- Use a dataset from [FiveThirtyEight](https://fivethirtyeight.com/), [Kaggle Datasets](https://www.kaggle.com/datasets), or another source that you clearly identify.
- Include annotated R code that explains what each important step does.
- Demonstrate meaningful data work, such as importing, cleaning, transforming, summarizing, reshaping, or visualizing data.
- State the dataset source and the package(s) and function(s) demonstrated.




You may submit an R script (.R), R Markdown document (.Rmd), or Quarto document (.qmd). Include any supporting data or files needed for classmates and the instructor to understand your work, subject to the dataset's licensing and size limits.




## Part 2: Extend a Classmate's Vignette (15 points)




Later in the course, select one classmate's vignette and extend it with additional annotated code. Your extension should add a meaningful new analysis, transformation, visualization, or Tidyverse technique.




## GitHub Workflow




1. Create a **fork** of this repository in your own GitHub account.
2. Add your vignette and any appropriate supporting files to your fork.
3. **Edit this README in place** in your fork: add a row to the **Class Vignette Index** section below describing your initial vignette.
4. Open a pull request from your fork back to this shared repository.
5. After creating your vignette, submit your GitHub handle through the course submission link so your work can be peer-graded.
6. When you complete Part 2, return to this README and add a row to the **Vignette Extensions** section identifying the classmate and vignette you extended.




Do not submit work to the previous course repository. Use this repository for the current class only.




## Class Vignette Index





**Students:** Edit this README in place by adding one row for your Part 1 vignette.





| Author | Vignette | Packages / Functions | Dataset | What It Demonstrates |
| --- | --- | --- | --- | --- |
| Marc Campo | [Foam Rolling Your Way Through the Tidyverse](https://github.com/cam5671/data607tidy/blob/main/Tidyverse%20Assignment%201.Rmd) | dplyr::filter(), dplyr::group_by(), dplyr::summarize(), tidyr::pivot_longer(), ggplot2::ggplot() | 'FR_data_set.xlsx' | A 3-condition crossover trial examining the effect of foam rolling on flexibility. Demonstrates how tidyr and dplyr were used to reshape, summarize, and analyze the results. |

| Antik Salimullah | [FIFA 2022 World Cup Possession Analysis](Fifa 2022 Tidyverse.qmd) | readr::read_csv(), dplyr::select(), dplyr::rename(), dplyr::mutate(), dplyr::case_when(), dplyr::filter(), dplyr::group_by(), dplyr::summarise(), stringr::str_remove(), ggplot2::ggplot(), ggplot2::geom_col() | FIFA 2022 World Cup Matches (Kaggle) | Analyzes whether teams with higher ball possession were more likely to win matches during the 2022 FIFA World Cup. Demonstrates how Tidyverse functions were used to clean and transform data, calculate match outcomes, summarize results, and visualize win, loss, and draw percentages. |



| Renee Watson | [Tidyverse Assignment.Rmd](Tidyverse%20Assignment.Rmd) | readr::read_csv(), dplyr::filter(), dplyr::select(), tidyr::pivot_longer(), dplyr::mutate(), dplyr::group_by(), dplyr::summarise(), dplyr::arrange() | [World Bank Life Expectancy](https://data.worldbank.org/indicator/SP.DYN.LE00.IN) | Analyzes life expectancy across 12 countries from 2000–2024 using filtering, reshaping, summary statistics, and comparisons between 2019 and 2024. |
| Troy Tournat | [troy-tournat_vignette.qmd](troy-tournat_vignette.qmd) | lubridate::weeks(), lubridate::yday(), lubridate::ymd(), lubridate::day(), lubridate::today() | [Japanese cherry blossom data](https://www.kaggle.com/datasets/ryanglasnapp/japanese-cherry-blossom-data) | Demonstrates date functions from lubridate using Japanese cherry blossom data from 1953–2025. Also uses readr, dplyr, tidyr, and ggplot2. |
| Patricio Romero | [Exploring Vehicle Fuel Efficiency with Tidyverse](vehicle_fuel_efficiency_tidyverse.qmd) | dplyr::select(), dplyr::filter(), dplyr::mutate(), dplyr::group_by(), dplyr::summarise(), ggplot2::ggplot(), ggplot2::geom_col(), ggplot2::geom_point(), stringr::str_to_title() | [ggplot2 mpg dataset](https://ggplot2.tidyverse.org/reference/mpg.html) | Cleans and transforms vehicle data, compares city and highway MPG, summarizes fuel efficiency by vehicle class, and creates visualizations. |
| Ozge Gundogan | [Exploring Chemical Elements Using Tidyverse](Data607_Tidyverse_Project.qmd) | readr::read_csv(), readr::parse_number(), dplyr::select(), dplyr::filter(), dplyr::mutate(), dplyr::arrange(), dplyr::summarise(), dplyr::across(), stringr::str_extract(), stringr::str_remove(), ggplot2::ggplot(), ggplot2::geom_col(), ggplot2::geom_line(), ggplot2::geom_point() | [Periodic Table of the Elements (Kaggle)](https://www.kaggle.com/datasets/jwaitze/tablesoftheelements) | Cleans and analyzes chemical elements data, compares melting points, examines electronegativity trends across Period 2, and visualizes the relationship between electronegativity and first ionization energy. |
| Noelle Messaoudi | [Finding hidden missing data with tidyr::complete()](noelle_m_tidyr_complete.qmd) · [RPubs report](https://rpubs.com/NoelleMe/1473094) | tidyr::complete(), dplyr::n_distinct(), dplyr::summarise(), dplyr::mutate(), dplyr::filter(), ggplot2::ggplot() | [tidyr fish_encounters](https://tidyr.tidyverse.org/reference/fish_encounters.html) | Makes missing fish-station combinations explicit, compares detection proportions, preserves existing NA values, and plots detections by station. |
| Maxim Arisov | [Tidyverse-Vignette-Assignment.-Maxim.-Data-607] (Tidyverse Vignette Assignment. Exploring Top 250 Movies.Updated.qmd) | readr::read_csv(), dplyr::group_by(),dplyr::filter(), dplyr::select(), dplyr::mutate(), ggplot2::ggplot(), ggplot2::geom_line(), ggplot2::geom_point()| [IMDb Top 250 Movies Dataset] (https://www.kaggle.com/datasets/kushwahaaa27/imdb-top-250-movies-dataset?resource=download) |  Use of IMDb Top 250 Movies dataset to explore movie ratings by decades, 1990s, 2000s, and 2010s.|


## Vignette Extensions




**Students:** After completing Part 2, edit this README in place by adding one row that states **whose vignette you extended** and links to both the original and your extension.




| Extending Student | Original Author | Original Vignette | Extension File | New Tidyverse Work Added |
| --- | --- | --- | --- | --- |
| Your Name | Classmate Name | [original_vignette.qmd](original_vignette.qmd) | [your_extension.qmd](your_extension.qmd) | A brief description of the added analysis, transformation, or visualization. |
