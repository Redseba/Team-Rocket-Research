# Copilot Instructions for Team Rocket Research Project

## Code Style Conventions

### Comments
- all lowercase, short, contextual
- only where context needed (not self-explanatory code)

### Prints
- when printing results use tables over text where possible
- do not use headers like =xxx= or ***xxx*** it should be simple and clean not too cluttered
- do not use divide like -------------------- or ==================== or ******************** 

### Function Names
- `snake_case_lowercase` with underscores
- descriptive, max 3 words

## Project Overview

For our project, we are interested in analyzing a Pokemon dataset that contains information about different Pokemon including their stats, types, abilities, and many other characteristics. We are particularly interested in exploring classification problems, such as predicting a Pokemon's type (fire, water, grass, etc.) based on their base stats (HP, attack, defense, speed, etc.), which would fall under the gaming/entertainment domain. We could also investigate clustering to identify natural groupings of Pokemon with similar characteristics, correlation analysis to understand relationships between different stats, and outlier detection to find legendary Pokemon that deviate significantly from normal patterns.

### Dataset
- `Pokemon Database.csv`

### Project Objectives
- **Classification**: Predict a Pokemon's type based on base stats.
- **Clustering**: Identify natural groupings of Pokemon with similar characteristics.
- **Correlation Analysis**: Understand relationships between different stats.
- **Outlier Detection**: Find legendary Pokemon that deviate from normal patterns.

## Visualization and Modeling Guidelines

### Tools and Libraries
- Use Python with pandas for data manipulation, matplotlib and seaborn for visualizations, scikit-learn for machine learning models.
- Work in Jupyter notebooks (e.g., `analysis.ipynb`) for interactive analysis and presentation-ready outputs.

### Color Palette
- Use Set2 as the color present everywhere for consistency and aesthetics.

### Accessibility and Good Practices
- Ensure visualizations are accessible: Use high contrast colors, include patterns or markers alongside colors for colorblind users, provide clear legends and axis labels.
- Follow best practices: Include descriptive titles, labeled axes with units, avoid clutter, use appropriate chart types (e.g., boxplots for distributions and outliers, scatter plots for correlations).
- Make figures presentation-ready: High resolution, readable fonts, consistent styling.

### Specific Visualizations
- **Boxplots**: Use for analyzing distributions, identifying outliers in stats (HP, Attack, Defense, etc.), and comparing across types or clusters.
- **Histograms/Bar Charts**: For frequency distributions of types, stats, or cluster sizes.
- **Scatter Plots**: For correlation analysis between stats, with color-coding by type or cluster.
- **Heatmaps**: For correlation matrices to show relationships between variables.
- **Other**: Include plots for model evaluation (e.g., confusion matrices for classification, silhouette plots for clustering).

### Modeling Approaches
- **Preprocessing**: Handle missing values, normalize/standardize data, encode categorical variables.
- **Classification**: Use scikit-learn models like LogisticRegression, RandomForestClassifier, or SVC. Evaluate with accuracy, precision, recall, F1-score, and confusion matrices.
- **Clustering**: Use KMeans or DBSCAN. Evaluate with silhouette scores, elbow method for K selection.
- **Correlation Analysis**: Use pandas `corr()` for Pearson/Spearman correlations, visualize with heatmaps.
- **Outlier Detection**: Use IQR method or z-scores (scipy.stats.zscore) to identify outliers, visualize with boxplots highlighting legendaries.
- Ensure all models are evaluated and interpreted in the context of the Pokemon domain.

### Presentation Focus
- Create clear, explanatory graphs to illustrate each stage of the data mining process (preprocessing, analysis, evaluation, interpretation) for the 10-minute presentation.
- Prioritize visualizations that tell a story: e.g., how outliers relate to legendaries, how clusters group similar Pokemon, prediction accuracy for types.

## Evaluation Criteria

### Questions
| Level | Description |
|-------|-------------|
| Poor | Questions overly simplistic, unrelated to courses, or unmotivated |
| Good | Questions appropriate, coherent, and motivated |
| Excellent | Questions well motivated, interesting, insightful, and novel |

### Analysis
| Level | Description |
|-------|-------------|
| Poor | Choice of analysis is overly simplistic or not complete (not considering each stage of data mining: preprocessing, data analysis, model evaluation, model interpretation) |
| Good | Analysis appropriate, complete (consider each stage of data mining) |
| Excellent | Analysis appropriate, complete, advanced, and informative |

### Results/Understanding
| Level | Description |
|-------|-------------|
| Poor | Discussion and Conclusions are missing, incorrect, or not based on analysis. Limited, superficial understanding of the analytical concept. Inappropriate choice of plots; poorly labeled plots; plots missing |
| Good | Discussion and Conclusions relevant, but partially correct or partially complete. Good understanding of analytical concept. Plots convey information but lack context for interpretation |
| Excellent | Insightful discussion and relevant conclusions explicitly tied to analysis and to context. Outstanding ability to grasp concepts. Plots convey information correctly with adequate and appropriate reference information |

### Presentation Preparation (10-minute presentation)
| Level | Description |
|-------|-------------|
| Poor | Verbal presentation is illogical, incorrect, or incoherent. Visual presentation is cluttered, disjoint, or illegible. Verbal and visual presentation unrelated |
| Good | Verbal presentation partially correct but incomplete or unconvincing. Visual presentation is readable and clear. Verbal and visual presentation related |
| Excellent | Verbal presentation is correct, complete, and convincing. Visual presentation is appealing, informative, and crisp. Verbal and visual presentation clearly related |

### Writing (IEEE format, Minimal 4 pages)
| Level | Description |
|-------|-------------|
| Poor | Report is incomplete, not following the IEEE format. Explanation is illogical, incorrect, or incoherent. Lack of clarity, with some grammatical and spelling errors |
| Good | Report is complete in right format. Explanation is correct, complete, and convincing. Clear presentation of thoughts with grammatically correct sentences |
| Excellent | Report is complete in right format. Explanation is correct, complete, convincing. Outstanding ability to grasp concepts and relate theory to practice. Excellent structure and organization with grammatically correct sentences |

### Code Readability
| Level | Description |
|-------|-------------|
| Poor | Code is messy and poorly organized; unused or irrelevant code distracts when reading code. Variables and functions names do not helpful to understand code |
| Good | Code is reasonably well organized. There is little unused or irrelevant code, or this code has been moved out of the main project files. Variable and function names generally meaningful and helpful for understanding |
| Excellent | Code very well organized. No irrelevant or distracting code. Variable and function names have clear relationship to their purpose in the code. Code is easy to read and understand |

## Additional Guidelines
- Ensure all stages of data mining are covered: preprocessing, data analysis, model evaluation, model interpretation.
- Use appropriate visualizations with proper labels and context.
- Adhere to code style conventions for any code written.