Projekti failide repositooriumis leiduvad kõik analüüsi, andmete manipulatsiooni ja mudelite testimisel kasutatud Jupyter Notebookid
Selguse huvides on erinevad protsessi sammud esitatud erladi notebook failidena

Spaceship Titanic Kaggle võistluse treening ja test alusandmestikud:
ST_train.csv
ST_test.csv

Andmete esialgsel analüüsil kasutatud notebookid:
spaceship-titanic_start.ipynb
spaceship-tit_addit_feature_selection.ipynb
spaceship-t_EDA_Cabin_analy.ipynb
spaceship-t_EDA_group_analy.ipynb
spaceship-t_EDA_name_analy.ipynb
spaceship-t_EDA_services_analy.ipynb

Puuduvate andmete asendamise protsessis kasutatud notebookid:
(notebookide päises on võimalik valida, kas laadida training või testing set andmetest)
spaceship-tit_NaN_imputation.ipynb
spaceship-tit_HomePlanet_predict.ipynb
spaceship-tit_Cabin_predict.ipynb
spaceship-tit_CryoSleep_impute.ipynb
spaceship-tit_Name_impute.ipynb
spaceship-tit_other_imputations.ipynb

Lõplike täiendatud andmestike kompileerimine:
spaceship-tit_compile_final_imputations.ipynb
spaceship-tit_feature_engineer.ipynb
(lõpliku kompileeritud faili salvestamise funktsioonis on võimalik valida kas salvestada training või testing andmestik)

Treenimiseks ja ennustamiseks valmis konstrueeritud csv failid:
ST_test_feature_final.csv
ST_train_feature_final.csv

Mudelite treenimine:
spaceship-tit_model_training.ipynb
spaceship-tit_model_featuretest.ipynb
spaceship-tit_RandomForest_improve.ipynb

Treenitud mudelite pickle failid:
trained_RandomForest.pkl
trained_Stacked.pkl
