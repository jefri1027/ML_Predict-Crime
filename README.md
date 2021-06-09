# Sexual Harassments and Child Abuse Prediction

Determining the Relationship between Sexual Harassments and Child Abuse Occurrences with the Location of the Incidents with Machine Learning Principles (Example of a Case Study in Los Angeles Crime Data)

## Important Input Feature

Data set from:
https://www.kaggle.com/cityofLA/los-angeles-crime-arrest-data

1. Year

* The year the crime occurred

2. Month

* The month the crime occurred

3. Day

* The day the crime occurred

4. Day of Week

* The day of the week the crime occurred

5. Quarter

* Quarter did the crime occur (example: January-April is quarter 1, etc)

6. Time Occurred

* The time when the crime occurred

7. Victim Age

* Age of victims when the crime occurred

8. Victim Sex

* Victim gender

9. Victim Descent 
(Description)

* A: Other Asian, B: Black, C: Chinese, D: Cambodian, F: Filipino, G: Guamanian, H: Hispanic, J: Japanese, K: Korean, L: Laotian, O: Other, P: Pacific Islander, S: Samoan, U: Hawaiian, V: Vietnamese, W: White, X: Unknown, Z: Asian Indian

10. Premise

* The type of structure or where the crime took place

11. Address

* Address when the crime occurred

12. Latitude

* Latitude when the crime occurred

13. Longitude

* Longitude when the crime occurred

## Target 

1. Type of crime and its index number

* LETTERS, LEWD  -  TELEPHONE CALLS, LEWD                      (7)

* BATTERY WITH SEXUAL CONTACT                                  (0)

* RAPE, FORCIBLE                                               (12)

* CHILD ABUSE (PHYSICAL) - SIMPLE ASSAULT                      (4)

* SEX, UNLAWFUL(INC MUTUAL CONSENT, PENETRATION W/ FRGN OBJ    (13) 

* SEXUAL PENETRATION W/FOREIGN OBJECT                          (14)

* ORAL COPULATION                                              (10)

* CHILD ABUSE (PHYSICAL) - AGGRAVATED ASSAULT                  (3)

* SODOMY/SEXUAL CONTACT B/W PENIS OF ONE PERS TO ANUS OTH      (15)

* LEWD CONDUCT                                                 (8)

* RAPE, ATTEMPTED                                              (11)

* HUMAN TRAFFICKING - COMMERCIAL SEX ACTS                      (5)

* LEWD/LASCIVIOUS ACTS WITH CHILD                              (9)

* CHILD ABANDONMENT                                            (2)

* BEASTIALITY, CRIME AGAINST NATURE SEXUAL ASSLT WITH ANIM     (1)

* INCEST (SEXUAL ACTS BETWEEN BLOOD RELATIVES)                 (6)

## Workflow

1. Taking data from Kaggle
2. Select data related to sexual harassments and child abuse
3. Separate latitude, longitude, and  date occurred in one frame each
4. Separate date occurred to year, month, day, day of week, and quarter
5. Convert some data to numeric, and label with label encoder
7. Fix data weird data and delete outlier data
8. Merge all data frame which needs to training
9. Plot histogram to visualization type of crime and heatmap
10.Plot to map see the distribution of type crime at Los Angeles

Machine Learning (Neural Network)

11. Selected feature and target data
12. Normalization data (improve training data)
13. Make callback function
14. Split and tuning data (train and validate)
15. Set model layer
16. Train the data
17. Plot accuracy and loss based on training vs validation
18. Take a data model to predict
19. Test prediction
20. Save the model with TensorFlow Lite type
