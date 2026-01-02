# IMPACT OF TEMPERATURE ON ELECTRICITY CONSUMPTION PATTERNS IN ALBERTA, CANADA?

Date: 03/11/2024

# Background

Temperature and Electricity Consumption: The relationship between temperature and electricity consumption is a wellstudied phenomenon1. Research has shown that electricity consumption tends to follow a well u-shaped curve with respect to temperature. This means both extremely high and low temperature leads to increased electricity use.
Winter: During colder months, electricity consumption rises due to the increased use of     heating systems. In regions with harsh winters, heating demands can significantly drive-up electricity usage.
Summer: Conversely, in the summer, higher temperatures lead to greater use of air                conditioning and cooling systems, which also increases electricity consumption
Studies have identified a critical temperature point around 14.6°C. Below this temperature, electricity consumption increases due to heating needs, and above this temperature, it        increases due to cooling needs.
The impact of temperature on electricity consumption can vary by region. Urban and              industrial areas often have higher consumption due to greater energy needs. 
Climate change can exacerbate this relationship, particularly in regions already facing          electricity deficits. For example, a 1°C increase in temperature can significantly increase electricity demand in some areas.
Understanding this relationship is crucial for energy policy and infrastructure planning. It helps in designing strategies to manage peak demand periods and ensure a reliable electricity supply. Additionally, promoting energy efficiency measures can mitigate the impact of temperature fluctuations on electricity consumption.


# Research Objective

How do winter and summer temperatures affect electricity consumption differently of nine different regions in Alberta?

## Research Questions
    To analyze the relationship between temperature variations and electricity consumption patterns across nine regions in Alberta during the winter and summer seasons.
    To identify critical temperature thresholds that significantly impact electricity demand for heating in winter and cooling in summer.
    To assess regional differences in electricity consumption and explore the influence of regional characteristics (e.g., population, industrial activity) on energy usage.

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


## REGRESSING ANALYSIS FOR TEMPERATURE AND TOTAL ELECTRICITY 

