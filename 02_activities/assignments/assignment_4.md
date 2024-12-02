# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
    
    I used Python (Matplotlib and Seaborn libraries) and Tableau Public to create my visualizations; Python for data cleaning, preparation, and creating the first visualization. Python offers flexibility and precision, which is essential for handling and visualizing complex datasets like crime data. Tableau for the second visualization to create an interactive map of crime occurrences across Toronto. Tableau is particularly powerful for dynamic visualizations and geographic data representation.

    > Who is your intended audience? 
    
    My primary audience consists of urban planners, policymakers, law enforcement agencies, and community organizations in Toronto. This visualization will help them understand crime trends and make informed decisions related to public safety and resource allocation.

    > What information or message are you trying to convey with your visualization? 

    The primary message of my visualizations is to highlight trends in crime across different neighborhoods and over time, helping stakeholders identify areas that need more attention, intervention, or resources. The second visualization, an interactive map, specifically aims to show the distribution of crime types across Toronto’s neighborhoods, facilitating targeted crime prevention strategies.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    
    Substantive 
    - I chose to focus on the crime categories (e.g., violent crimes, property crimes) and geographical distribution to ensure the visualizations are aligned with the audience's objectives of understanding crime patterns. For the time series plot, I focused on year-over-year crime trends to illustrate patterns of crime reduction or increase.

    Perceptual 
    - Color: In the map, I used a color gradient (lighter to darker shades) to represent crime density, making it easy for users to visually differentiate high-crime areas from low-crime ones. For the time series plot, I used contrasting colors for different crime categories to improve clarity
    - Scale and Layout: In the time series plot, I kept the x-axis simple with consistent time intervals to facilitate comparison over the years. In the map, I used proportional symbols and heatmaps to ensure that users could easily spot regions with higher crime rates.

    Aesthetic
    - I kept the design clean and minimalistic, with no extraneous elements. In Tableau, I used large icons to represent crime types on the map, ensuring they were both informative and visually appealing. The time series plot in Python followed a simple yet professional design with clear labels and gridlines for ease of interpretation.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    To ensure reproducibility I wrote clean, modular code with clear comments and used well-documented libraries (Matplotlib and Seaborn) to create the plot. The code is available in a GitHub repository, and I’ve ensured that all external dependencies are included in a requirements file. I also used Tableau which offers less flexibility in code but allows me to save the workbook and data, which are publicly available via Tableau Public. The visualization can be updated dynamically with new data by simply uploading an updated version of the dataset.
    
    > How did you ensure that your data visualization is accessible?  
    
    I took several steps to ensure that my visualizations are accessible. In Python, I used color palettes that are specifically designed to be colorblind-friendly (e.g., ColorBrewer), making sure that individuals with color vision deficiencies can still interpret the visual data. I also ensured that the charts had clear labels, axis titles, and annotations to guide the viewer’s understanding. In Tableau, I focused on creating an interactive map with intuitive filtering options so that users can explore the data at their own pace, adjusting for time periods or crime types. Additionally, I incorporated large font sizes, high contrast colors, and a straightforward layout to improve legibility and usability for individuals with visual impairments.
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    The individuals and communities most impacted by these visualizations are the residents of Toronto, especially those living in areas with high crime rates. These visualizations can help them understand the safety landscape of their neighborhoods and make informed decisions about their daily lives. Law enforcement agencies and policymakers can use the data to better allocate resources, design crime prevention programs, and evaluate the success of current safety strategies. Non-profit organizations focused on crime prevention, housing, or social services may also find these visualizations useful in advocating for resources or policy changes in areas affected by high crime rates.
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    In designing my visualizations, I carefully selected the most relevant features of the dataset. For the time series plot, I chose to focus on the number of incidents per year for key crime types, which allowed me to illustrate trends over time without overwhelming the viewer with excessive details. I excluded very granular data, such as individual incident records, as this would make the visualization too detailed and less effective for the intended audience. In the Tableau map, I included geographic data related to neighborhood locations, crime types, and crime counts, ensuring the visualization remained focused on presenting clear and actionable insights. I excluded extraneous data, such as arrest information or specific case details, to keep the map focused and readable.

    > What ‘underwater labour’ contributed to your final data visualization product?

    The creation of these visualizations involved substantial "underwater labor," especially in terms of data cleaning and preparation. In Python, I used pandas to handle missing values, convert date formats, and filter out irrelevant columns. I also needed to normalize crime types, ensuring consistency across different datasets. This was a time-consuming process that required careful attention to detail to avoid errors that could compromise the accuracy of the visualizations. In Tableau, I spent time creating calculated fields, adjusting filters, and fine-tuning the map's interactivity. Additionally, I worked to ensure that the map was both functional and aesthetically pleasing, which involved adjusting color schemes and the design of interactive features.

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
