Economic Efficiency of TIF Districts

_Khushin Patel, Mehal Gosalia, Rajdeep Singh Konthoujam, Parth Patel, Ezekiel Oldham_

# **Abstract**

A TIF district is an effective tool that may help a community with a variety of challenges. It is frequently used to promote development, get rid of blight, deal with environmental problems, and make adaptive reuse easier. TIF finances development-related expenses by utilizing the higher sales and/or property taxes produced by a new development. Public infrastructure, property acquisition, relocation, demolition, utilities, debt payment, and planning expenses are a few examples of these expenditures. Economic efficiency of businesses vary from year to year. A just, easily accessible, and efficient distribution of products and services across society is made possible by an efficient economy. By utilizing all resources in a productive and effective manner, these circumstances allow firms to minimize or completely eradicate waste. An economy's capacity to boost efficiency is influenced by a number of variables, such as customer behavior, the accessibility of products and services, and standard economic production methods.

# **Objective**

Our main aim for the project was to find an accurate dataset which show all businesses mainly based in Chicago, and also those that were present inside the TIF districts. We used the following dataset for our project - [CHICAGO BUSINESS LICENSES](https://data.cityofchicago.org/Community-Economic-Development/Business-Licenses/r5kz-chrr/about_data). After finding our dataset, our focus shifted to comparing the economic impact of TIF districts of the area when they are created. Compare the economics of TIFs versus other TIFs and also compare how well economies are doing inside TIFs versus outside. We also focused on discovering the economic advantage or disadvantage of TIF district and the effect that TIFs have on businesses.

We used this dataset to analyze how many businesses are created or closed before and after the creation of a TIF district. Also, used it to compare the TIF district to surrounding areas. Our first stepping stone was cleaning the data as it went all the way back to the 90’s. The above dataset included business that were out of Chicago and also included multiple attributes which seemed irrelevant for our project.

# **Methodology**

In our study of the impact of Tax Increment Financing (TIF) districts on business activities in Chicago, we encountered initial data challenges with the Chicago Business Licenses Dataset. This dataset did not specify whether each business license was located within a TIF district, nor did it identify the specific TIF district applicable to each business. Additionally, some entries in the dataset were missing crucial geospatial data, specifically longitude and latitude coordinates, which are essential for precise geographic analysis. To address these gaps, our first step involved geocoding the business addresses to assign longitude and latitude values to the licenses lacking this information. Subsequently, we developed a custom function designed to map each business license to its corresponding TIF district. This function utilized the newly acquired geospatial coordinates to accurately associate businesses with their respective TIF districts, thereby enabling a more detailed and location-specific analysis of the economic effects of TIFs on businesses within these designated areas. This preparatory work was crucial for ensuring the reliability and accuracy of our subsequent analyses.

We then continued our project by splitting our data into the following categories:  
\- By business size

\- By business type

# **Categorizing businesses according to business size**

Within the economic framework, separating franchises from local stores requires the classification of firms based on size. The basis for this classification is the frequency with which a company's name occurs in a dataset. Three business categories—small, medium, and large—were used in a recent research.

Small firms are defined as those whose names occur in the dataset one to eight times. The core of local business is highlighted by this categorization, which is often shown by one or a small number of locations. A strong ecosystem of small-scale firms that support the resilience and variety of the regional economy is indicated by the study's identification of 363,635 small businesses.

The medium-sized business names, ranging from nine to twenty-three, indicate a potential stage of development and potential regional expansion. There are 354,486 businesses in this group according to the poll, indicating that they are neither large-scale companies nor small-scale enterprises. This compromise is necessary in the commercial climate.

The names of 315,495 notable companies are included in the collection; their average frequency of occurrence ranges from 24 to 3,386. They often represent the wide variety of scales observed in this category, from well-known domestic chains to international franchises, as they are well-known firms or franchises with numerous sites.

By categorizing businesses into these groups based on how often their names appear, the study effectively distinguishes between franchise sites, with their broad reach and numerous outlets, and locally managed establishments, which often serve as the cornerstone of community-focused commerce. Studying the business environment requires an in-depth understanding of market dynamics and operational scales across several industries, which is what this stratification offers.

Businesses outside a TIF:

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/BusOutTIF.png?raw=true)

