# <div align="center"><h1>Statistics for Data Science</h1><p>
<b>A structured collection of Statistics, Probability, and Hypothesis Testing</b>
</p><p>
<code>Data Science</code> • <code>Statistics</code> • <code>Probability</code> • <code>Python</code> • <code>Machine Learning</code>
</p></div><hr><h2>About This Repository</h2><p>
This repository contains my <b>completed learning and practical implementation of Statistics</b> as part of my Data Science and Machine Learning journey.
</p><p>
The topics covered range from <b>descriptive statistics and probability</b> to <b>hypothesis testing and relationships between variables</b>. The repository contains concepts, formulas, notes, and Python-based implementations wherever applicable.
</p>---

<h2>Learning Progress</h2><table>
<tr>
<th>Technology / Topic</th>
<th>Status</th>
</tr><tr>
<td><b>Python</b></td>
<td>Completed</td>
</tr><tr>
<td><b>NumPy</b></td>
<td>Completed</td>
</tr><tr>
<td><b>Pandas</b></td>
<td>Completed</td>
</tr><tr>
<td><b>Statistics</b></td>
<td><b>Completed</b></td>
</tr>
</table>---

<h1>1. Descriptive Statistics</h1><p>
<b>Descriptive Statistics</b> focuses on collecting, organizing, summarizing, and understanding data.
</p><h2>1.1 Statistical Visualization</h2><p>
Statistical visualization is used to represent data graphically and identify patterns, trends, distributions, and unusual observations.
</p><ul>
<li>Histograms</li>
<li>Bar Charts</li>
<li>Scatter Plots</li>
<li>Box Plots</li>
<li>Distribution Visualization</li>
</ul>---

<h2>1.2 Measures of Central Tendency</h2><p>
Measures of central tendency describe the <b>central or typical value</b> of a dataset.
</p><table>
<tr>
<th>Measure</th>
<th>Description</th>
</tr><tr>
<td><b>Mean</b></td>
<td>Arithmetic average of the observations.</td>
</tr><tr>
<td><b>Median</b></td>
<td>Middle value after arranging the observations.</td>
</tr><tr>
<td><b>Mode</b></td>
<td>Most frequently occurring value.</td>
</tr>
</table>---

<h2>1.3 Measures of Spread</h2><p>
Measures of spread describe how widely the observations are distributed.
</p><ul>
<li>Range</li>
<li>Variance</li>
<li>Standard Deviation</li>
<li>Interquartile Range (IQR)</li>
</ul>---

<h2>1.4 Outliers</h2><p>
An <b>outlier</b> is an observation that is unusually different from the other observations in a dataset.
</p><h3>IQR Method</h3><p><b>Interquartile Range:</b></p><p align="center">
<b>IQR = Q3 − Q1</b>
</p><p><b>Lower Bound:</b></p><p align="center">
<b>Q1 − 1.5 × IQR</b>
</p><p><b>Upper Bound:</b></p><p align="center">
<b>Q3 + 1.5 × IQR</b>
</p><p>
The IQR method can be used to identify potential outliers in a dataset.
</p>---

<h2>1.5 Five Number Summary</h2><p>
The Five Number Summary provides a compact description of a dataset.
</p><table>
<tr>
<th>Value</th>
<th>Description</th>
</tr><tr>
<td><b>Minimum</b></td>
<td>Smallest observation</td>
</tr><tr>
<td><b>Q1</b></td>
<td>First Quartile</td>
</tr><tr>
<td><b>Median / Q2</b></td>
<td>Middle value</td>
</tr><tr>
<td><b>Q3</b></td>
<td>Third Quartile</td>
</tr><tr>
<td><b>Maximum</b></td>
<td>Largest observation</td>
</tr>
</table>---

<h2>1.6 Variance</h2><p>
<b>Variance</b> measures the degree to which observations differ from their mean.
</p><p>
A higher variance indicates greater dispersion, while a lower variance indicates that observations are closer to the mean.
</p>---

