<img width="914" height="375" alt="Global AI Job Analysis Dashboard" src="https://github.com/user-attachments/assets/2e6abc44-94df-45d0-bccf-5ff9c394d9ab" />

1. Introduction

In today's data-driven world, Artificial Intelligence (AI) is transforming industries, creating new career opportunities, and influencing salary structures across the global workforce. As organizations continue to adopt AI technologies, understanding salary trends across different job titles, experience levels, geographical locations, industries, companies, and technical skills has become increasingly important.

This project focuses on analyzing global AI job salary data to identify compensation patterns, explore high-paying AI roles, and understand how salary distribution varies across different segments of the AI employment market. Through an interactive dashboard, the analysis presents key findings that can help job seekers make informed career decisions and enable organizations to better understand compensation trends.

Objective of the Project

The primary objective of this analysis is to examine salary distribution across the global AI job market by evaluating job titles, experience levels, employee locations, industries, companies, and technical skills.

The analysis seeks to answer the following questions:

- Which AI job titles record the highest salary values?
- How is salary distributed across different experience levels?
- Which countries have the highest reported salary totals?
- Which industries and companies record the highest salary values?
- What technical skills frequently appear in the salary analysis?
- How can these findings support career planning, recruitment, and workforce development?

The project aims to transform raw salary data into meaningful insights that support informed decision-making within the AI employment market.

Problem Being Addressed

Despite the increasing demand for AI professionals, identifying suitable career opportunities and understanding salary differences across roles, industries, and countries can be challenging. Job seekers may struggle to determine which specializations to pursue, which technical skills to prioritize, and which geographical markets to investigate.

Similarly, employers need reliable information to understand compensation patterns and develop competitive recruitment strategies.

This analysis addresses these challenges by presenting salary information through interactive visualizations that allow users to compare different dimensions of the AI job market.

## 2. Story of Data:

This section explains the structure of the data, the variables used in the analysis, and their relevance to understanding salary distribution across AI-related professions.


Data Structure:

The analysis focuses on the following variables:

- Job Title: Identifies AI-related positions, including Machine Learning Engineer, Machine Learning Researcher, Head of AI, AI Architect, AI Software Engineer, AI Research Scientist, Robotics Engineer, and AI Specialist.
- Salary: Represents the compensation measure used to compare job titles, industries, locations, and companies.
- Experience Level: Categorizes professionals according to their career stage, including entry-level, mid-level, senior-level, and executive-level.
- Employee Residence: Identifies the countries associated with employees in the dataset.
- Industry: Represents the sectors in which AI professionals work, including Automotive, Consulting, Government, Media, Real Estate, Retail, Technology, and Telecommunications.
- Company Name: Identifies organizations represented in the salary comparison, including TechCorp Inc, Future Systems, Cloud AI Solutions, Quantum Computing Inc, Cognitive Computing, and Neural Networks Co.
- Skills: Represents technical competencies associated with AI employment, including Python, TensorFlow, PyTorch, SQL, Spark, MLOps, Tableau, and Deep Learning.

Important Features and Their Significance

Salary is the primary metric used to examine compensation patterns throughout the dashboard. Job titles provide insight into differences across professional specializations, while experience levels offer a way to examine the composition of the workforce at different career stages.

Employee residence supports geographical comparisons, and the industry and company visualizations highlight where the largest reported salary totals occur. The skills visualization presents combinations of technical competencies represented in the salary analysis.

Together, these variables provide a foundation for exploring the AI employment market from multiple perspectives.

 Data Limitations and Biases

Several limitations should be considered when interpreting the findings.

First, the dashboard does not establish the dataset's collection period, sample size, or representativeness of the global AI workforce. Second, the currency and salary period should be confirmed. Third, the visualizations primarily display salary totals, which may be influenced by the number of employees represented in each category.

The dashboard also contains an inconsistency between the headline industry KPI and the detailed industry visualization. These values should be validated against the underlying data before definitive conclusions are drawn.

 3. Data Splitting and Preprocessing

Purpose

Data preprocessing is essential for ensuring that the dataset is organized consistently and suitable for analysis. Accurate data preparation helps reduce errors and improves the reliability of the dashboard's findings.

Data Cleaning

The data preparation process should include the following checks, where applicable:

