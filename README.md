# How does winter temperature affect electricity consumption patterns compared to summer temperatures?

Date: 03/11/2024

# Background

Temperature and Electricity Consumption: The relationship between temperature and electricity consumption is a wellstudied phenomenon1. Research has shown that electricity consumption tends to follow a well u-shaped curve with respect to temperature. This means both extremely high and low temperature leads to increased electricity use.
Winter: During colder months, electricity consumption rises due to the increased use of     heating systems. In regions with harsh winters, heating demands can significantly drive-up electricity usage.
Summer: Conversely, in the summer, higher temperatures lead to greater use of air                conditioning and cooling systems, which also increases electricity consumption
Studies have identified a critical temperature point around 14.6°C. Below this temperature, electricity consumption increases due to heating needs, and above this temperature, it        increases due to cooling needs.
The impact of temperature on electricity consumption can vary by region. Urban and              industrial areas often have higher consumption due to greater energy needs. 
Climate change can exacerbate this relationship, particularly in regions already facing          electricity deficits. For example, a 1°C increase in temperature can significantly increase electricity demand in some areas.
Understanding this relationship is crucial for energy policy and infrastructure planning. It helps in designing strategies to manage peak demand periods and ensure a reliable electricity supply. Additionally, promoting energy efficiency measures can mitigate the impact of temperature fluctuations on electricity consumption.


# Research questions

How do winter and summer temperatures affect electricity consumption differently of nine different regions in Alberta?


# Data

How do winter and summer temperatures affect electricity consumption differently of nine different regions in Alberta?

## Area Focus and selected Regions

This analysis was conducted focusing on the Province of Alberta as a study Area. 9 regions with their respective Numbers were selected for the analysis as follows:

    •	Lethbridge (South) – 54
    •	Athabasca / Lac La Biche (Northeast) – 27
    •	Vegreville (Central) – 56
    •	High Level (Northwest) – 18
    •	Alliance / Battle River (Central) – 36
    •	Brooks (South) – 47
    •	Grand Prairie (Northwest) – 20
    •	Wabamun (Edmonton)– 40
    •	Hinton / Edson (Central) – 29


# Electricity Consumption per capita for the Nine region in Alberta for the Whole Data frame

The image below provides a clear visual representation of electricity consumption per capita across nine different regions in Alberta, with each region labeled by numbers. The color gradient, from purple (low consumption) to yellow (high consumption), indicates the level of electricity consumption.