Small companies are the most closely spaced; they make up a larger percentage of firms with fewer locations overall. On the other hand, compared to their smaller counterparts, medium-sized firms are less densely populated, consisting of fewer companies but more locations. Big enterprises have the lowest density, with comparatively fewer entities, but each one typically has many sites. Small companies often have a wider footprint since they are more equally dispersed throughout different communities. Large and medium-sized enterprises, on the other hand, exhibit more clustering, indicating economic tactics that leverage particular locations to improve market awareness. Large corporations tend to concentrate in specific places as a result of deliberate decisions, probably influenced by local demographics, strong foot traffic, and accessibility.

Businesses inside a TIF:

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/BusInTIF.png?raw=true)

The tiny business map, which shows a large number of businesses operating in a small number of locations, has the highest saturation and densest point population. Large companies have the least amount of saturation, indicating fewer businesses but maybe larger individual footprints; in contrast, medium-sized companies exhibit a moderate level of density and saturation. The color coding on each map suggests that there is more classification than just size, maybe according to the type of business or sector. The way the colors are distributed differently throughout the maps may represent how different business sizes range from little to massive. Each map shows a different geographic pattern based on the size of the businesses: Medium-sized businesses start to group together, while large businesses are placed thoughtfully around the city.

After making these graphs, we realized it was not the best idea to go forward with it as the way we split the data was by frequency, and it wasn’t exactly the best way to distinguish large businesses. Hence, there wouldn’t have been any conclusion on how business licenses for each TIF district differ over the years.

## **Splitting by chains**

A comprehensive list of every chain company in Chicago was hand-compiled in an attempt to gain a complete understanding of the city's commercial environment. Based on their brand awareness and operational reach, national and local chain enterprises were included in this comprehensive compilation. Every national chain that is known to exist and is present in Chicago was identified; this process required a great deal of searching through several company directories and painstaking cross-referencing to guarantee correctness and comprehensiveness.

Businesses outside a TIF:  
![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/BusOutTIF1.png?raw=true)

Businesses inside a TIF:

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/BusInTIF1.png?raw=true)

On the other hand, the local chains were distinguished not by a nationwide presence but by their importance inside the city or region. Every local chain, spanning many sectors, was painstakingly listed by name. Furthermore, a frequency study of the most common corporations in Chicago was carried out, with the companies being categorized based on the number of sites and size of their activities. This detailed analysis clarifies Chicago's dynamic economic climate in addition to highlighting the spread of chain stores. The following bar graph illustrate the same -




The graph is showing us the active number of businesses every year at Little Village Industrial Corridor. The data spans from 2000-2023. The businesses are categorized into three distinct types of businesses:  
\- Non-chain businesses (indicated by blue bars)

\- Local chains (green bars)

\- National chains (red bars).

The y-axis quantifies the number of active businesses, while the x-axis represents consecutive years.

A red line around the year 2008 signifies the creation of a Tax Increment Financing (TIF) district. The two dashed lines indicate the creation of TIF projects. The graph below shows us the active number of businesses around the TIF district, basically in the community areas.

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/Combar.png?raw=true)

We can conclude the following by comparing these two graphs:

- Before the creation of the TIF we did not see any significant change in the number of licenses, but after the creation of the TIF we see there was an increase in the number of businesses.
- However there was an increase in the number of licenses in the surrounding community areas as well, so we can not attribute the change to the TIF but the area's economy was having a boom.
- We also see here the the TIF projects did not affect the trend in businesses before their creation, So like the project indicated by the orange line, there was a trend downward, and that trend continued downward after the creation of the project. This downward trend was in the community areas as well.

**Categorizing businesses according to business type**

The tight categorization of business licenses into groups based on the kind and size of each organization was one of the key elements of the methodology used to analyze the business landscape. The objective was to separate smaller, individually owned businesses from bigger global corporations. Sorting these businesses into different categories can help you understand their various impacts on the local economy and create appropriate strategies to address them. To achieve this, a range of generic licensing categories were created using the descriptive information found in each company's business license.

Nonetheless, there were a lot of difficulties with the categorization procedure. The information comprised incredibly detailed and particular descriptions of every company, thus precise classification required a sophisticated grasp of the regional business environment. Owing to the intricate and particular nature of the information, no automated method could consistently classify the companies according to their thorough descriptions and operations. Because of this, the procedure could not be effectively processed or algorithmic using conventional data sorting methods. The companies were split up into 14 distinct licensing groups in order to handle this. Similarities in business operations and legal frameworks served as a basis for these groups' establishment, allowing for the development of a coherent structure that encapsulates each company's essential function within the economy.