- Removing duplicate records that could distort salary calculations.
- Standardizing job titles, country names, industry labels, and company names.
- Checking salary values for missing entries, invalid formats, and inconsistencies.
- Ensuring that experience levels are categorized consistently.
- Standardizing technical skill names and combinations.
- Verifying that salary values use a consistent currency and measurement period.

These checks help ensure that salary comparisons are meaningful and that different categories are represented consistently.

Handling Missing Values

Missing salary values and incomplete categorical fields should be examined before analysis. Records with missing information should be handled according to the extent of the missing data and the purpose of the analysis.

Categorical values should not be assigned arbitrarily, and salary values should not be replaced with averages without considering the effect this could have on the final results.

The specific missing-value treatment used in this project should be documented according to the actual preprocessing steps performed.

Data Transformation

The dashboard organizes salary information across several dimensions:

- Salary by job title to compare professional roles.
- Salary by employee residence to examine geographical distribution.
- Salary by industry to compare sector-level totals.
- Salary by company to identify organizations with high reported totals.
- Salary distribution by experience level to examine workforce composition or compensation distribution.
- Skills by salary to explore the technical skill combinations represented in the dataset.

These transformations make it easier to identify patterns and compare performance across different categories.

Data Validation

An important validation step is ensuring that the headline KPIs agree with the detailed visualizations. In this dashboard, the highest-paid industry KPI identifies Automotive, while the detailed industry chart displays Retail with a higher salary total. This discrepancy requires investigation.

The salary measure used in each visualization should also be verified to determine whether it represents total salary, average salary, or another calculation.

4. Industry Context:

This section explains the relevance of AI salary analysis to the wider employment and technology landscape.

Artificial Intelligence is applied across industries such as Automotive, Technology, Retail, Manufacturing, Media, Consulting, Telecommunications, and Government. Organizations in these sectors use AI for tasks such as automation, predictive modelling, intelligent systems, decision support, and operational improvement.

The dashboard examines how reported salary totals vary across these industries and the different professional roles associated with AI.

Stakeholders

The analysis may be useful to:

- AI professionals and job seekers exploring career opportunities.
- Recruiters and human resource professionals benchmarking compensation.
- Technology companies competing for skilled AI talent.
- Business executives making workforce and investment decisions.
- Career advisers and training providers identifying relevant technical skills.

Value to the Industry

The project provides a structured view of salary patterns that can support career research, recruitment planning, and compensation benchmarking.

It also highlights the importance of technical skill development and specialized expertise in an employment market where organizations increasingly rely on AI solutions.

However, salary totals should be combined with other measures, including employee counts, average salaries, and median salaries, before they are used to make compensation decisions.

Pre-Analysis:

The pre-analysis stage involves examining the dashboard's initial patterns and identifying areas for deeper investigation.

Identify Key Trends:

The dashboard presents several notable observations.

Job titles: Machine Learning Engineer records the highest displayed job-title salary total at $91,735,154, followed by Machine Learning Researcher at $90,998,372 and Head of AI at $90,685,371.

Location: Denmark records the highest displayed employee-residence salary total at $116,512,370, followed by Switzerland at $114,268,584 and Norway at $104,542,355.

Industry: The headline KPI identifies Automotive as the highest-paid industry, with a displayed value of $116,266,986. However, the detailed industry chart shows Retail at $122,007,274, which is higher than the Automotive figure.

Companies: TechCorp Inc records the highest displayed company salary total at $118,842,993, followed by Future Systems at $111,620,309.

Skills: Python, TensorFlow, and PyTorch appear prominently in the skills visualization, alongside combinations involving Tableau, MLOps, SQL, Spark, and Deep Learning.

Experience level: The pie chart displays four segments representing 40.79%, 26.42%, 19.22%, and 13.57%. The category labels are not visible in the provided image, so the percentages cannot be assigned reliably to specific experience levels.

Potential Relationships

The initial observations suggest several areas for further analysis:

- Whether particular job titles have higher average salaries than others.
- Whether geographical salary differences remain after accounting for employee counts and living costs.
- Whether industry salary totals reflect compensation differences or differences in workforce size.
- Whether particular skill combinations are associated with specific job titles or experience levels.
- Whether seniority is associated with higher individual compensation.
- Whether the same salary rankings remain consistent when the dashboard is filtered by experience level.

Initial Insights

The dashboard suggests that salary distribution varies across job titles, locations, industries, and companies. It also highlights the recurring appearance of Python and machine learning frameworks in the skills visualization.

