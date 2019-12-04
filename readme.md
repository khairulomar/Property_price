Module 1 project - DS111819

Team members:
1. Khairul Omar
2. Aleksandar Gakovic

Executive summary:

We're taking the position of a real estate agency to advice prospective sellers in setting the right asking price, and to prospective buyers to gauge if an asking price is a good deal for a given area.

Specifically, we are looking to answer the following questions:

1. What are the main drivers that contribute to property prices in King County?
2. Could property prices in King County be reliably predicted?
3. Which areas in King County can be considered as premium locations?

High-level overview of methodology:

1. Discuss the direction of project and key questions to be addressed.
1. Initial data exploration, data cleansing and agree on assumptions.
2. Detailed analysis of data to identify potential drivers for price.
3. Create new derived fields from raw data to further help the analysis.
4. Subset data into categories where applicable.
5. Select key drivers for the model and further scrutinise them.
6. Run first regression model with a single (primary) variable.
7. Analyse first regression model for improvements.
8. Run second regression model with multiple variables.
9. Analyse second regression model for improvements.
10. Repeat multiple variable model using different combinations of variables.
11. Decide on final variable combination that gives the best r2.
12. Refine model by exploring normalisation of variables and retest.
13. Finalise model reliability via various statistical measures.

Key findings and conclusions:

Our model shows that the primary driver for property prices in King County is the square footage of the living space. Property prices are also highly impacted by its location in the city (derived from zipcode): in particular, properties in premium areas in and near the city have higher prices than it outer suburbs. Building grade as set by the county authority is also another factor as higher grade properties are in better condition and thus can fetch a higher. Finally in our model, waterfront view is another factor that pushes the property price up due to the prime views.

With an r-squared value of 0.702 for our model, we conclude that the property price in King County can be reasonably predicted. However, we are confident that the model can be further refined if more data is available. As our model factors in the impact of the location, additional area information (for example, by zipcode) such the number of schools, public transportation and crime rate would be very useful. We believe that the high property prices in the premium areas of the city are partly driven by these factors.

We worked on the assumption that areas with significantly higher price per square feet (of living space) than the overall county constitute as premium locations. Cross-referencing our findings with a zipcode map (link here), we noted that Medina (zipcode 98039) is most premium location in King County, driven by its proximity to the city centre and great waterfront views facing Lake Washington. In addition, zipcodes around Belleview and downtown Seattle are also identified as premium locations.

With these results, we are confident that we would be able to serve our clients better in advising them on the right price for both selling and buying.

Task delegations:

Data cleansing: Khairul & Alek
Data exploration: Khairul & Alek
Data subsetting: Khairul
Deciding variables for model: Khairul & Alek
Single variable regression model: Khairul
Multiple variables regression mode: Khairul
Fine-tuning regression models: Khairul & Alek
Formalising Jupiter notebook: Khairul
Presentation slides: Khairul & Alek

