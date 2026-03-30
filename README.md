# Advanced Statistical Methods Case Studies

This repository contains statistical analyses completed as part of an **Advanced Statistical Methods** course. The projects demonstrate applied statistical reasoning, hypothesis testing, exploratory data analysis, and modeling using R.

Each analysis investigates a real scientific or policy-related research question using datasets from the **Sleuth3** package or similar sources. The goal of these projects was to practice interpreting statistical results, evaluating assumptions, and communicating conclusions clearly.

---

# Tools and Packages Used

The analyses in this repository were conducted in **R** using several common statistical and data visualization packages.

Required packages:

```
install.packages("Sleuth3")
install.packages("ggplot2")
install.packages("tidyr")
```

Libraries used:

```
library(Sleuth3)
library(ggplot2)
library(tidyr)
```

Most datasets are loaded directly from the `Sleuth3` package.

---

# Repository Structure

Each file in this repository corresponds to a case study or chapter analysis.

```
advanced-statistical-methods
│
├── case_study_1_mercury_fish.R
├── chapter_1_senate_votes.R
├── chapter_2_sparrow_humerus.R
├── chapter_3_brain_size_litter.R
├── chapter_4_sunscreen_effect.R
├── chapter_5_trex_temperature.R
├── chapter_7_black_wheatears.R
├── chapter_8_2000_presidential_election.R
├── chapter_9_diet_dropout.R
├── chapter_19_diet_dropout.R
└── README.md
```

Each script includes:

* description of the dataset
* research question
* statistical analysis
* interpretation of results

---

# Case Study 1: Mercury Contamination in Freshwater Fish

## Background

Mercury contamination in freshwater fish is an important environmental and public health concern. Elevated mercury levels can pose risks to both humans and wildlife that consume contaminated fish.

Data were collected from **53 lakes in Florida**, measuring:

* mercury concentration in largemouth bass
* lake water pH levels

The lakes were categorized as:

* **Acidic** (pH < 7)
* **Basic** (pH ≥ 7)

## Research Question

Is there a difference in mercury concentrations in fish between acidic lakes and basic lakes?

## Statistical Question

The analysis tests whether the distribution of mercury concentrations differs between the two lake categories.

**Null Hypothesis (H₀):**
There is no difference in mercury concentrations between acidic and basic lakes.

**Alternative Hypothesis (Hₐ):**
Mercury concentrations differ between acidic and basic lakes.

---

# Chapter 1: Environmental Voting in the U.S. Senate

## Background

This dataset examines environmental voting behavior in the **United States Senate between 2005 and 2007**. Each observation represents a senator's voting record on environmental legislation.

Variables include:

* state
* senator
* political party affiliation
* number of pro-environment votes
* number of anti-environment votes
* overall percentage of pro-environment votes

## Research Question

Is there a difference in environmental voting behavior between **Republican and Democratic senators**?

This analysis investigates whether political party affiliation is associated with differences in the proportion of pro-environment votes.

---

# Chapter 2: Natural Selection in House Sparrows

## Background

In 1899, biologist **Hermon Bumpus** studied house sparrows collected after a severe winter storm. The birds were categorized based on whether they survived or died from injuries caused by the storm.

Measurements include:

* humerus (arm bone) length
* survival status

## Research Question

Do sparrows that survived the storm have different humerus lengths compared to those that died?

This analysis investigates whether physical characteristics such as bone length may have influenced survival, providing evidence for **natural selection**.

---

# Chapter 3: Brain Size and Reproductive Strategy in Mammals

## Background

This dataset contains measurements of **relative brain size for 96 mammal species**.

Relative brain size is calculated as:

```
1000 × (brain weight / body weight)
```

Species are categorized by **average litter size**:

* **Small litter**: fewer than 2 offspring
* **Large litter**: 2 or more offspring

## Research Question

Is relative brain size different between mammals with small litters and those with large litters?

This analysis explores whether reproductive strategy may be associated with brain development.

---

# Chapter 4: Effectiveness of Sunscreen

## Background

This dataset records sunlight tolerance (in minutes) for **13 patients**, measured both:

* before sunscreen treatment
* after sunscreen treatment

Because measurements were taken on the same individuals before and after treatment, the data are **paired observations**.

## Research Question

Does sunscreen significantly increase the amount of time patients can tolerate sunlight exposure?

The analysis examines differences between the paired measurements.

---

# Chapter 5: Body Temperature of Tyrannosaurus Rex

## Background

Scientists have long debated whether **Tyrannosaurus rex** was warm-blooded or cold-blooded.

One approach to investigating this question is by examining the **oxygen isotopic composition of bone phosphate**, which reflects the temperature at which bone forms.

Measurements were taken from **12 bones of a single T. rex skeleton**.

## Research Question

Do the mean isotopic compositions differ among bones?

If body temperature was constant throughout the body, the measurements should be similar across bones.

Large differences could indicate temperature variation within the body.

---

# Chapter 7: Sexual Selection in Black Wheatears

## Background

Male **black wheatears (Oenanthe leucura)** perform an unusual display behavior during breeding season: they transport large stones to nesting cavities.

Although these birds weigh only about **35 grams**, they carry an average of **3.1 kilograms of stones** during a breeding season.

Researchers hypothesized that this behavior may serve as an **honest signal of male health or fitness**.

For each male bird, researchers recorded:

* average stone mass carried
* T-cell immune response

## Research Question

Is there an association between immune system strength and the mass of stones carried?

This analysis examines the relationship between these two quantitative variables.

---

# Chapter 8: 2000 Presidential Election Analysis

## Background

This project analyzes voting data from the 2000 U.S. presidential election to determine whether Palm Beach County had an unusually high number of votes for Pat Buchanan. A log-log regression model is used to predict expected vote counts based on other Florida counties. The observed value significantly exceeds the prediction interval, suggesting a statistical anomaly consistent with possible voter confusion.

## Research Question

Is the number of votes for Pat Buchanan in Palm Beach County significantly higher than expected given the relationship between Bush and Buchanan votes in other Florida counties?

---

# Chapter 19: Diet Type and Study Dropout Rates

## Background

Weight-loss studies often compare multiple diet types. However, participant adherence is also an important factor in evaluating a diet’s effectiveness.

This dataset records the number of participants who:

* completed the study
* dropped out

for three diet types:

* **Low Fat**
* **Mediterranean**
* **Low Carbohydrate**

## Research Question

Do dropout rates differ among the three diet types?

The analysis evaluates whether the observed differences in completion rates are statistically significant.

---

# Reproducing the Analyses

To reproduce these analyses:

1. Install the required packages in R.
2. Clone this repository.
3. Run the scripts in RStudio or another R environment.

Most datasets are loaded directly from the **Sleuth3** package.

---

# Author

Brenna Bunderson
B.S. Computational Statistics and Data Science

Coursework Portfolio – Statistical Analysis in R