These patterns provide a useful starting point for investigating AI career opportunities. However, further validation is required to establish the exact meaning of the salary measures and the extent to which the displayed differences reflect individual earning potential.

In-Analysis:

The in-analysis stage examines the displayed salary patterns in greater detail, compares the categories, and identifies findings that can inform further investigation.

Job Title by Salary

Machine Learning Engineer records the highest displayed job-title salary total at $91,735,154. Machine Learning Researcher follows at $90,998,372, while Head of AI records $90,685,371.

AI Architect follows at $90,543,552, and AI Software Engineer records $89,590,190. AI Research Scientist, Robotics Engineer, and AI Specialist also appear among the displayed roles.

The differences between the leading values are relatively small compared with the overall totals, indicating that several job titles have substantial salary values in the dataset.

Insight: Machine learning engineering, AI research, and AI leadership are prominent in the displayed salary comparison. However, these figures do not establish which role offers the highest average individual salary or the strongest long-term career prospects.

Recommendation: Job seekers should examine the requirements, responsibilities, and advertised salary ranges of these roles. They should also compare entry requirements and opportunities for specialization before selecting a career path.

Employee Residence by Salary

Denmark leads the geographical comparison with $116,512,370, followed by Switzerland at $114,268,584 and Norway at $104,542,355.

The United States records $98,272,778, followed by Sweden at $95,301,743, the Netherlands at $93,463,064, Singapore at $92,092,720, and Germany at $91,746,274.

The visualization shows that the total salary values associated with the displayed countries are not evenly distributed.

Insight: Denmark, Switzerland, and Norway stand out in the geographical comparison. Nevertheless, aggregate salary values alone cannot confirm that employees in these countries earn more on average than employees elsewhere.

Recommendation: Professionals exploring international opportunities should compare individual salary ranges, taxes, living expenses, employment benefits, and work permit requirements. A future analysis should incorporate average and median salaries to provide a clearer picture of individual earning potential.

Industry by Salary

The detailed industry chart presents Retail as the highest category at $122,007,274, followed by Media at $121,353,478 and Consulting at $119,954,185.

Real Estate records $116,730,529, Technology records $117,105,974, Automotive records $116,266,986, Government records $115,462,933, and Telecommunications records $114,945,537.

The detailed chart therefore ranks Retail above the Automotive industry, even though Automotive appears in the headline KPI as the highest-paid industry.

Insight: Retail, Media, and Consulting have the highest displayed industry salary totals in the detailed chart. The difference between the headline KPI and the chart suggests that the calculations, filters, or measures should be reviewed before publishing a definitive industry ranking.

Recommendation: Validate the industry KPI against the underlying data and ensure that the same measure and filters are applied consistently. Once confirmed, compare average salaries and employee counts across industries to identify sectors offering stronger individual compensation.

Company Name by Salary

TechCorp Inc records the highest displayed company salary total at $118,842,993, followed by Future Systems at $111,620,309 and Cloud AI Solutions at $111,024,051.

Quantum Computing Inc records $110,709,592, Cognitive Computing records $109,520,181, and Neural Networks Co records $109,404,851.

TechCorp Inc has a noticeably higher displayed total than the other companies in this visualization.

Insight: TechCorp Inc leads the company-level salary comparison, but the difference may reflect workforce size, compensation levels, or both. The dashboard does not provide enough information to determine which explanation accounts for the difference.

Recommendation: Compare average and median salaries by company and job title. Adding employee counts and experience-level breakdowns would help distinguish organizations with large workforces from those offering higher individual compensation.

Top Skills by Salary

The treemap highlights Python, TensorFlow, and PyTorch as a prominent combination. Other visible combinations include Python, TensorFlow, and Tableau; Python, TensorFlow, and MLOps; and Python, TensorFlow, and Deep Learning. A further category includes SQL and Spark, although its full label is partially obscured.

Insight: Python and machine learning frameworks are prominent in the skills visualization. MLOps, SQL, Spark, Tableau, and Deep Learning also appear in the displayed skill combinations.

These findings suggest that programming, machine learning development, data processing, and model deployment are useful areas to investigate when planning technical development. However, the treemap alone does not demonstrate that these skills independently cause higher salaries.

Recommendation: AI professionals should develop practical competence in Python and relevant machine learning frameworks, then strengthen complementary skills according to their target roles. Portfolio projects involving data preparation, model training, evaluation, and deployment can help demonstrate applied knowledge. Employers should identify the skills needed for their actual AI systems and provide targeted training accordingly.

