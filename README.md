# Pymaceuticals, Inc.

### Background

You've just joined Pymaceuticals, Inc., a new pharmaceutical company that specializes in anti-cancer medications. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

The executive team has tasked you with generating all of the tables and figures needed for the technical report of the clinical study. They have also asked you for a top-level summary of the study results.



### Analysis

Given the most recent data, the drug of interest, Capomulin, has shown great promise. When compared to it's counterparts, Capomulin stands to be one of the top drugs of choice. However, Ramicane also proves to be as effective as Capomulin, with a possibility of being even more effective. When comparinng Capomulin and Ramicane, Ramicane's tumor statistics show a slight advantage over Capomulin with a Mean Tumor Volume: 40.217 and a Tumor Volume Standard Deviation: 4.846 as opposed to Capomulin's Mean Tumor Volume: 40.676 and Tumor Volume Standard Deviation: 4.994. This is indicative of how large the average tumor volume resulted in over time for each mice and its relativity to the meann tumor volume. Both Capomulin and Ramicane show very similar results, but Ramicane leading just slightly in these statistical tests.

Based on Figure 2, the gender or sex of a mice may not necessarily factor into tumor volume. A closer look into the correlation between tumor volume and sex/gender would need to be considered before making a definitive conclusion.

However, based on Figure 5, there is a strong correlation between tumor volume and mice weight. With an r-value of 0.84, it is very likely to be considered a strong, positive correlation between both factors.



### Summary Statistics

![summary statistics](https://user-images.githubusercontent.com/120594187/216162514-e916330d-9794-45f6-b804-f5552ad3ab48.jpg)



### Figure 1. Number of Mice Tested per Drug Regimen

![Mice Tested Per Drug](https://user-images.githubusercontent.com/120594187/216162716-90852799-c4c0-4fe3-b303-2de41b2bc6d5.jpg)



### Figure 2. Distribution of Female vs Male Mice

![Distribution of Female v Male Mice](https://user-images.githubusercontent.com/120594187/216163041-b02885e7-7edc-46fc-b9d9-95257a921899.jpg)


### Figure 3. Final Tumor Volume (mm3) for Each Mice for the Most Promising Treatment Regimens

![quartiles outliers and boxplots](https://user-images.githubusercontent.com/120594187/216163309-412dd629-777b-4845-9584-38545b6a5994.jpg)


![Box plot final tumor volume for drug regimen](https://user-images.githubusercontent.com/120594187/216163339-afbb9214-ff66-49ca-9aa8-1be8a6085574.jpg)


### Figure 4. Capomulin Treatment for Mouse ID: r157

![Capomulin treatment for specific mice](https://user-images.githubusercontent.com/120594187/216163441-3d32d4ce-a1bb-44e8-8957-a754452693f8.jpg)


### Figure 5. Capomulin Drug Regimen: Tumor Volume vs Mouse Weight

![tumor vol vs mouse weight](https://user-images.githubusercontent.com/120594187/216163629-659aca05-c51a-4e8a-a2be-be54bd6b5095.jpg)