<h2>1.7 Standard Deviation</h2><p>
<b>Standard Deviation</b> measures the amount of variation or dispersion in a dataset.
</p><ul>
<li>Small standard deviation → observations are closer to the mean.</li>
<li>Large standard deviation → observations are more widely spread.</li>
</ul>---

<h2>1.8 Density Curve</h2><p>
A <b>Density Curve</b> represents the distribution of continuous numerical data.
</p><p>
It helps in understanding the shape and distribution of a dataset.
</p>---

<h2>1.9 Z-Score</h2><p>
A <b>Z-Score</b> indicates how many standard deviations an observation is away from the mean.
</p><p align="center">
<b>Z = (X − μ) / σ</b>
</p><p>
Z-scores are useful for:
</p><ul>
<li>Standardization</li>
<li>Comparing observations</li>
<li>Identifying potential outliers</li>
<li>Statistical analysis</li>
</ul>---

<h1>2. Probability</h1><p>
<b>Probability</b> measures the likelihood or chance of an event occurring.
</p><h2>2.1 Basic Probability</h2><p>
Covered the fundamental concepts of probability, including:
</p><ul>
<li>Sample Space</li>
<li>Outcomes</li>
<li>Events</li>
<li>Probability of an Event</li>
</ul>---

<h2>2.2 Probability Events</h2><p>
Studied different types and relationships between probability events.
</p><ul>
<li>Independent Events</li>
<li>Dependent Events</li>
<li>Mutually Exclusive Events</li>
<li>Compound Events</li>
</ul>---

<h2>2.3 Addition Rule</h2><p>
The addition rule is used to calculate the probability of events occurring together through their union.
</p><p align="center">
<b>P(A ∪ B) = P(A) + P(B) − P(A ∩ B)</b>
</p>---

<h2>2.4 Multiplication Rule</h2><p>
The multiplication rule is used to calculate the probability of the intersection of events.
</p><p align="center">
<b>P(A ∩ B) = P(A) × P(B)</b>
</p>---

<h2>2.5 Conditional Probability</h2><p>
<b>Conditional Probability</b> calculates the probability of one event occurring when another event is already known to have occurred.
</p><p align="center">
<b>P(A | B) = P(A ∩ B) / P(B)</b>
</p>---

<h2>2.6 Bayes' Theorem</h2><p>
<b>Bayes' Theorem</b> is used to update the probability of an event based on new information or evidence.
</p><p align="center">
<b>P(A | B) = [P(B | A) × P(A)] / P(B)</b>
</p><p>
Applications include classification, prediction, and probabilistic Machine Learning algorithms.
</p>---

<h1>3. Hypothesis Testing</h1><p>
<b>Hypothesis Testing</b> is a statistical method used to make conclusions about a population using sample data.
</p><h2>3.1 Hypothesis Testing Basics</h2><h3>Null Hypothesis (H<sub>0</sub>)</h3><p>
The Null Hypothesis generally represents the assumption that there is <b>no significant difference or effect</b>.
</p><h3>Alternative Hypothesis (H<sub>1</sub>)</h3><p>
The Alternative Hypothesis represents the possibility that a <b>significant difference or effect exists</b>.
</p><h3>P-Value</h3><p>
The P-value is used to evaluate the evidence against the Null Hypothesis.
</p><table>
<tr>
<th>Condition</th>
<th>Decision</th>
</tr><tr>
<td><b>p-value &lt; α</b></td>
<td>Reject H<sub>0</sub></td>
</tr><tr>
<td><b>p-value ≥ α</b></td>
<td>Fail to reject H<sub>0</sub></td>
</tr>
</table>---

<h2>3.2 Z-Test</h2><p>
Studied the <b>Z-Test</b> and its application in statistical hypothesis testing.
</p><ul>
<li>Z-Test concepts</li>
<li>Statistical significance</li>
<li>Hypothesis testing</li>
<li>Z-Test implementation in Python</li>
</ul>---