Experience Level by Salary

The pie chart contains four segments of 40.79%, 26.42%, 19.22%, and 13.57%.

The largest segment accounts for 40.79%, while the smallest accounts for 13.57%. The screenshot does not show the labels identifying the four segments, and it is unclear whether the percentages represent employee counts or salary distribution.

Insight: The visualization shows an uneven distribution across four categories, but the available image does not support conclusions about which specific experience level represents the largest share.

Recommendation: Display the experience-level labels and clearly identify the measure used. Then compare average and median salaries across entry-level, mid-level, senior-level, and executive-level positions to investigate how compensation changes with experience.

Post-Analysis and Insights

The post-analysis consolidates the dashboard findings and translates the observed patterns into insights that can support career planning, recruitment, and workforce development.

Key Findings

Job titles and salary opportunities: Machine Learning Engineer records the highest displayed job-title salary total at $91.74 million, followed by Machine Learning Researcher at approximately $91.00 million and Head of AI at approximately $90.69 million.

This highlights the prominence of engineering, research, and leadership roles in the dashboard's salary comparison.

Actionable recommendation: Aspiring AI professionals should build foundational skills in programming, machine learning, and model evaluation before pursuing specialized roles. Experienced professionals should assess the requirements of their target positions and develop relevant technical and leadership capabilities. Employers should benchmark compensation using comparable roles and individual salary measures.

Geographical salary distribution: Denmark leads the displayed employee-residence comparison at approximately $116.51 million, followed by Switzerland at $114.27 million and Norway at $104.54 million.

These countries are prominent in the dashboard's geographical salary analysis, although the displayed totals do not establish differences in average individual earnings.

Actionable recommendation: Job seekers should investigate opportunities in these countries while comparing salary ranges, living expenses, taxes, employment benefits, and visa requirements. Employers should evaluate regional compensation benchmarks when recruiting international AI talent.

Industry salary distribution: Retail records the highest displayed total in the detailed industry chart at approximately $122.01 million, followed by Media at $121.35 million and Consulting at $119.95 million. The Automotive headline KPI conflicts with this ranking and requires validation.

Actionable recommendation: Verify the industry calculations and KPI filters before using the ranking for career or business decisions. After validation, compare individual compensation and employee counts across industries to identify more meaningful differences in earning potential.

Company salary distribution: TechCorp Inc leads the displayed company comparison at approximately $118.84 million, followed by Future Systems at $111.62 million and Cloud AI Solutions at $111.02 million.

Actionable recommendation: Job seekers should research relevant vacancies, responsibilities, salary ranges, and career progression opportunities at these organizations. Employers should compare compensation across equivalent roles and experience levels to identify potential gaps in their pay structures.

Technical skills and salary potential: Python, TensorFlow, and PyTorch appear prominently in the skills visualization, while MLOps, SQL, Spark, Tableau, and Deep Learning also feature in the displayed combinations.

Actionable recommendation: Professionals should prioritize technical skills relevant to their intended specialization and demonstrate their abilities through practical projects. Employers should identify skill gaps and provide targeted training that supports their AI development and deployment objectives.

Experience-level distribution: The chart shows four segments, but the category labels and underlying measure are not visible.

Actionable recommendation: Improve the chart's labels and clarify whether it represents employee counts or salary totals. Further analysis should compare compensation across the four experience levels using consistent salary measures.

Comparison with Initial Findings

The detailed analysis supports the initial observation that salary totals vary across job titles, geographical locations, industries, and companies. It also confirms the prominence of Python and machine learning frameworks in the skills visualization.

However, two limitations became apparent during the analysis. The Automotive headline KPI does not agree with the detailed industry's displayed ranking, and the experience-level categories cannot be identified from the screenshot. These issues should be resolved before drawing definitive conclusions.

Overall Post-Analysis Insight

The dashboard demonstrates how salary data can be examined from multiple perspectives to explore the global AI employment market. Machine Learning Engineer ranks first in the displayed job-title comparison, Denmark leads the geographical comparison, and TechCorp Inc records the highest displayed company salary total.

The recurring appearance of Python, TensorFlow, and PyTorch also identifies technical competencies worth investigating further. However, the findings describe patterns in the displayed data rather than proving that particular skills, countries, industries, or employers directly cause higher salaries.

