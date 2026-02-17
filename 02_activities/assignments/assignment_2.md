# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```

GOOD VISUALIZATION
Formula 1 2024 Lap Times – Beeswarm
Link: https://public.tableau.com/app/profile/vizgrowth/viz/Formula12024LapTimesBeeswarm/Beeswarm


The Formula 1 2024 Lap Times beeswarm visualization is an effective example of good data visualization because it appropriately matches the chart type to the data and supports accurate comparison. A beeswarm plot is well-suited for displaying continuous numerical data such as lap times because it preserves the full distribution rather than aggregating results into averages. This allows viewers to see variation, clustering, and outliers across drivers. According to Cleveland and McGill (1984)*, position along a common scale is one of the most accurate perceptual tasks for interpreting quantitative differences. Because the data points are aligned along a shared axis, comparisons between lap times can be made precisely and without distortion.

The visualization also demonstrates strong use of visual encoding. Colour is used consistently to distinguish drivers or teams without overwhelming the viewer, and the layout avoids unnecessary decorative elements. This aligns with Tufte’s principle of maximizing the data-ink ratio by prioritizing meaningful information over embellishment. The clean design reduces cognitive load, allowing the viewer to focus directly on performance differences. Additionally, the spacing of points reflects Gestalt principles of proximity, making clusters and patterns easier to interpret at a glance. Overall, the scaling appears honest and proportional, avoiding exaggerated differences or truncated axes that could mislead interpretation.

*https://www.jstor.org/stable/2288400



BAD VISUALIZATION
Shining Stars – Movies Data Dashboard
Link: https://public.tableau.com/app/profile/.83057946/viz/ShiningStarsMoviesData/ShiningStarsDashboard

The Shining Stars Movies Dashboard is an example of ineffective data visualization because it attempts to communicate too many variables simultaneously without establishing a clear visual hierarchy or central insight. The dashboard analyzes the careers of over 2.4 million actors using IMDb data and attempts to measure career impact, consistency, and public memory. While the project's ambition is impressive, its execution results in cognitive overload. The viewer is presented with multiple encodings at once: star size represents the number of appearances (larger stars indicate more credits), colour represents the number of films rated 7.0 or higher on IMDb (with pink indicating fewer and blue indicating more), distance from the center represents genre diversity, and interactive summaries and timelines appear when selecting individual actors. Additionally, there is a country filter dropdown that further expands the analytical scope.

Although each metric may be meaningful independently, combining them into a single radial visualization creates interpretive strain. According to cognitive load theory, effective visualizations reduce the mental effort required to extract meaning. In this case, viewers must simultaneously decode size, colour, spatial position, and interaction mechanics before understanding what the visualization is attempting to communicate. There is no clear focal point guiding interpretation, and no headline or annotation clarifies the primary takeaway. As a result, the viewer must independently search for patterns, which weakens the dashboard’s communicative power. Because genre diversity is represented by distance from the center, comparisons between actors require estimating relative spacing rather than reading from a shared axis. Similarly, encoding the number of appearances as star size relies on area perception, which is less precise than length-based comparisons. These design choices reduce perceptual accuracy.

Colour use also presents issues. While pink-to-blue may indicate variation in highly rated films, the distribution appears skewed, with many stars appearing similar in tone, making distinctions less immediately clear. Additionally, a 7.0 IMDb rating is already relatively high, raising questions about whether this threshold meaningfully differentiates actors. Effective use of preattentive attributes, such as colour, should immediately clarify differences rather than require interpretive effort. Although a legend is present and individually clear, integrating all encodings simultaneously increases complexity rather than clarity.

      ```
    - How could this data visualization have been improved?  
      ```
GOOD VISUALIZATION
Although the visualization is strong, it could be improved by adding brief annotations that highlight key insights, such as the fastest driver or the tightest performance clusters. Including median or average markers would further support quick interpretation. Finally, ensuring a colour-blind-accessible palette would strengthen accessibility and inclusivity.


BAD VISUALIZATION

This dashboard could be improved by narrowing its analytical focus. Rather than encoding four variables in a single radial visualization, the designer could separate them into coordinated, simpler charts, such as bar or scatter plots, using shared linear axes. Reducing the number of visual encodings would improve perceptual accuracy and lower cognitive load. A clear headline stating the primary insight, such as whether career longevity correlates with genre diversity or critical success, would strengthen narrative direction. Simplifying the colour scheme and reconsidering whether all four metrics are equally meaningful would transform the dashboard from a visually dense display into a more purposeful and interpretable communication tool.

      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
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
* Submission Due Date: `23:59 - 02/16/2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