![sf_viz_whole](https://github.com/user-attachments/assets/3a06c786-bcb5-45b3-a8be-ae5bf9a337e7)

## Regional Electricity Consumption Per capita Analysis:
### High Consumption Areas: 

Hinton / Edson (29) in the central region is having the highest electricity consumption per capita indicated by yellowish green colour. Areas line Grand Prairie (20), and Brooks (47) followed with an electricity consumption per capita of about 0.03.

### Moderate Consumption Areas: 
Areas such Vegreville (56) in the Central and Athabasca / Lac La Biche (27) in the northeast show’s moderate consumption. 
Low Consumption Areas: 
High level (18), Wabamun (40), Alliance / Battle River (36), and Lethbridge (54), which are in the purple blue range, indicate lower electricity consumption. 


## Average Temperature for the Nine Regions in Alberta
![sf_viz_temp_whole](https://github.com/user-attachments/assets/d5702944-d110-4897-aa80-6851f5de6bef)

Analysis:
The image depicts temperature data across nine regions, with each region labeled by numbers and temperature in degrees Celsius. All regions have similar average degree of temperature in a year with a slight difference between central regions, north and southern regions. This means that there is only slight temperature difference between these regions in Alberta ranging from 2°C to 10°C. Regions with temperatures around 0°C to 10°C might see higher electricity usage during colder periods due to heating needs. The variation in temperature highlights how different climatic conditions can significantly influence electricity consumption patterns. 



# Winter Season
## Electricity Consumption per capita for the Nine region in Alberta for Winter Season

![elect_sf_viz_winter](https://github.com/user-attachments/assets/e945e6e1-e051-4d18-a7d5-9403e2f0b893)

### Regional Electricity Consumption Trends for Winter:
Areas located on the Hinton / Edson (29), Grand Prairie (20), and Brooks (47), are having the highest electricity consumption per capita, with Hinton / Edson from Central is having the highest consumption per capita. Areas such Vegreville (56) in the Central and Athabasca / Lac La Biche in the northeast show’s moderate consumption. High level (18), Wabamun (40), Alliance / Battle River (36), and Lethbridge (54), which are in the purple blue range, indicate lower electricity consumption. The central and northern regions show a mix of high and low values. The northernmost area has a consumption value of 18, which is one of the lowest on the map, indicating either lower heating requirements or less demand for electricity in that region.


## Average Temperature during Winter for Nine Selected Regions

From the image below as you move northward (towards higher latitudes), the temperatures tend to decrease. This is shown by progressively darker shades of blue and lower numerical values. From the image it is showing that High Level (18) in the Northwest is having a lowest temperature with an average temperature of amount -18 than all the other regions. From number Grand Prairie down south is having a similar temperature during winter of an average of -15 which is indicated by a similar colour gradient on the map.

![temp_sf_viz_winter](https://github.com/user-attachments/assets/15b1e2de-6470-4596-b6ab-c9c495a76705)



## Heatmap of Temperature and Electricity consumption during winter season

The highest concentration of data points is around -20°C, indicating that electricity consumption peaks at this temperature. As temperatures rise from 0°C to -20°C, electricity consumption increases, shown by the transition from light blue to dark red.
There is a noticeable positive correlation between temperature and electricity consumption up to around -20°C. As the temperature increases from 20°C to -20°C, electricity consumption also increases. This is due to heating requirements in colder temperatures. 
In colder temperatures (below 20°C), the demand for heating drives up electricity consumption. This is evident from the increasing consumption as temperatures falls from 20°C to - 20°C. The peak around -10°C suggests an optimal temperature range where electricity consumption is highest. This could be due to heating to higher overall energy use.

![heatmap_winter](https://github.com/user-attachments/assets/1e88aa6b-455f-4254-a1a6-d4bbdb4bf818)



# REGRESSION ANALYSES ON TEMPERATURE AND ELECTRICITY CONSUMPTION DURING WINTER

![image](https://github.com/user-attachments/assets/cdf2577e-c579-4614-b8f8-036ca9886673)


## Results Analysis:
The regression analysis assesses the relationship between total electricity consumption in winter and numerous factors, including minimum temperature and area-specific identifiers (Area_ID) for the areas. The model shows that minimum temperature (min_temp) significantly and positively impacts total electricity consumption, with a coefficient of 116,361.1, suggesting that colder temperatures increase electricity usage. Area-specific factors also significantly affect consumption. Alliance / Battle River (Area_ID36) has a negative effect, while Wabamun in Edmonton (Area_ID40),  Brooks (Area_ID47), Lethbridge (Area_ID54), and Vegreville (Area_ID56) have positive impacts, indicating regional variations in electricity use. Lethbridge (Area_ID54) is having the highest total electricity consumption of all the areas.
The high R-squared value of 0.958 suggests the model explains 95.8% of the variance in total electricity consumption. The F-statistic of 1,281.399 indicates overall model significance, confirming the robustness of these findings.



# Summer Season

## Electricity Consumption per capita for the Nine region in Alberta for Summer Season

![elect_sf_viz_summer](https://github.com/user-attachments/assets/38b72996-e342-4834-8de1-31b78c2a30a1)


## Regional Electricity Consumption Trends for Winter:
### Low Consumption Regions:
  
Wabamun (40), Alliance / Battle River (36), and Lethbridge (54), which are in the purple blue range, indicate lower electricity consumption in summer. 

### Moderate Consumption Regions:

Areas such Vegreville (56) in the Central, Athabasca / Lac La Biche (27) in the northeast, and High Level (18) in the northern shows moderate consumption.

### Higher Consumption Regions: 

Hinton / Edson (29) in the central region is having the highest electricity consumption per capita indicated by yellowish green colour. Areas like Grand Prairie (20) and Brooks (47) followed with an electricity consumption per capita of about 0.03.


## Temperature for the Nine region in Alberta for Summer Season
![temp_sf_viz_summer](https://github.com/user-attachments/assets/9f56f10a-4f78-465e-83e6-b987333733a3)


## Interpretation
High Level (18) is showing the area in a region having the highest average temperature in the summer around 20°C indicating higher need for cooling systems and higher. Moving from that area to the eastern and southern part, they have a similar temperature, but it falls slightly to around 18°C shown by the yellowish-green colour which suggest moderate cooling need. Areas like Hinton / Edson (29) and Grand Prairie (20) are having the lowest temperature ranking averagely during summer.


## Heatmap of Temperature and Electricity consumption during summer season

![heatmap_summer](https://github.com/user-attachments/assets/b3085251-66c5-485a-accd-da40d2a96182)

The highest counts of data points are in range 10°C to 30°C, indicated by the area on the heatmap.  Electricity consumption in these regions varies between 50 and 200 units. This suggests that during summer, moderate to high temperatures lead to increased electricity use, likely due to the widespread use of cooling systems.
At temperatures below 10°C and above 30°C, the counts of data points decrease, indicated by the blue areas. Electricity consumption in these ranges remains consistent, with fewer data points recorded. This imply that extreme temperatures (extremely low or extremely high) are less common in the summer. 
The heatmap visually highlights a strong positive correlation between temperature and electricity consumption during summer. As temperatures rise from around 10°C to 30°C, there's a clear increase in electricity consumption, seen in the red areas on the heatmap. This trend is driven by the extensive use of air conditioning and cooling systems as people seek to maintain comfortable indoor temperatures.
Interestingly, the most frequent occurrences of high electricity consumption align with moderate to elevated temperatures, reinforcing the direct relationship between temperature and energy use.


## EGRESSING ANALYSIS FOR TEMPERATURE AND TOTAL ELECTRICITY 