![image](https://github.com/user-attachments/assets/6da8af59-fced-4829-aabb-244ca2240452)

## Results Analysis
The regression analysis explores the relationship between total electricity consumption and maximum temperature during summer, incorporating area-specific factors. The maximum temperature (max_temp) has a significant positive effect, with each unit increase leading to an increase in electricity consumption by approximately 78,671 units. This highlights the substantial influence of rising temperatures on energy demand for cooling. Area-specific factors further illustrate significant variability: regions like Grande Prairie (Area_ID20), Athabasca / Lac La Biche (Area_ID27), Hinton / Edson (Area_ID29), Waban(Area_ID40), Brooks (Area_ID47), and Lethbridge (Area_ID54) exhibit markedly higher electricity consumption, possibly due to higher population densities or industrial activities, while Alliance / Battle River (Area_ID36) shows a significant decrease, indicating regional efficiency or lower energy needs. The model’s high R-squared value of 0.982 underscores its robustness, explaining 98.2% of the variance in electricity consumption, confirming the significant impact of both temperature and regional characteristics on electricity usage. 


# Conclusion

Based on the analysis of electricity consumption patterns in Alberta during winter and summer seasons, several key conclusions can be drawn. In winter, the regions of Hinton/Edson, Grand Prairie, and Brooks show the highest electricity consumption per capita, likely due to increased heating demands. The regression analysis for winter reveals a significant positive relationship between colder temperatures and electricity usage, with a coefficient of 116,361.1 for minimum temperature.
Conversely, in summer, while Hinton/Edson maintains high consumption, areas like High Level show increased usage, due to cooling needs. The summer regression analysis indicates that each unit increase in maximum temperature leads to an increase in electricity consumption by approximately 78,671 units.
Both seasons demonstrate strong correlations between temperature and electricity consumption, with R-squared values of 0.958 for winter and 0.982 for summer, highlighting the substantial impact of seasonal temperature variations on energy demand.


# APPENDIX

## DATA 
[studentData.zip](https://github.com/user-attachments/files/18934111/studentData.zip)

## CODES

[Uploading Assignment-3.Rm---
title: "Assignment_3"
author: "Seth Oduro"
date: "2024-10-31"
output: html_document
---

#    How does winter temperature affect electricity consumption patterns compared to summer temperatures?


```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```


## Loading Libraries
```{r}
library(readr)
library(sf)
library(lubridate)
library(stargazer)
library(ggplot2)
library(here)
library(readxl)
library(janitor)
library(tidyverse)
library(dplyr)
here()
```

## Importing dictionary, population, electricity and AESO planning Data
```{r}
# Import data
dictionary <- read_csv(here("data", "dictionary.csv"))
population <- read_csv(here("data", "population.csv"))
electricity <- read.csv(here("data", "electricity_district.csv"))
planning_areas <- st_read(here("data", "shape", "AESO_Planning_Areas.shp"))
```


## Preparation to plot Shape Visualization
```{r}
planning_areas <- st_read(here("data", "shape/AESO_Planning_Areas.shp")) |>
  mutate(Area_ID = as.numeric(Area_ID))

head(planning_areas)
```

```{r}
# Plotting the plot
map_base <- ggplot(planning_areas) +
  geom_sf() +    
  labs(title = "Alberta") 
map_base
```

```{r}
AESO_Planning_Areas <- st_read("data/shape/AESO_Planning_Areas.shp")
```

```{r}
districts <- st_drop_geometry(AESO_Planning_Areas)

selected_districts <- c("Lethbridge", "Athabasca / Lac La Biche", "Vegreville", "High Level", "Alliance / Battle River", "Brooks", "Grande Prairie", "Wabamun", "Hinton / Edson")
districts <- districts %>%
  filter(NAME %in% selected_districts)
 
print(districts)
```

```{r}
planning_areas$Area_ID <- as.character(planning_areas$Area_ID)
```


```{r}
# combining the planning area data to the district data
planning_areas <- planning_areas %>%
  left_join(districts, by = "Area_ID")
head(planning_areas)

# Plotting the map for the planning area
alberta_complete <- ggplot(planning_areas) +
  geom_sf(fill = "lightblue", color = "black") +    
  geom_sf_text(data = st_centroid(planning_areas),             
               aes(label = Area_ID),                   
               color = "darkred", size = 3) +       
  labs(title = "Alberta")

alberta_complete

```


```{r}
# Mutating the district Area_ID
districts <- districts |>
  mutate(id_label = Area_ID) |>
  select(Area_ID, id_label)

head(districts)
```

```{r}
# Adding the planning data to the district
planning_areas_joined <- planning_areas |>
  left_join(districts, by = "Area_ID") |>
  mutate(id_label = as.character(id_label)) |>
  mutate(id_label = ifelse(is.na(id_label), "", id_label))
head(planning_areas_joined)

st_centroid(planning_areas_joined)
```
```{r}
# Selecting the 9 regions for Alberta
alberta_dist <- ggplot(planning_areas_joined) +
  geom_sf(fill = "lightblue", color = "black") +    
  geom_sf_text(data = st_centroid(planning_areas_joined),             
               aes(label = id_label),                   
               color = "darkred", size = 3) +       
  labs(title = "Alberta ") 

alberta_dist
```

## Data Preparation for the Dictionary, Population, and Electricity Data 
```{r}
head(dictionary)
```

```{r}
head(population)
```


```{r}
head(electricity)
```


```{r}
# Join population data with dictionary
population <- population %>%
  inner_join(dictionary, by = "code") %>%
  group_by(Area_ID, year) %>%
  summarise(total_pop = sum(population, na.rm = TRUE)) %>%
  arrange(Area_ID, year)
```

```{r}
head(population)
```

```{r}
# Convert datetime column to datetime object
electricity$datetime <- ymd_hms(electricity$datetime)

# Pivot electricity data to long format
electricity_long <- electricity %>%
  pivot_longer(cols = starts_with("AREA"), names_to = "Area_ID", values_to = "elect_use") %>%
  mutate(Area_ID = as.numeric(gsub("AREA", "", Area_ID)),
         year = year(datetime))

head(electricity_long)
```




```{r}
# Join electricity data with population data
combined_data <- electricity_long %>%
  inner_join(population, by = c("Area_ID", "year")) %>%
  mutate(consumption_per_capita = elect_use / total_pop)

head(combined_data)


```



```{r}
# Joining the planning area data with the electricity combined data
planning_areas_joined <- planning_areas_joined %>%
  mutate(Area_ID = as.character(Area_ID))

combined_data <- combined_data %>%
  mutate(Area_ID = as.character(Area_ID))


shape_viz <- planning_areas_joined |>
  left_join(combined_data, by = "Area_ID")
head(shape_viz)
```

## Plotting consumption per capita for the nine regions using the whole year round
```{r}
ggplot() +
  geom_sf(data = shape_viz,
          aes(fill = ifelse(consumption_per_capita > 0, consumption_per_capita, NA))) +
  # scale_fill_viridis_c(na.value = "gray90") +      
  labs(title = "Electricity consumption per capita",
       fill = "Consumption") 
```


```{r}
elect_viz_shape_whole <- ggplot() +
  geom_sf(data = shape_viz,
          aes(fill = ifelse(consumption_per_capita > 0, consumption_per_capita, NA))) +
  scale_fill_viridis_c(na.value = "gray90") +  
  geom_sf_text(data = st_centroid(planning_areas_joined),             
               aes(label = id_label),                   
               color = "white", size = 3) +
  labs(title = "Electricity consumption per capita",
       fill = "Consumption")

print(elect_viz_shape_whole)
```

```{r}
# Saving Electricity Consumption Per Capita for the 9 Regions using the whole data
#ggsave("sf_viz_whole.png", plot = elect_viz_shape_whole, width = 8, height = 6)
```



## Importing and Preparing Temperature Data
```{r}
# Importing the temperature data

temp_files <- list.files(here("data", "temperature"), full.names = TRUE, pattern = "*.csv")
temperature_data <- map_df(temp_files, read_csv) %>%
  mutate(year = year(datetime))


```

```{r}
head(temperature_data)
```

```{r}
# Changing the date to an appropriate date
temperature <- temperature_data %>%
  mutate(datetime = as.Date(datetime, format = "%Y-%m-%d"))

head(temperature)
```




```{r}
# Combining temperature data with the planning area data
temperature_data <- temperature_data %>%
  mutate(Area_ID = as.character(Area_ID))

shape_temp <- planning_areas_joined %>%
  left_join(temperature_data, by = "Area_ID")


head(shape_temp)
```


## Plotting the map for temperature in the nine regions for the whole data
```{r}
ggplot() +
  geom_sf(data = shape_temp,
          aes(fill = ifelse(temp_c, temp_c, NA))) +
  # scale_fill_viridis_c(na.value = "gray90") +      
  labs(title = "Temperature",
       fill = "Fahrenheit") 
```



```{r}
temp_viz_shape_whole <- ggplot() +
  geom_sf(data = shape_temp,
          aes(fill = ifelse(temp_c , temp_c, NA))) +
  scale_fill_viridis_c(na.value = "gray90") +  
  geom_sf_text(data = st_centroid(planning_areas_joined),             
               aes(label = id_label),                   
               color = "white", size = 3) +
  labs(title = "Temperature",
       fill = "degree Celsius (°C)")

print(temp_viz_shape_whole)
```


```{r}
# Saving Temperature for the 9 Regions using the whole data
# ggsave("sf_viz_temp_whole.png", plot = temp_viz_shape_whole, width = 8, height = 6)
```


# REDUCING DATA FOCUS FOR ONLY DATA DURING WINTER

```{r}
# reducing the combined data to only winter (dec to feb)
combined_data_winter <- combined_data %>%
  filter(month(datetime) %in% c(12, 1, 2))

combined_data_winter <- combined_data_winter %>%
  mutate(Area_ID = as.numeric(Area_ID))


head(combined_data_winter)
```

```{r}
# Reducing temperature data for the winter months (e.g., December to February):

temperature_data_winter <- temperature_data %>%
  filter(month(datetime) %in% c(12, 1, 2))

temperature_data_winter <- temperature_data_winter %>%
  mutate(Area_ID = as.numeric(Area_ID))


head(temperature_data_winter)
```


```{r}
# Join temperature data with combined data
winter_data <- combined_data_winter %>%
    left_join(temperature_data_winter, by = c("Area_ID", "year"))

head(winter_data)
```

```{r}
# Combining Temperature with the planning area data for winter
temperature_data_winter <- temperature_data_winter %>%
  mutate(Area_ID = as.character(Area_ID))


shape_viz_temp_winter <- planning_areas_joined %>%
  left_join(temperature_data_winter, by = "Area_ID")
head(shape_viz_temp_winter)
```


```{r}
# Combining Temperature with the planning area data for winter
combined_data_winter <- combined_data_winter %>%
  mutate(Area_ID = as.character(Area_ID))


shape_viz_comb_winter <- planning_areas_joined %>%
  left_join(combined_data_winter, by = "Area_ID")
head(shape_viz_comb_winter)
```

## Plotting The Per Capita For The 9 Regions For Winter (December to February)
```{r}
ggplot() +
  geom_sf(data = shape_viz_comb_winter,
          aes(fill = ifelse(consumption_per_capita > 0, consumption_per_capita, NA))) +
  # scale_fill_viridis_c(na.value = "gray90") +      
  labs(title = "Electricity consumption per capita during winter",
       fill = "Consumption") 
```

```{r}
elect_shape_viz_winter <- ggplot() +
  geom_sf(data = shape_viz_comb_winter,
          aes(fill = ifelse(consumption_per_capita > 0, consumption_per_capita, NA))) +
  scale_fill_viridis_c(na.value = "gray90") +  
  geom_sf_text(data = st_centroid(planning_areas_joined),             
               aes(label = id_label),                   
               color = "white", size = 3) +
  labs(title = "Electricity consumption per capita during winter",
       fill = "Consumption")

print(elect_shape_viz_winter)
```

```{r}
# Saving the viz
#ggsave("elect_sf_viz_winter.png", plot = elect_shape_viz_winter, width = 8, height = 6)
```


## Plotting the Shape Visualization for Temperature for Winter
```{r}
ggplot() +
  geom_sf(data = shape_viz_temp_winter,
          aes(fill = ifelse(temp_c, temp_c, NA))) +
  # scale_fill_viridis_c(na.value = "gray90") +      
  labs(title = "Temperature",
       fill = "Degree Celsius (°C)") 
```


```{r}
temp_shape_viz_winter <- ggplot() +
  geom_sf(data = shape_viz_temp_winter,
          aes(fill = ifelse(temp_c , temp_c, NA))) +
  scale_fill_viridis_c(na.value = "gray90") +  
  geom_sf_text(data = st_centroid(planning_areas_joined),             
               aes(label = id_label),                   
               color = "white", size = 3) +
  labs(title = "Temperature during Winter",
       fill = "Degree Celsius (°C)")

print(temp_shape_viz_winter)
```

```{r}
# Saving the Shape Visualization for Temperature in 9 regions for Winter
# ggsave("temp_sf_viz_winter.png", plot = temp_shape_viz_winter, width = 8, height = 6)
```


## Regression Analysis for Winter
```{r}
# Add a day column by extracting the day from the datetime column:
winter_data <- winter_data %>%
  mutate(day = day(datetime.x))

head(winter_data)
```

```{r}
# Group by Area_ID, year, and day, then calculate the minimum temperature and sum of electricity consumed:

winter_summary <- winter_data %>%
  group_by(Area_ID, year = year(datetime.x), day) %>%
  summarise(
    min_temp = min(temp_c),
    total_electricity = sum(elect_use)
  )
```


```{r}
head(winter_summary)
```


```{r}
# Regression total electricity on temperature
model_winter <- lm(total_electricity ~ min_temp + factor(Area_ID), data = winter_summary)
summary(model_winter)
```

```{r}
# Saving with Stargazer
# stargazer(model_winter, type = "html", title = "Regression Results  on Total Electricity and Temperature (Winter)", align = TRUE,
  #        column.labels = c("Total Electricity"),
   #       out = "Regression(Winter).html")
```


## Plotting Heatmap for only 2018 for Winter Season
```{r}
# Filter the data for the year 2018
winter_data_2018 <- winter_data %>% filter(year == 2018)


```

```{r}
head(winter_data_2018)
```


```{r}
# Plotting thr heatmap for the winter season in 2018
library(ggplot2)

heatmap_winter <- ggplot(winter_data_2018, aes(x = temp_c, y = elect_use)) +
  geom_bin2d() +
  scale_fill_gradient(low = "blue", high = "red") +
  labs(title = "Heatmap of Temperature vs Electricity Consumption",
       x = "Temperature (°C)",
       y = "Electricity Consumption")

print(heatmap_winter)
```



```{r}
# Saving the Heatmap for Temperature and Electricity Consumption(Winter)
# ggsave("heatmap_winter.png", plot = heatmap_winter , width = 8, height = 6)
```


# REDUCING DATA FOCUS FOR ONLY DATA DURING SUMMER

```{r}
# reducing the combined data to only Summer season
combined_data_summer <- combined_data %>%
  filter(month(datetime) %in% c(6, 7, 8))

combined_data_summer <- combined_data_summer %>%
  mutate(Area_ID = as.numeric(Area_ID))


head(combined_data_summer)
```


```{r}
# Reducing temperature data for the summer season

temperature_data_summer <- temperature_data %>%
  filter(month(datetime) %in% c(6, 7, 8))

temperature_data_summer <- temperature_data_summer %>%
  mutate(Area_ID = as.numeric(Area_ID))


head(temperature_data_summer)
```


```{r}
# Join temperature data with combined data for summer seeason
summer_data <- combined_data_summer %>%
    left_join(temperature_data_summer, by = c("Area_ID", "year"))

head(summer_data)
```

```{r}
# Combining Temperature with the planning area data for summer season
temperature_data_summer <- temperature_data_summer %>%
  mutate(Area_ID = as.character(Area_ID))


shape_viz_temp_summer <- planning_areas_joined %>%
  left_join(temperature_data_summer, by = "Area_ID")

head(shape_viz_temp_summer)
```

```{r}
# Combining electricity combined data with the 9 planning area data for Summer season
combined_data_summer <- combined_data_summer %>%
  mutate(Area_ID = as.character(Area_ID))


shape_viz_comb_summer <- planning_areas_joined %>%
  left_join(combined_data_summer, by = "Area_ID")

head(shape_viz_comb_summer)
```

## Plotting the Shape Visualization for consumption per capita for the Summer season
```{r}
ggplot() +
  geom_sf(data = shape_viz_comb_summer,
          aes(fill = ifelse(consumption_per_capita > 0, consumption_per_capita, NA))) +
  # scale_fill_viridis_c(na.value = "gray90") +      
  labs(title = "Electricity consumption per capita during Summer",
       fill = "Consumption") 
```


```{r}
elect_shape_viz_summer <- ggplot() +
  geom_sf(data = shape_viz_comb_summer,
          aes(fill = ifelse(consumption_per_capita > 0, consumption_per_capita, NA))) +
  scale_fill_viridis_c(na.value = "gray90") +  
  geom_sf_text(data = st_centroid(planning_areas_joined),             
               aes(label = id_label),                   
               color = "white", size = 3) +
  labs(title = "Electricity consumption per capita during Summer",
       fill = "Consumption")

print(elect_shape_viz_summer)
```

```{r}
# Saving the shape vizualization for the 9 regions for Summer season
# ggsave("elect_sf_viz_summer.png", plot = elect_shape_viz_summer, width = 8, height = 6)
```


## Plotting the Shape Visualization for Temperature for Summer Season
```{r}
ggplot() +
  geom_sf(data = shape_viz_temp_summer,
          aes(fill = ifelse(temp_c, temp_c, NA))) +
  # scale_fill_viridis_c(na.value = "gray90") +      
  labs(title = "Temperature",
       fill = "Fahrenheit") 
```


```{r}
temp_shape_viz_summer <- ggplot() +
  geom_sf(data = shape_viz_temp_summer,
          aes(fill = ifelse(temp_c , temp_c, NA))) +
  scale_fill_viridis_c(na.value = "gray90") +  
  geom_sf_text(data = st_centroid(planning_areas_joined),             
               aes(label = id_label),                   
               color = "white", size = 3) +
  labs(title = "Temperature during Summer",
       fill = "degree Celsius (°C)")

print(temp_shape_viz_summer)
```


```{r}
# Saving the shape visualization for the 9 regions for summer
# ggsave("temp_sf_viz_summer.png", plot = temp_shape_viz_summer, width = 8, height = 6)
```


## Plotting the Heatmap for the Summer season
```{r}
# Filter the data for the year 2018 for the summer season
summer_data_2018 <- summer_data %>% filter(year == 2018)
```

```{r}
head(summer_data_2018)
```


```{r}
heatmap_summer <- ggplot(summer_data_2018, aes(x = temp_c, y = elect_use)) +
  geom_bin2d() +
  scale_fill_gradient(low = "blue", high = "red") +
  labs(title = "Heatmap of Temperature vs Electricity Consumption for Summer",
       x = "Temperature (°C)",
       y = "Electricity Consumption")
```

```{r}
print(heatmap_summer)
```


```{r}
# Saving the heatmap plot
#ggsave("heatmap_summer.png", plot = heatmap_summer, width = 8, height = 6)
```


## Regression Results for Summer Season
```{r}
# Add a day column by extracting the day from the datetime column:
summer_data <- summer_data %>%
  mutate(day = day(datetime.x))

head(summer_data)
```


```{r}
# Group by Area_ID, year, and day, then calculate the maximume temperature and sum of electricity consumed for the Summer Season

summer_summary <- summer_data %>%
  group_by(Area_ID, year = year(datetime.x), day) %>%
  summarise(
    max_temp = max(temp_c),
    total_electricity = sum(elect_use)
  )
```
```{r}
head(summer_summary)
```

## Regression and Results for Summer Season
```{r}
model_summer <- lm(total_electricity ~ max_temp + factor(Area_ID), data = summer_summary)
summary(model_summer)
```


```{r}
# # Saving Regression results for Summer
#stargazer(model_summer, type = "html", title = "Regression Results  on Total Electricity and Temperature (Summer)", align = TRUE,
      #    column.labels = c("Total Electricity"),
      #    out = "Regression(Summer).html")
```d…]()



