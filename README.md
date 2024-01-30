# Predict-nationality-Based-on-name

  <p align="center">
  <img width="500" height="500" src=https://github.com/NjoodJ/Predict-nationality-Based-on-name/assets/93571826/0d6ce2fd-02d0-48ed-83d3-7cab0a4fb18b>
</p>
This repository contains code for predicting the nationality of individuals based on their names using a Naive Bayes model. The goal of this project is to accurately classify names into different nationalities using the Naive Bayes algorithm.

## Data
The dataset contains names labeled with the following nationalities:
- Indian
- Russian
- Japanese
- African
- German
- French
- American
- Saudi
  <p align="center">
  <img width="600" height="400" src=https://github.com/NjoodJ/Predict-nationality-Based-on-name/assets/93571826/ba21058f-163b-447a-87ae-ce9693fd2d9b>
</p>

## Output
After running the code, you will receive the predicted nationalities for the provided list of names. The output will be displayed in the console or saved to a file, depending on your configuration. 
#### EX1:
```
sample1 = ["Laxie"]
vect1 = cv.transform(sample1).toarray()
clf.predict(vect1)
```
##### Output:
```
array(['american'], dtype='<U8')
```
--------------------------------------------------
#### EX2:
```
sample2= ["khan","Satit","Silko",'Sila','Braun','Kozakura']
vect2 = cv.transform(sample2).toarray()
clf.predict(vect2)
```
##### Output:
```
array(['indian', 'saudi', 'african', 'american', 'german', 'japanese'],
      dtype='<U8')
```
## Conclusion
In conclusion, the Naive Bayes model developed for predicting nationalities based on names has shown promising results. By leveraging the characteristics of different nationalities, the model successfully classified names into various categories, such as Indian, Russian, Japanese, African, German, French, American, and Saudi.

Overall, the developed Naive Bayes model has demonstrated its ability to predict nationalities based on names effectively, offering a valuable tool for various real-world applications.

