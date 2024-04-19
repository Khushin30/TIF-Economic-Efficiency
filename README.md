Economic Efficiency of TIF Districts

_Mehal Gosalia, Rajdeep Singh Konthoujam, Khushin Patel, Parth Patel, Ezekiel Oldham_

Abstract

A TIF district is an effective tool that may help a community with a variety of challenges. It is frequently used to promote development, get rid of blight, deal with environmental problems, and make adaptive reuse easier. TIF finances development-related expenses by utilizing the higher sales and/or property taxes produced by a new development. Public infrastructure, property acquisition, relocation, demolition, utilities, debt payment, and planning expenses are a few examples of these expenditures. Economic efficiency of businesses vary from year to year. A just, easily accessible, and efficient distribution of products and services across society is made possible by an efficient economy. By utilizing all resources in a productive and effective manner, these circumstances allow firms to minimize or completely eradicate waste. An economy's capacity to boost efficiency is influenced by a number of variables, such as customer behavior, the accessibility of products and services, and standard economic production methods.

Objective

Our main aim for the project was to find an accurate dataset which show all business mainly based in Chicago, and also those that were present inside the TIF districts. We used the following dataset for our project - [CHICAGO BUSINESS LICENSES](https://data.cityofchicago.org/Community-Economic-Development/Business-Licenses/r5kz-chrr/about_data). After finding our dataset, our focus shifted to comparing the economic impact of TIF districts of the area when they are created. Compare the economics of TIFs versus other TIFs and also compare how well economies are doing inside TIFs versus outside. We also focused on discovering the economic advantage or disadvantage of TIF district and the effect that TIFs have on businesses.

We used this dataset to analyze how many businesses are created or closed before and after the creation of a TIF district. Also, used it to compare the TIF district to surrounding areas. Our first stepping stone was cleaning the data as it went all the way back to the 90’s. The above dataset included business that were out of Chicago and also included multiple attributes which seemed irrelevant for our project.

Methodology

In our study of the impact of Tax Increment Financing (TIF) districts on business activities in Chicago, we encountered initial data challenges with the Chicago Business Licenses Dataset. This dataset did not specify whether each business license was located within a TIF district, nor did it identify the specific TIF district applicable to each business. Additionally, some entries in the dataset were missing crucial geospatial data, specifically longitude and latitude coordinates, which are essential for precise geographic analysis. To address these gaps, our first step involved geocoding the business addresses to assign longitude and latitude values to the licenses lacking this information. Subsequently, we developed a custom function designed to map each business license to its corresponding TIF district. This function utilized the newly acquired geospatial coordinates to accurately associate businesses with their respective TIF districts, thereby enabling a more detailed and location-specific analysis of the economic effects of TIFs on businesses within these designated areas. This preparatory work was crucial for ensuring the reliability and accuracy of our subsequent analyses.

We then continued our project by splitting our data into the following categories:  
\- By business size

\- By business type

_Categorizing businesses according to business size_

The classification of businesses by size plays a pivotal role in distinguishing between franchises and local shops within the economic landscape. This categorization process is underpinned by the frequency of business name occurrences within the dataset. In our study, businesses were segmented into three distinct categories: small, medium, and large.

Small businesses are identified by the occurrence of their names in the dataset between one and eight times. This classification captures the essence of local commerce, typically characterized by a single or a small number of outlets. Our results indicate a significant presence of small businesses, with 363,635 such entities identified. This high number suggests a vibrant ecosystem of small-scale enterprises contributing to the diversity and resilience of the local economy.

Medium-sized businesses, with name occurrences ranging from nine to twenty-three, are indicative of a growing presence and possibly regional expansion. Our data revealed that there are 354,486 businesses in this category. These businesses are likely to be those that have outgrown the "small" label but have not yet reached the "large" scale, representing a critical middle ground within the business environment.

The large business category is reserved for names that appear 24 to 3,386 times in the dataset, totaling 315,495 entries. These are indicative of well-established corporations or franchises with multiple locations. The wide range of occurrence counts within this category underscores the considerable size variation among large businesses, encompassing both prominent national chains and global franchises.

By assigning businesses to these categories based on the frequency of their name occurrences, we effectively separate the franchise locations, with their extensive reach and numerous outlets, from the locally operated shops that often serve as the bedrock of community-focused commerce. This stratification is essential for analyzing the business landscape, allowing for a nuanced understanding of market dynamics and the varying scales of operation within different sectors of the economy.

Businesses outside a TIF:



Small businesses are the most densely packed, indicating a larger number of businesses with fewer locations. Medium businesses are less dense, with fewer total businesses that have more locations than small businesses. Big businesses have the least density, with significantly fewer total businesses but many locations for each. Small businesses are more evenly distributed, reflecting their presence in various neighborhoods. Medium and big businesses show more clustering, which may reflect economic strategies that leverage location for market presence. The concentration of big businesses in particular areas implies a strategic choice, likely based on factors like high foot traffic, accessibility, and the demographic profile of neighborhoods.

Businesses inside a TIF:



The small businesses map is the most saturated and densely populated with points, indicating a large number of businesses with fewer locations each. Medium businesses have a moderate level of saturation and density, while big businesses have the least, suggesting fewer businesses but possibly with more significant individual footprints. All maps are color-coded, which implies a classification beyond just size—perhaps industry type or nature of business. The variation in color distribution across the maps could reflect how different types of businesses scale from small to big. Each map presents a distinct spatial pattern that corresponds to the size of the businesses. Small businesses are widespread, medium businesses begin to show clusters, and big businesses exhibit strategic placement within the city.

_Categorizing businesses into Chains/Local Chains/Not part of Chains_

_Categorizing businesses according to business type_

A rigorous process of classifying business licenses into groups that correspond to the size and kind of each organization was part of our approach for analyzing the business landscape. The idea was to keep smaller, independently run businesses apart from bigger corporate conglomerates. Understanding the various effects these companies have on the local economy and developing relevant governmental responses depend on this segmentation. In order to do this, we classified each business into a number of generic licensing categories using the descriptive information contained in the business licenses.  
<br/>However, the classification process presented significant challenges. The dataset contained highly specific and granular descriptions for each business, which required a nuanced understanding of the local commercial ecosystem to ensure accurate categorization. Given the complexity and specificity of the data, there was no automated system capable of reliably grouping the businesses based on their detailed descriptions and activities. Consequently, the process could not be efficiently algorithmized or processed through standard data sorting techniques. To overcome this, we split the businesses into 14 different license groups. . The establishment of these groups was informed by commonalities in business activities and regulatory frameworks, allowing us to create a cohesive structure that captures the essence of each business's role within the economy.

Principal Component Analysis

Results

https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/BusOutTIF.png?raw=true
https://raw.githubusercontent.com/Khushin30/TIF-Economic-Efficiency/main/BusOutTIF.png



![alt text](https://github.com/Khushin30/TIF-Economic-Efficiency/blob/main/BusOutTIF.png?raw=true)
