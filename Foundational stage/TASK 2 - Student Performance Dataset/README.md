# Task 2 - Student Performance Analysis

## Objective
To analyze the academic performance of students by calculating subject-wise averages, validating score data, identifying top performers, and visualizing score distributions.

## Dataset
- File: StudentsPerformance.csv
- Source: Kaggle (Students Performance in Exams Dataset)
- Contains demographic information along with Math, Reading, and Writing scores.

## Steps Performed
1. Loaded the dataset using Pandas.
2. Performed data validation by checking:
   - Missing values
   - Negative score values
3. Computed average marks for Math, Reading, and Writing.
4. Created a total score column to rank students.
5. Identified the top 5 performing students based on total score.
6. Visualized:
   - Subject-wise average marks using a bar chart
   - Score distribution using histograms for each subject

## Insights from Student Performance Analysis

### 1. Subject-Wise Performance
- Reading and Writing subjects have higher average scores compared to Math.
- Math scores show a wider distribution with noticeable low-scoring students.

### 2. Top Performers
- Top 5 students recorded total scores above approximately 250.
- Students with strong Reading and Writing skills tend to have higher total scores.

### 3. Performance Patterns
- The dataset shows that students generally perform better in language-based subjects.
- Math appears to be the most challenging subject based on score distribution.

### 4. Observations for Improvement
- Additional academic support in Math may help students balance overall performance.
- Identifying patterns in demographic attributes may help future academic planning.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook or VS Code

## Files Included
- analysis.ipynb
- StudentsPerformance.csv