<h2>3.3 T-Test</h2><p>
Studied the <b>T-Test</b> for statistical comparison and hypothesis testing.
</p><ul>
<li>One Sample T-Test</li>
<li>Independent T-Test</li>
<li>Paired T-Test</li>
<li>T-Test implementation in Python</li>
</ul>---

<h2>3.4 Two Sample Test</h2><p>
Studied statistical testing methods used to compare two independent samples or groups.
</p><ul>
<li>Comparison of two groups</li>
<li>Comparison of sample means</li>
<li>Statistical significance</li>
<li>Python implementation</li>
</ul>---

<h2>3.5 Chi-Square Test</h2><p>
The <b>Chi-Square Test</b> is used primarily for categorical data and is useful for testing relationships or differences involving categorical variables.
</p><ul>
<li>Observed values</li>
<li>Expected values</li>
<li>Categorical variables</li>
<li>Statistical significance</li>
<li>Python implementation</li>
</ul>---

<h2>3.6 ANOVA Test</h2><p>
<b>ANOVA</b> stands for <b>Analysis of Variance</b>.
</p><p>
It is used to analyze differences among the means of multiple groups.
</p><ul>
<li>Group comparison</li>
<li>Between-group variation</li>
<li>Within-group variation</li>
<li>Statistical significance</li>
</ul>---

<h1>4. Relationship Between Variables</h1><h2>4.1 Covariance</h2><p>
<b>Covariance</b> describes the direction in which two variables tend to change together.
</p><table>
<tr>
<th>Covariance</th>
<th>Interpretation</th>
</tr><tr>
<td><b>Positive</b></td>
<td>Variables tend to move in the same direction.</td>
</tr><tr>
<td><b>Negative</b></td>
<td>Variables tend to move in opposite directions.</td>
</tr>
</table>---

<h2>4.2 Correlation</h2><p>
<b>Correlation</b> measures the strength and direction of a linear relationship between two variables.
</p><p align="center">
<b>−1 ≤ r ≤ +1</b>
</p><table>
<tr>
<th>Correlation</th>
<th>Interpretation</th>
</tr><tr>
<td><b>+1</b></td>
<td>Perfect positive correlation</td>
</tr><tr>
<td><b>0</b></td>
<td>No linear correlation</td>
</tr><tr>
<td><b>−1</b></td>
<td>Perfect negative correlation</td>
</tr>
</table>---



<h1>Tools and Libraries</h1><table>
<tr>
<th>Tool / Library</th>
<th>Purpose</th>
</tr><tr>
<td><b>Python</b></td>
<td>Programming and statistical implementation</td>
</tr><tr>
<td><b>NumPy</b></td>
<td>Numerical computation</td>
</tr><tr>
<td><b>Pandas</b></td>
<td>Data manipulation and analysis</td>
</tr><tr>
<td><b>Matplotlib</b></td>
<td>Data visualization</td>
</tr><tr>
<td><b>Seaborn</b></td>
<td>Statistical visualization</td>
</tr><tr>
<td><b>SciPy</b></td>
<td>Statistical tests and scientific computing</td>
</tr>
</table>---

<h1>Learning Journey</h1><div align="center"><pre>
Python
   ↓
NumPy
   ↓
Pandas
   ↓
Statistics
   ↓
Exploratory Data Analysis
   ↓
Machine Learning
   ↓
Machine Learning Projects
</pre></div>---

<h2>Objective</h2><p>
The objective of this repository is to build a strong foundation in <b>Statistics for Data Science and Machine Learning</b>.
</p><p>
Through this learning journey, I have developed an understanding of how statistical concepts can be used to analyze data, identify patterns, measure relationships, evaluate hypotheses, and support data-driven decision making.
</p>---

<div align="center"><hr><p>
<b>Statistics provides the foundation for understanding data and making data-driven decisions.</b>
</p></div>
