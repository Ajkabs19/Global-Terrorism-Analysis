# Terrorism Database

## About The Dataset

It contains information about terrorist attacks worldwide. It includes details such as the date, location, attack type, weapons used, number of casualties, and responsible groups from 1970 to 2017. Download the dataset [here](https://drive.google.com/file/d/1HrriUeyWZTlcAIDlpcWY4PU6k4DFOVav/view?usp=drive_link)

## Project Task

We want to create a Power BI dashboard that provides a comprehensive overview of global terrorism trends and patterns.

### Data Exploration 

It contains initial 135 columns and 0ver 5000 rows

1. the event id, iyear, imonth, iday, extended,  column seems ok with nulls and blanks removed
2.  I decided to remove approxdate, country numbers, region number. I do not see the need of it in this analysis.
3. The resolution date has huge numbers of empty cells, and I figured out it won't be needed based on the task at hand. So, I removed the column.
4. provstate 2 cells belonging to Dominican Republic and Japan that were empty were removed.
5. All nulls and empty cells in City, longitude and latitude were removed.
6. location and summary were equally removed as they do not seem relevant to this analysis, nor were they complete. the same with specificity, vicinity, crit1-3, doubtterr, alternative, alternative text, attacktype1-3 no, sucide, multiple, targettype1 no, target subtype, natlyt1, targettype2, .. all irrelevant, blanks and empty column were removed
7. corp1 empty and nulls were removed, targetsubtype too.

### Data Visualization

#### Terrorist Attack by Event_id
The Sum of event Id column was compared against the year to give highlights of events over the year

![Capture](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/1be32020-34d6-4fa6-b593-abb29208f715)

#### Critical Attacks By Region
The sum of attacks was compared against regions, to reveal the region with the most attacks. Overall, North America has the highest, though different regions has it with varying years.

![1](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/76b31afd-6768-453a-bb74-c2f4528db142)

#### Institutions By Attacks
Various Institutions were compared in attacks. Business happens to have the highest overall, the institutions also changes with years

![2](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/ee726702-14ce-49c3-9e72-16d35a6bf288)

#### Sum of Sucide By Region
Middle East & North Africa are tied in over number of sucide attacks, it changes with years as well.

![3](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/531308cc-8d22-4fee-be04-6815a8f79d02)

#### Attack Type 
Faclity and Infrastructural attack has the highest number of attacks by the terrorsit groups combined. It varies with individual terrorist groups

![4](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/c2c4803e-8f5b-4667-b5ee-d48d34b424c8)


#### Overall Killing Figures Obtained
The figures in killigs varies with individual terrorist group

![5](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/e127bda6-e683-4055-b0ef-6067c5b0058c)


#### Corporation Atacks By Kills & Wounds
Various corporation/ establishments affected with the variuous gang/terrorist group responsible were obtained with each records. 
The image belows shows ranking by killings

![dynamic dashboard](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/32d61866-12f8-410b-a5cc-3c68090a1918)

The other one here shows ranking by wounds

![6](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/efb31283-eb57-417a-b0a7-bd071a7d2c49)

#### Count of Kills & Attacks By Region
With the Comparison, North America tops in Attacks, while Sub-Saharan African tops in Kills

![7](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/c106ca53-a662-4dfe-973e-7ab7bbcc5220)

#### Attacks By Weapon
Explosives is observed as the overall weapon of all time by the terrorist in the cordination of their attacks. It is only followed by Incendiary

![8](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/964143a5-8ff4-46f3-9f84-96eef4c001db)

#### Critical Attacks By Gangs
Left wings millitants and Student Radicals seems to have the overall number of cordinated attacks, and it varies over the years

![9](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/92777fe4-bf60-461b-8b63-8a59191f2455)

#### Attacks over Time
The timeline showa attack over Year in this first chart

![10](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/9385583f-343d-44b4-8dc3-1daa63ef24e7)

And with a drill down option, we can see the timeline in months.

![12](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/7b82e3ae-c76a-4824-a37b-c7c420992cc5)

#### Count Of Critical Attacks in Longitud and Latitude
South Asia tops here with the most critical hits

![11](https://github.com/Ajkabs19/Global-Terrorism-Analysis/assets/138918007/e92bb2f6-2656-4a79-aa54-7c2be6f7c965)


Kaggle portfolio [here](https://www.kaggle.com/kehindeajadi)
