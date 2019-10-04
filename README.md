# lego-Predict-the-theme-lego-kind-
classification project: Predict lego theme based on lego data dataset

This is a classification project:  I tried to predict the theme of Lego sets based on the parts, colors and year and some more features.
When I find the Lego database on re-brick-able, It sparkled my imagination and I wanted to do an ML project based on that database.
The re-brick-able dataset contains the LEGO Parts/Sets/Colors and Inventories of every official LEGO set in the Rebrickable database.
To work with this data, first I flatten the data: from eight connected tables to one big table.
After that I cleaned the data a little bit
Then I did some feature engineering.
colorful: how much each set is colorful (based on the RGB of each part)
complexity:  and how complex is the set (how many different parts categories in each set)

next I tested if pca will help or not and run different models to predict the theme of the set
in the end adaboost was the best model

files in this repository:
code: lego 4.0 code.ipynb 
original dataset schema : downloads_schema.png
dateset files:
colors.csv
inventories.csv
inventory_parts.csv
inventory_sets.csv
part_categories.csv
part_relationships.csv
parts.csv
sets.csv
themes.csv

https://rebrickable.com/downloads/ 
hope you enjoy to play and see the project like I did!
yossi
