# Peace Corps Response Volunteer Living Conditions Analysis in Iquitos, Peru

## Organizational Value Contributed

* **Expert Analytical Skills:**   Demonstrated advanced expertise in processing and analyzing large, unstructured datasets in Spanish, effectively translating them into insightful, actionable information in English. Utilized a combination of statistical analysis and visual data representation techniques to distill complex data into clear, comprehensible findings.
* **Innovative Data-Driven Approach:**  Innovatively applied data-driven methods to analyze volunteer stipends, likely being the first to approach this issue with such rigor. This strategy compelled the administration to corroborate practices with empirical data, moving beyond outdated methodologies.
* **Enhanced Decision-Making for Peace Corps:**  Provided key insights for the Peace Corps administration, leading to a reevaluation of stipend allocations and housing policies. This work helps prevent potential exploitation due to policy negligence, aligning policy implementation with the organization’s responsibility to volunteers as mandated by US Charter Code and MS Policy.
* **Strong Advocacy for Volunteer Rights:** Empowered by data, effectively advocated for volunteer rights by presenting findings to the Senate and communicating with high-level Peace Corps directors. This initiative demonstrated exceptional communication, leadership, and persuasive skills.
* **Critical Policy Insights:** Uncovered significant discrepancies in stipends and living conditions, leading to crucial policy recommendations. This analysis directly influenced the adjustment of stipends and the enhancement of living conditions, significantly impacting the well-being of current and future volunteers.
* **Foundation for Future Research:** Established a comprehensive repository and methodological framework for ongoing and future analyses, setting a new standard for data-driven decision-making within volunteer organizations.

## Summary
As a Peace Corps Response Volunteer in Peru, I found a large discrepancy between my living conditions promised and those accessible. My realization occurred after investing my savings in this opportunity for my career and after arriving to Peru under a legal status administered by the Peace Corps that denies me the right to work here. Unfortunately, the data corroborates that I was exploited and the living stipend is incompatible with a middle class lifestyle in Iquitos if the Peace Corps' strict lifestyle policies are followed. These are portions of the review of economic data in Iquitos, Peru. This reporting served as the foundation to my formal written testimony to Senate and communications with the Director of the Peace Corps, Intra-American Pacific Regional Director, and the Director of Peace Corps Response after months of communication with administration in Lima with no additional support offered.

### Overview
The data tells a story of extreme negligence. Geographic comparison shows demoralizing inequitable treatment of Response Volunteers living independently in Iquitos to two year Volunteers living comuunally in small villages.
Compounding upon the injustice, prior to a recent raise, Response Volunteers in Huaraz recieved 365/s in locality supplement and those in Lima recieved a staggering ~1000/s while volunteers in Iquitos recieved 165/s. The economic data shows Iquitos is a more expensive local than Huaraz. Living costs in Iquitos are on par with those in Lima if you disregard affluent areas of the city (a reasonable approach considering Peace Corps volunteers are supposed to engage in cultural integration and living modest local lifestyles). A recent raise was the final blow to my spirit as Volunteers recieved a raise in Huarazo 340/s, Lima 669/s, and Iquitos 439/s. For the remainder of my service, 180/s of my raise monthly will be used to pay back administraion for fridge and stove money I used on food. Leaving me yet again with no recourse to eat more than 1 meal a day or get to work more than 3 out of 4 weeks in the month and unable to leave my house otherwise. I am in the process of evaluating the other economic sectors, however I hope to have found alternative recourse of action prior.

### Data
_All monetary amounts in the repository are Peruvian Soles (PEN) unless otherwise specified._

[All data can be accessed here.](https://proyectos.inei.gob.pe/microdatos/Consulta_por_Encuesta.asp)

The data was published by the Instituto Nacional de Estadística e Informática (National Institute of Statistical Information); an insitution of the Peruvian Federal Government. It was published as a part of Encuesta Nacional de Hogares (Survey of Households). This census is an ongoing initiative that publishes data trimesterally about and offers extensive and detailed insight into living conditions and expenses in relation to local and amny other variables. 

In the data base you can use the drop-downs and select trimesters 1, 2, and 3 of 2023 individually. 

* Housing Data: "Condiciones de Vida y Pobreza - ENAHO | Caracteristicas de la Vivienda y del Hogar"
* Food Costs: "	Condiciones de Vida y Pobreza - ENAHO | Gastos en Alimentos y Bebidas (Módulo 601)"

### Methodology
* **Housing Analysis (housing.ipynb)**
  * In the housing analysis, I utilized descriptive statistics and comparative analysis, leveraging the detailed insights from the ENAHO survey about housing conditions and correlated costs. This approach was particularly beneficial as Peace Corps regulations have specific requirements regarding housing material, security measures, utility access, and more. By analyzing the actual costs associated with these conditions as reported in the ENAHO survey, I was able to provide a more accurate assessment of housing costs compared to remote evaluations by staff in Lima, which lack detailed information about the costs tied to these requirements.
  * The key finding is that upon my arrival, the initial housing stipend of 600/s was inadequate for Response volunteers to secure accommodations that met the safety standards set by Lima. After a subsequent increase in the housing budget to 900/s, it became sufficient given the current housing prices. However, considering the seasonal nature of placements, I advocate for future volunteers to receive additional support to accommodate market availability fluctuations, or for procedures allowing expedited relocation post-arrival to the site.

* **Food and Beverage Expenses Analysis (Iquitos2023food_beverage.ipynb)**
  * For the analysis of food and beverage expenses, I employed a detailed methodological approach. This began with the organization of thousands of unstructured entries for various food items into a structured dataset. Following this, I conducted a geographical comparison to underscore the disparities in living costs across different locations. The analysis combined statistical methods with visual data representations, facilitating a comprehensive understanding of the living cost variations. By focusing on the geographic locations of current volunteers, this analysis effectively highlights the inequity in volunteer treatment, illustrating how the purchasing power of a sole in different living environments (communal versus independent | village versus city) impacts volunteer experiences. In the 

### Repo & Files

Within the repository you can find:
* "housing.ipynb"- Analysis of the housing data. Here I focused on housing conditions and the costs associated with types of housing. The Peace Corps has strict regulations regarding housing.
* "food_drink"- folder
  - "Iquitos2023food_beverage.ipyb"- Analysis of food and beverage expenses. Within this analysis of the food and beverage allowance, geographical comparison highlights the discrepancies in living costs amongst locals.
  - "food_categories.csv"- The survey data had thousands of unformatted entries for different food items. Iteratively, I sorted each entry or item into this csv to structure the categories of food items for further analysis.
  - "ubigeo_codes.csv"- Geogaphic information columns with rows of zip code where other Volunteers are present. This allowed me to filter the data, analyze sample distribution, and append lat and long.
 
### Future Work

This project opens several avenues for further research and analysis:

1. **Comparative Analysis with Other Volunteer Programs:** Analyzing how the living conditions and stipends of Peace Corps volunteers compare with those of volunteers from other international organizations could offer a broader context to these findings.
2. **Long-term Economic Trends:** Examining the long-term trends in living costs in these areas could be valuable, especially in understanding how sustainable the current stipend model is.
3. **Impact Assessment on Volunteer Well-being and Effectiveness:** Conducting a study on how these financial challenges impact the well-being and effectiveness of volunteers could provide critical insights for policy and decision-making.
4. **Policy Review and Recommendations:** Based on the findings, developing a set of policy recommendations to address these challenges could be a valuable contribution to the Peace Corps and similar organizations.
