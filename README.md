# Azerbaijani School Graduate Enrollment Indicators (1995-2023)

This dataset compiles key enrollment indicators of school graduates from 1995 to 2023, presenting a comprehensive view of their performance in entrance exams and subsequent acceptance into higher education institutions. It includes data on both male and female graduates, offering insights into gender-specific trends and performances. The dataset features a generalized rating system that compares the school graduates' performance against the republic's average level, providing a nuanced understanding of educational outcomes over nearly three decades.

Encompassing data from all schools within the Azerbaijani region, the dataset, consisting of approximately 83,000 rows, is an invaluable asset for predictive analytics, facilitating the forecast of future university acceptance rates based on historical patterns. The dataset is structured into rows, each representing a unique combination of a school and academic year, with columns for each recorded indicator, such as attendance, average scores, and acceptance rates into different types of higher education institutions.

Authors: [Nijat Zeynalov](https://www.linkedin.com/in/nijat-zeynalov-064163142), [Natig Mamishov](https://www.linkedin.com/in/natig-mamishov/?originalSubdomain=az)

Dataset url: [HuggingFace](nijatzeynalov/az-school-graduate-enrollment)
##  Column Descriptions
school_name: The official name of the school.

region: The geographical region or administrative area where the school is located.

school_code: A unique identifier assigned to the school, often used for administrative and tracking purposes.

year: The academic year for which the data is reported.

rating_b: The generalized rating for male graduates based on their entrance exam results compared to the republic's average level.

rating_g: The generalized rating for female graduates based on their entrance exam results compared to the republic's average level.

attendance_b: The number of male graduates who attended the entrance exams.

attendance_g: The number of female graduates who attended the entrance exams.

attendance_mean_points_b: The average score obtained by male graduates in the entrance exams.

attendance_mean_points_g: The average score obtained by female graduates in the entrance exams.

accepted_mean_points_b: The average score of male graduates who were accepted into institutions.

accepted_mean_points_g: The average score of female graduates who were accepted into institutions.

accepted_scholarship_b: The number of male graduates accepted on a scholarship basis.

accepted_scholarship_g: The number of female graduates accepted on a scholarship basis.

accepted_tution_b: The number of male graduates accepted on a tuition-paying basis.

accepted_tution_g: The number of female graduates accepted on a tuition-paying basis.

accepted_private_b: The number of male graduates accepted into private institutions.

accepted_private_g: The number of female graduates accepted into private institutions.

accepted_b: The total number of male graduates accepted into any form of higher education institution.

accepted_g: The total number of female graduates accepted into any form of higher education institution.

advanced_graduate: Indicates graduates who achieved notably high results, potentially including distinctions or honors.

__Predictive Analysis Use Case: Additionally, this dataset offers a significant opportunity for predictive analytics. By leveraging the 23 years of historical data on school graduates' performance and acceptance rates, data scientists and educational researchers can develop models to forecast the number of boys and girls likely to be accepted into universities in the upcoming year. Such predictions can be instrumental for educational planners and policy-makers in allocating resources, designing targeted interventions, and preparing for future educational demands. This predictive capability underscores the dataset's utility not only as a historical record but also as a tool for proactive educational planning and policy formulation.__

Ethics and Privacy: The dataset respects privacy by omitting personal identifiers, ensuring ethical use in research and analysis. Users are encouraged to maintain ethical standards, safeguarding the dignity and privacy of the individuals and institutions represented.