After splitting it into license groups, we created a csv file where we split the data into the 14 license groups showing the percentages of each business in each of the TIF districts. We then formed 14 different heatmaps for the same, basically showing how much of a TIF is made in that business and how scattered each business is. The heatmaps are as follows:

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/map1.png?raw=true)
![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/map2.png?raw=true)
![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/map3.png?raw=true)
![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/map4.png?raw=true)

# **Principal Component Analysis**

We want to understand whether or not TIF districts have an impact on the distribution of business license types. Or in other words, whether or not the distribution of business license types within TIF districts differs from that of areas outside of TIF districts. Further, we want to visualize the similarities and/or differences. However, there are 14 business license types that we have identified, over 130 TIF districts, and over 70 non-TIF regions (grouped by community areas). The sheer amount of data presents a challenge for visualization. Principal Component Analysis (PCA) can be used to visualize high dimensional data in lower dimensions while maintaining as much visual information as possible.

## _PCA of Business License Types in TIF Districts_

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/PCA1.png?raw=true)

_PCA of Business License Types in Non-TIF Regions_

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/PCA2.png?raw=true)

## _PCA of Business License Types in TIF and Non-TIF Regions_

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/PCA3.png?raw=true)

There seems to be a small right-shift of the Non-TIF areas in the distribution, along principal component 0. The difference of sample means of the principal component 0 values between TIF and non-TIF areas is -0.1166, with 95% confidence interval \[-0.1498, -0.0834\]. Thus there is high confidence that the mean of principal component 1 values of TIFs is slightly less than non-TIF areas. This is largely due to TIFs having a higher business license value compared to non-TIF areas.

### _Explained Variance of Principal Component (Merged)_

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/PCA4.png?raw=true)

\* Variance explained by principal component 0 and 1 = 0.780242227372013

### _Principal Component 0 Values_

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/PCA5.png?raw=true)

### _Principal Component 1 Values_

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/PCA6.png?raw=true)

#

# **Difference of Means (TIF Districts vs Non-TIF Areas) Analysis Across License Types**

**Difference of Means**: Mean of percent of license types in TIF areas minus that of non-TIF areas.

**95% Confidence Interval**: of the value of the difference of means, bounds rounded to 4 digits.

**1 - p-value (One-Sided)**: Confidence in rejecting the null hypothesis that difference of means is greater/less than zero.

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/stats.png?raw=true)

**Businesses By Investments**

We did an analysis on the TIFs by the amount of property taxes extracted in a year, and the percent change of licenses over the previous year.

![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/lines.png?raw=true)

As we see in this graph, the high investment TIFs(green line), and the medium investment TIFs(red line) follow a similar pattern to the non-TIF areas of Chicago(blue line). This means that the TIFs did not see any difference in their businesses licenses no matter the amount of investments made into them. The low investment TIFs(pink line) see a high volatility since they are TIFs with smaller areas, and therefore less businesses. This means that a small change in businesses was affecting their percentages by a big margin.

Since TIFs are following the same pattern as areas without the TIF help, as analyzed by the Chain/Non-chain analysis, PCA, and the investment analysis, we can conclude that TIFs do not affect the businesses within a TIF.

**Implementation and Analysis**

- Deepnote, a collaborative data science platform, has been used to execute our extensive analytical project. It combines several potent technologies, including SQL, GeoPandas, Python, and PCA, to analyze and display complicated datasets.
- The 'Community Business Distributions' notebook, which acts as the center of our investigations, is accessible within our project area.
- This notebook includes a detailed codebase that allows for the dynamic generation of graphs depicting the number of active businesses per year in various Tax Increment Financing (TIF) districts and their adjacent community areas. For those interested in customizing the analysis, the code is adaptable to your specific interests.
- By navigating to line 75, you can modify the function call to plot_active_businesses_by_year_by_tif('TIF district of your choice'), substituting 'TIF district of your choice' with the name of the TIF district you wish to explore. This feature enables personalized exploration of business trends across different TIF districts, directly within [Deepnote](https://deepnote.com/workspace/CS%20584%20Final%20Project-956fc710-abb9-4dcf-8654-2f1ab73b4e09/project/Khushin-Patels-Untitled-project-41bd1eeb-8ade-41a5-ae81-cf4a88f38197/notebook/PCA%20Plots-6b5051edcbfb46a8a297e53e66bcbd8f).


