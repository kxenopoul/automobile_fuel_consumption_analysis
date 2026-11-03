# Αναλυση Δεδομενων Αυτοκινητων και Προβλεψη Καταναλωσης Καυσιμου

### Περιγραφη

Στο project αυτο αναλυουμε δεδομενα 398 αυτοκινητων με τη χρηση Python.

Σκοπος ειναι να εξετασουμε πως χαρακτηριστικα οπως το βαρος, η ιπποδυναμη και ο κυβισμος σχετιζονται με την καταναλωση καυσιμου.

Επισης, χρησιμοποιουμε μοντελα παλινδρομησης για την προβλεψη της καταναλωσης σε L/100Km.

### Εργαλεια

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn και Jupyter Notebook.

### Τι εχει ολοκληρωθει

- Φορτωση και αρχικος ελεγχος δεδομενων.
- Data Cleaning και αντικατασταση ελλιπων τιμων.
- Μετατροπη MPG σε L/100Km.
- Αναλυση συσχετισεων μεταξυ μεταβλητων.
- Οπτικοποιηση δεδομενων με Regplot και Boxplot.
- Αρχικη εκπαιδευση Simple Linear Regression και δημιουργια προβλεψεων.

### Work in Progress

Το project δεν εχει ολοκληρωθει ακομα.

Στα επομενα βηματα θα γινουν:

1. Διαχωρισμος δεδομενων σε Training και Test Sets.
2. Αξιολογηση του Simple Linear Regression με R² και MSE.
3. Εφαρμογη Multiple Linear Regression.
4. Εφαρμογη Polynomial και Ridge Regression.
5. Συγκριση των αποτελεσματων των μοντελων.
6. Εξαγωγη τελικων συμπερασματων.

Το repository θα ενημερωνεται σταδιακα με νεο κωδικα, αποτελεσματα και αναλυσεις.

### Dataset

Χρησιμοποιειται το Auto MPG Dataset απο το UCI Machine Learning Repository.

Source: https://archive.ics.uci.edu/dataset/9/auto+mpg

Citation: Quinlan, R. (1993). Auto MPG. UCI Machine Learning Repository.

DOI: https://doi.org/10.24432/C5859H

License: CC BY 4.0

Το αρχικο dataset χρησιμοποιειται για εκπαιδευτικους σκοπους. Οι μετατροπες περιλαμβανουν συμπληρωση ελλιπων τιμων και μετατροπη της καταναλωσης απο MPG σε L/100Km.
