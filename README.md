# regression_lin-aire
## Prediction le prix de vente d'une maison:
### Les bibliotheques importer:
#### La bibliotheque Pandas, matplotlib, numpy, seaborn,
** j'ai importee les classes dont j'ai besoin depuis scikit-learn: 
  - from sklearn.metrics import mean_squared_error
  - from sklearn.linear_model import LinearRegression
  - from sklearn.model_selection import KFold
#### Traitement des caracteristiques en creant la fonction:
 [def transform_caracteristiques(dataFrame,ele_pourcentage):]
#### Selection des caracteristique en creant la fonction :
 [def select_caracteristique(dataFrame,val_unique_caracteristique=1029 ,coeff_corr=0.3):]
#### Entrainement et test en creant la fonction : 
 [def train_and_test(dataFrame,k=0):]
