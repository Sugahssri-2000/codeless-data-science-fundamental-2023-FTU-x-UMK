# Codeless Data Science Fundamental 2023 FTU x UMK

Divorce Cases in Malaysia based Several Factors

Abstract 

The purpose of this research is to appraise the escalate cases of divorce drift in Malaysia. Additionally, it also calls attention to the intention behind occurrence of the divorce cases. Moreover, there exist several factors of why divorce cases take place continuously by both categories namely male and female. However, with the research data, there are few influencing factors that contributes to the increase of divorce cases such as social, environmental, as well as background. Nevertheless, this report has come up with the reading of what are the reasons that largely subscribe to the supplement of the divorce in Malaysia.
Keywords: appraise, divorce, drift, influencing factors, supplement 

Introduction

Divorce cases in Malaysia has been setting the history day by day by increasing rapidly. The common issues such as domestic violence, age difference, religion, culture, difference or same races, and others there are also other acceptable factors being mentioned in the dataset.   
There are various factors that contributed to divorce such as age gap, education, economic similarity, social similarity, cultural similarity, social gap, common interest, religion compatibility, number of children from previous marriage, desire to marry, independency, relationship with the spouse family, trading in, engagement time, love, commitment, mental health, the sense of having children, previous trading, previous marriage, the proportion of common genes, addition, loyalty, height ratio, good income, self-confidence, relation with non-spouse before marriage, spouse confirmed by family, divorce in the family grade 1, as well as start socializing with the opposite sex age. Those factors have been contributed by both man and women in their married life.
Moreover, this report helps to present the graphs, charts, and numbers of each factor in clear and detail which can assist to understand what the divorce cases occur between male and female. In addition, besides the common factors like age, religion and others, there other new factors as also play the role in increasing the divorce cases in Malaysia. Those factors have been presented in respective charts and graphs for better understanding with description. 

Methodology
![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/a5ff05d1-ed79-4a3d-9367-138c7e0e3a58)


This is a CSV Reader where the excel files take place. Moreover, from this CSV reader can also be checked for the tables that has been correctly in ordered manner. There will be three colours exist which is the red, yellow and green. Where it means that the red is needed to be checked and the yellow is being checked and needs to be or ready to be executed and the green is the executed.


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/faa1975f-c872-441c-b57f-214dce9f7002)

The purpose of the column filter is to allow to be filter from the input table while only the remaining column can be passed to the next stage which is the output table. Well, all respective node has the main colour presented. When the column filter being executed the table can be viewed.


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/0ad4d37d-f353-4d0c-9da7-0ab803dbdcf0)

This is the single sample t-test which computed statistic for the single sample only. Besides, this single sample test is also known as the null hypothesis which the population mean will be same to the given value

![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/c1b03978-579d-4b81-943c-cbaa3477a63d)

This is known as the partitioning which the table of input is split into 2 which can be called as the learning and test data. Those 2 partitions are available in the 2 output ports.

![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/6b05d499-0b4a-430b-85d9-340f6e4c49d4)

The node allows for row filtering according to certain criteria. It can include or exclude certain ranges (by row number), rows with a certain row ID, and rows with a certain value in a selectable column (attribute).

![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/ef555ea6-be78-493a-8e44-237d021cd419)

In the node configuration, you can choose the columns you want to display. Only numeric and text based columns are supported. 
The configuration also offers a preview of the table, which should help to get the statistics in the desired shape quickly.

![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/975ac4a8-8dd7-439f-8e63-ad7b45d54ec3)

This node calculates the number of rows per attribute value per class for nominal attributes and the Gaussian distribution for numerical attributes. The created model could be used in the naive Bayes predictor to predict the class membership of unclassified data.


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/6e7c6a4d-0690-4a01-bfe9-c41c86872c45)




Predicts the class per row based on the learned model. The class probability is the product of the probability per attribute and the probability of the class attribute itself. 

