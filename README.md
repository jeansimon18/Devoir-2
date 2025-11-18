# Devoir-2
Devoir  2
Problème 1 [15 points], Construction des données et analyse sommaire
Dans cette question, vous reproduirez les intrants principaux de l’analyse de l’article « Expected EPS
× Trailing P/E Pricing Without Discounting ». Votre tâche consiste à recueillir les données pertinentes, à
calculer les variables clés et à fournir des informations descriptives initiales. Ce processus vise à reproduire
la construction des intrants utilisés dans la stratégie empirique de l’article.
a. Rédigez du code qui sélectionne aléatoirement un échantillon de 50 sociétés américaines cotées en
bourse de l’indice S&P 500 et recueille les informations suivantes pour chaque entreprise : les prix
quotidiens (ou mensuels, si requis par l’article) des actions, le bénéfice par action (BPA), et les ratios
prix-bénéfice (P/B) glissants. Vos données doivent correspondre à la fréquence et à l’intervalle de temps
utilisés dans l’article original. Utilisez WRDS comme source de données et assurez-vous que votre code
est facilement adaptable à un échantillon plus grand. [5 points]
b. En utilisant les données recueillies à la partie (a), calculez les rendements pour chaque action, estimez
le BPA attendu (tel que défini ou sous-entendu dans l’article), et calculez le ratio de prix donné par
le P/B glissant. Rapportez clairement votre code pour ces transformations. Assurez-vous que toute
hypothèse ou approximation soit explicitement énoncée. [5 points]
c. Fournissez des statistiques descriptives pour chacun des éléments suivants : prix de l’action, rendements
de l’action, BPA, P/B glissant, et le ratio composite BPA attendu × P/B glissant. Générez et étiquetez
clairement des graphiques de séries chronologiques de chaque série. Dans votre discussion, soulignez
toute caractéristique qui pourrait être importante pour les résultats empiriques plus loin dans le devoir
— par exemple, la persistance, les valeurs aberrantes ou les ruptures structurelles. [5 points]
