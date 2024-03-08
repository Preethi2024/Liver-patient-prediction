# Liver-patient-prediction
# Task 1:-Prepare a complete data analysis report on the given data

      1. univariant ,bivariant and mutvariant analysis is done for the given data
      
      
 ## Task 2:-Create a predictive model with implementation of different classifiers on liver patient diseases dataset to predict liver diseases.

            1.after data preporcessing the data was tested under different machine learning models

            2.normal approcach and the optimization techniques were not giving better accuracy on the given data.
                except svc model which gave 86 % accuracy after optimization with better segragation between FN,FP

            3. threshold setting has given the better result above 95% accuracy with very few FP,FN
                 there are 3 models which giving more than 90% of accuracy which are
                 **RANDOM FOREST**, **XGB** AND **GRADIANTBOOSTING**

                 out of these RANDOM FOREST PERFORMING VERY WELL compared to these 2
                 
                 
### Task3:- Create an analysis to show on what basis you have designed your model.

main focus was to reduce the number of `false postive` and `false negative` values in the classification process

            1.analysis is done on  tpr,fpr and threshold values and segregated the balacned threshold value to get
               balanced  FP and FN.
