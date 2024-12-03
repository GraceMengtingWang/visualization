# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    
    I chose the Annual Population Projection, from 2023 to 2051 by age and gender organized by geography - 49 census divisions from[Ontario’s Open Data Catalogue] https://data.ontario.ca/dataset/population-projections/resource/03abe0d5-0995-4ce2-ad9d-e904d50106a5

    First one (Please refer to the A4_Appendix.ipynb for codes and the visualization):  
    > What software did you use to create your data visualization?
    Python

    > Who is your intended audience? 
    The intended audience includes policymakers, urban planners, demographers, and researchers interested in understanding population trends and distributions across regions. Additionally, this visualization could be valuable for educators or students analyzing census and demographic data.

    > What information or message are you trying to convey with your visualization? 
    The visualizations aim to highlight the distribution of populations by age groups across key regions, helping to identify age-related demographic trends.
  
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive: The bar chart compares population distributions by age group for clarity and ease of interpretation.
  
    Perceptual:
    - Use of distinct colors for each age group and region to avoid confusion.
    - Clear axis labels, titles, and legends ensure accessibility.
  
    Aesthetic: Balanced spacing and consistent font sizes to enhance readability.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    - The entire process is documented with Python code, ensuring reproducibility.
    - The code includes data cleaning, preprocessing, and visualization steps.
    - The dataset was loaded programmatically, making it easier for others to replicate the results using the same file.

    > How did you ensure that your data visualization is accessible?  
    - Colors: A color-blind-friendly palette was used to ensure accessibility for individuals with visual impairments.
    - Annotations: The charts include clear titles, legends, and axis labels.
    - Clarity: Complex data was broken into simpler subsets, and legends were used to guide the audience through the visualizations.

    > Who are the individuals and communities who might be impacted by your visualization?  
    - Policymakers: May use the insights to allocate resources effectively across regions.
    - Communities: Regional data may highlight demographic needs such as healthcare, education, or housing, influencing funding or development decisions.
    - Researchers: The data could impact future studies on population dynamics or urban development.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    Included Features:
    - Total population by region and age group for the bar chart.
    - These features were chosen for their relevance to the primary objectives of understanding distributions and trends.
    
    Excluded Features: Detailed gender breakdowns and fine-grained age groups were excluded to avoid overloading the visualizations and maintain focus on the broader trends.

    > What ‘underwater labour’ contributed to your final data visualization product?
    Data Cleaning: Addressing missing values, duplicate entries, and ensuring consistent formats.
    Preprocessing: Aggregating data where necessary (e.g., resolving duplicates by summing values).
    Design Decisions: Choosing appropriate chart types, color schemes, and layouts for effective communication.
    Coding: Writing and testing Python code to handle the data pipeline and create the visualizations.
    Iteration: Adjusting visualizations based on feedback or identified issues to ensure clarity and accuracy.

    Second one (Please refer to the file "Population Trends by Gender (2023-2051.twbx)"):  
    > What software did you use to create your data visualization?
    Tableau

    > Who is your intended audience? 
    The visualization is intended for public sector officials, such as regional planners and policymakers, as well as private organizations that rely on demographic trends for decision-making. It is also valuable to educators and researchers studying population dynamics over time. By incorporating filtering, we also provide functionality for local administrators and demographers to zoom in on specific regions or genders for more focused analysis.

    > What information or message are you trying to convey with your visualization? 
    This chart seeks to reveal population growth patterns between genders over time from 2023 to 2051. The goal is to illustrate the gendered demographic shift and highlight disparities or equalities in population growth. With the inclusion of region and gender filters, users can dive deeper into specific areas or isolate gender-based trends, making the chart adaptable to various use cases.
  
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    Substantive Principles:

    - Relevance: 
      i. Focused on the most critical variables (year, gender, and population total) to avoid clutter.
      ii. Filter Functionality: Added filters for regions and genders to enable users to focus on specific subsets of the data.

    - Perceptual Principles:
      i. Color Differentiation: Used distinct, intuitive colors to represent each gender, ensuring clarity in the visual distinctions between data points.
      ii. Temporal Flow: Ordered data chronologically on the X-axis to naturally follow how trends develop over time.

    - Aesthetic Principles:
      i. Consistency: Chose harmonious colors and clean fonts to ensure a professional and visually cohesive chart.
      ii. Minimalism: Avoided excessive details like gridlines or overlapping labels to maintain simplicity.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    - Accessible Dataset: Used a publicly available dataset with clear column names and well-documented data fields.
    - Filters for Custom Analysis: The filters (region and gender) enhance reproducibility by allowing users to easily replicate subsets of the analysis.
  
    > How did you ensure that your data visualization is accessible?  
    - Interactive Filters: Added filters for gender and region, enabling users to tailor the chart to their specific interests or accessibility needs.
    - Color Accessibility: Used color palettes that are distinguishable even for users with color vision deficiencies.
    - Labeling: Clear data labels and tooltips provide precise information without overwhelming the viewer.

    > Who are the individuals and communities who might be impacted by your visualization?  
    - Policymakers: Gain insights to shape gender-inclusive policies and allocate resources equitably across regions.
    - Regional Administrators: Use filters to focus on specific areas for localized planning and development.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    - Included Features:
      i. Year: As the primary timeline for observing population trends.
      ii. Gender: To distinguish demographic changes between men and women.
      iii. Total Population: To show the overall scale of the demographic shift.
    - Excluded Features:
      i. Age Groups: Excluded to keep the chart concise and focused on gender.
      ii. Regions (Aggregated): Regional data was included as a filter, not as a primary variable in the chart, to allow flexibility without overloading the visual.

    > What ‘underwater labour’ contributed to your final data visualization product?
    - Testing Visualizations: Experimented with various chart types to identify the most effective way to present gender and population trends.
    - Filter Configuration: Incorporated interactive filters for region and gender to enhance the adaptability of the visualization.
    - Refining Layout: Adjusted axes, labels, and line styles to ensure the visualization was both accurate and visually appealing.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