![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/941b0d4f-84b9-4a3d-87c4-65f5aa8f5af9)



Compares two columns by their attribute value pairs and shows the confusion matrix like how many rows of which attribute and their classification match.


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/92f4e1b3-9c89-433b-bf65-099f42fe817c)

Colors can be assigned for either nominal (possible values have to be available) or numeric columns (with lower and upper bounds).




Experimental Result
![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/ed6389d8-4548-4180-b2c0-19242ba898c7)


Figure 1: Workflow of Knime

Figure 1 presents the workflow of the knime that has been used several nodes to come with informative results. In this workflow there are the use of column filter, row filter to specify which respective data to use. Next, partitioning, naïve bayes learner and predictor along scorer also been introduced to show the result of accuracy and error. On the other hand, there are other useful chart also been implemented to show clear results of the divorce dataset.

Statistics Table

![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/8c803284-0999-4f72-880a-bf92d5646d2c)

                                                                  Table 1


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/4b17af21-0318-473d-b79f-11429c05cbcd)
	





                                                               Table 2

 ![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/5145bff8-3765-4f7f-ba94-ec808adf35af)
                                                              
	Table 3

Diagram 1, 2, and 3 represents the statistical table of the whole factors that has been the main cause of divorce cases in Malaysia. In the table above it shows the values of minimum, maximum, 25, 50 and 75 percentage of quantile, mean, standard deviation as well as sum.

![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/7e189e3e-9c20-46b2-b40f-e8f36a08a5cd)

                                                           Figure 2: Scatter plot

This scatter plot is being represented with the education and age group factors


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/f11ca6af-019d-486d-a6ba-75c4255874dd)

Figure 3: Histogram
The histogram shows the result of factors such as age gap, education, love and self-confidence from both male and female from the first ten columns.


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/27479525-d907-4ef1-b959-872ae1d6d452)
   

Figure 4: Bar chart

The figure above presented in the bar chart which the blue, orange, green and red are the degree of freedom (df), mean difference, confidence interval and the confidence interval respectively for the male and female in the common interest, commitment, loyalty as well as the self confidence.


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/6a638d9b-2122-4451-91b8-60f6aeac4b71)

Figure 5: Density plot

The density plot presents the both male and female education.

![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/b7785eba-355f-4ad3-9f2f-840dfb5865fc)

                                                   Figure 5 : Line plot

Figure 5 is the line plot for the age gap, common interest, mental health and good income with green, blue, purple and red respectively.


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/346ae72e-6a9a-4e6f-a435-a289a0727f35)

                                             Figure 6: Single Sample T test
The table above in figure 6 is the single sample t test for the age gap, education, economic similarity, social similarity, cultural similarity, social gap, common interest, religion compatibility, number of children from previous marriage, desire to marry, independency, relationship with the spouse family trading in, engagement time and lastly love. For those attributes there are the calculated answer for mean, standard deviation, standard error mean.


![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/1bd2b4d6-f32c-4f8f-a214-8cb5bf5c29f6)


Figure 7: Single sample T-test and test
For the figure 7, it shows the single sample T-test and test for the common interest, commitment loyalty and for self confidence with the descriptive statistic and for confidence interval (CI) probability of 95%.


 ![image](https://github.com/langsari/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93998833/c6d9ee01-115c-401d-8b26-3d41723e7c43)



Figure 8: Density plot
This density plot resembles the common interest of both male and female.

Conclusion 
Divorce cases are common in Malaysia the occurrence of divorce cases has been rising gradually from day to day and it also records peak values in every year. Therefore, in the dataset there are 20 categories being the main cause of divorces occur and there are two factors namely male and female. However, with the usage of Knime workflow or platform makes the work way easier for a data analyst. This is due to the simple and non-coding platform to predict what will be the main or highest causes of the occurrence of the divorce cases. Moreover, with the usage of kinme it also can predict what will the main reason of the divorce cases among the 29 categories.



