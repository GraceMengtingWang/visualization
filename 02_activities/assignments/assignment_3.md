# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        Good one: https://public.tableau.com/app/profile/chimdi.nwosu/viz/MakeoverMondayWk43-TheMostReliableCarBrandsintheUS/Dashboard1
        
        The good visualization is largely accessible and equitable, though slight improvements (e.g., addressing color blindness and normalization) would enhance its usability. 

        1. Accessibility
        Strengths:
        a. The clear layout, use of legends, and labeling of key insights make the visualization easy to understand for most audiences.
        b. Alignment with best practices in visual clarity, as advocated by Tufte and Few, ensures minimal cognitive load.
        Weaknesses:
        a. Accessibility for color-blind users could be improved by using patterns or high-contrast colors.
        b. Some text (e.g., "distance from AVG" annotations) is small, potentially limiting readability.
        
        2. Reproducibility
        Strengths:
        a. The design is straightforward, and the process of creating such a visualization using tools like Tableau, Power BI, or Python libraries is reproducible with proper data.
        b. The simplicity of the bubble chart ensures it can be recreated easily without advanced skills.
        Weaknesses:
        Lack of detailed metadata (e.g., data source or methodology for calculating PP100) may limit exact reproduction.

        3. Equity
        Strengths:
        a. The visualization treats all countries and brands equally, providing a balanced comparison.
        b. Visual elements (e.g., bubble sizes and distances) allow users to understand brand rankings without requiring domain expertise.
        Weaknesses:
        Country-level averages are not normalized for the number of brands, which could lead to misleading comparisons (e.g., comparing Sweden’s single brand to Japan’s seven brands).

        Bad one: https://www.pinterest.com/pin/47639708534134635/

        1. Accessibility
        Weaknesses:
        a. The use of 3D distorts the data, making proportions harder to interpret.
        b. The high-contrast yellow background and overlapping patterns create visual clutter, reducing accessibility for those with visual impairments.
        c. Small text sizes and the lack of percentage labels make it challenging to read and understand.
        
        2. Reproducibility
        Weaknesses:
        a. Reproducing this visualization in its current form is difficult because 3D pie charts often depend on proprietary design tools, which may introduce inconsistencies.
        b. No metadata or clear data source is provided, limiting reproducibility.

        3. Equity
        Weaknesses:
        a. The design prioritizes aesthetics over clarity, making it inaccessible to audiences unfamiliar with pie charts or 3D effects.
        b. The lack of clear labels and metadata makes the visualization less inclusive, as it requires the audience to make assumptions or have prior context to interpret it.

        ```
    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Good one:
        1. Accessibility: Use color-blind-friendly palettes, increase text readability, and add interactivity for detailed information.
        2. Reproducibility: Provide metadata, raw data, and documentation of the visualization process.
        3. Equity: Normalize country comparisons, add context for market dynamics, and avoid reinforcing biases in the data.

        Bad one:
        1. Accessibility: Remove 3D effects, simplify the design with 2D charts, improve text readability, and use color-blind-friendly palettes.
        2. Reproducibility: Share raw data, include metadata and design documentation, and use tools that allow straightforward replication.
        3. Equity: Ensure accurate proportions, avoid misleading design choices, and make the data and design accessible to a broad audience.

        ```

- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:
| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