The greatest value of this analysis is its ability to help users identify questions worth exploring, make more informed career decisions, and improve compensation analysis through additional measures and validation.

Recommendations and Observations

Actionable Insights

Prioritize relevant AI career paths: Machine Learning Engineer, Machine Learning Researcher, and Head of AI feature prominently in the job-title visualization. Job seekers should examine the responsibilities, technical requirements, and experience expectations of these positions before deciding which path best suits their goals.

Investigate international opportunities: Denmark, Switzerland, and Norway record the highest displayed geographical salary totals. Professionals should investigate relevant vacancies in these markets while evaluating the complete financial and practical implications of relocation.

Validate industry performance: Retail leads the detailed industry chart, whereas Automotive is identified in the headline KPI. The calculations should be checked before using either result to make strategic decisions.

Strengthen technical capabilities: Python, TensorFlow, and PyTorch feature prominently in the skills visualization. Professionals should develop practical experience with these tools and select additional skills based on the requirements of their intended roles.

Improve company-level comparisons: TechCorp Inc has the highest displayed company salary total. Adding employee counts and average or median salaries would help establish whether this reflects workforce size, compensation differences, or both.

Improve experience-level reporting: The experience-level chart should display clear labels and identify the metric represented by each percentage. This would allow users to compare career stages more accurately.

Optimizations and Business Decisions

The dashboard findings can support several improvements:

- Standardize salary calculations across KPIs and detailed charts.
- Introduce average and median salary measures alongside total salary.
- Add employee counts to provide context for aggregate salary values.
- Enable comparisons by job title, experience level, location, and industry.
- Improve labels and tooltips to clarify the meaning of each visualization.
- Use verified salary benchmarks to support recruitment and compensation planning.
- Encourage targeted training in technical areas relevant to the organization's AI projects.

Unexpected Outcomes

One important finding is the inconsistency between the Automotive industry KPI and the detailed industry chart. Another is the difference in the total salary values displayed across companies and geographical locations, which raises questions about the effect of employee counts on the rankings.

The skills treemap also presents technical skills in combinations rather than showing the independent salary contribution of each skill. These observations highlight the importance of validating the underlying data and using appropriate metrics before making conclusions.

Data Visualizations and Charts:

The dashboard presents salary data visually to make comparisons easier and allow users to identify patterns across multiple categories.

Charts and Visualizations Used

- KPI cards: Display the headline salary values for industry, job title, and location.
- Pie chart: Shows the proportions of four experience-level segments.
- Horizontal bar chart: Compares salary totals across AI job titles.
- Column chart: Compares salary totals by employee residence.
- Radar chart: Displays industry salary comparisons across multiple sectors.
- Area chart: Illustrates salary totals across selected companies.
- Treemap: Presents combinations of technical skills represented in the analysis.
- Interactive filters: Allow users to explore selected categories and adjust the dashboard view.

Explanation of Visualizations

The KPI cards provide a quick summary of the headline indicators. The horizontal bar chart makes it easier to rank job titles by displayed salary total, while the column chart highlights differences among employee-residence categories.

The radar chart supports industry comparisons, although the inconsistency between its values and the headline industry KPI requires validation. The company area chart highlights TechCorp Inc's higher displayed total, while the treemap emphasizes recurring combinations of AI-related technical skills.

The pie chart provides a view of the four experience-level segments, but the category labels need to be made visible for meaningful interpretation.

Together, these visualizations create an interactive overview of salary distribution across several dimensions of the AI employment market.


Conclusion:

This Global AI Job Analysis project demonstrates how data analysis and visualization can be used to examine salary patterns across AI job titles, geographical locations, industries, companies, experience levels, and technical skill combinations.

The dashboard identifies Machine Learning Engineer as the leading job title by displayed salary total, Denmark as the leading employee-residence category, and TechCorp Inc as the company with the highest displayed salary total. Python, TensorFlow, and PyTorch also feature prominently in the skills visualization.

These findings provide a foundation for investigating career opportunities, technical skills development, international employment, and compensation benchmarking. They also highlight the importance of validating data calculations and clearly defining salary measures before using visualizations to guide decisions.

Overall, the project demonstrates the value of transforming raw employment data into interactive visual insights. With additional validation and more detailed salary measures, the analysis could provide a stronger basis for understanding individual earning potential and making informed decisions within the global AI employment market.

