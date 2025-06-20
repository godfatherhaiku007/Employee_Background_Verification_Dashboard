Employee Background Verification Analysis Report

1). Introduction: This report summarizes the Employee Background Verification project, which validates the educational credentials of 50,000 employees using Python (Jupyter Notebook), Excel, and Power BI. The dataset includes names, degrees, institutions, graduation years, employers, job titles, and emails. The project flags records with invalid graduation years (>2025) or non-accredited institutions.

2).Methodology:
• Data Generation: A synthetic dataset was created using Faker in Python, with 50,000 records across 10 institutions and employers.
• Validation: Records were validated in Jupyter Notebook, checking graduation years against 2025 and institutions against an accredited list (Harvard, Stanford, MIT, Oxford, Cambridge).
• Analysis: Excel pivot tables summarized verification status and distributions.
• Visualization: Power BI dashboards displayed verification status, employer, and institution breakdowns.

3). Results:
• Verification Status: 25,013 (50.03%) records verified, 24,987 (49.97%) flagged.

• Institution Distribution:
o University of Cambridge: 5,042
o Harvard University: 5,036
o University of Oxford: 5,026
o Stanford University: 4,963
o MIT: 4,946
o Non-accredited (Flagged): 24,987 (ETH Zurich, Caltech, Chicago, Princeton, Yale).

• Employer Distribution: Evenly spread (~5,000 per employer), with no significant verification bias.
Insights

• Nearly half the records are flagged due to non-accredited institutions, indicating a strict accreditation criterion.

• Accredited institutions account for ~50% of records, showing balanced representation.

• Employer distribution is uniform, suggesting no sector-specific issues.
• Data quality is high, with no missing values and robust year data.

4). Conclusion The project effectively identifies invalid educational credentials, with 50% of records verified. Expanding accreditation and automating processes can improve accuracy and scalability. Power BI dashboards provide clear insights for HR decision-making.
