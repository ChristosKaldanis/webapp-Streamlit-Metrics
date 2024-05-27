# webapp-Streamlit Metrics
# Info

# Περιγραφή Εφαρμογής
Η εφαρμογής μας Streamlit Metrics βοηθά στην οπτικοποίηση, ανάλυση, ταξινόμηση και συσταδοποίηση των δεδομένων από csv ή xlsx αρχεία dataset.

# Λειτουργικότητα της Εφαρμογής
Αρχικά, εισάγουμε το αρχείο (xlsx ή csv) το οποίο περιέχει το dataset με το button Βrowse Files. Ύστερα, εμφανίζεται στo tab Raw Data το dataset με τη μορφή πίνακα και επιπλέον από κάτω ενα προεπιλεγμένο διαγραμμα που μορφοποιείται ανάλογα με τη μορφή του κώδικα το οποίο υλοποιήθηκε για το συγκεκριμένο dataset (WorldBank) που έχει αναλυθεί. Προχωράμε στο tab 2D Visualization όπου οπτικοποιόυνται χαρακτηριστικά που επιλέγονται από τον χρήστη ανάλογα και με τον reduction αλγόριθμο που έχει επιλεχθεί. Στο επόμενο tab που αφορά τους αλγορίθμους ταξινόμησης επιλέγεται ο αλγόριθμος που ενδιαφέρει τον χρήστη, τα χαρακτηριστικά που επιθυμεί να αναλύσει, ο reduction αλγόριθμος για την καλύτερη κατανομή των χαρακτηριστικών καθώς και η παράμετρος του αλγόριθμου ταξινόμησης (εάν χρειάζεται). Στη συνέχεια υπάρχει το tab με τους clustering αλγόριθμους όπου πάλι ο χρήστης ακολουθεί την ίδια λειτουργική διαδικασία που ακολούθησε και στο classification tab, ώστε να γίνει η συσταδοποίηση σύμφωνα με τα labels του dataset. Τέλος στα επόμενα δύο tabs ο χρήστης μπορεί να διαβάσει πληροφορίες σχετικά με την εφαρμογή την ομάδα της και τη λειτουργικότητα της. Εάν όλα καταχωρηθούν σωστά εμφανίζεται μήνυμα επιτυχίας Done! αλλιώς μήνυμα σφάλματος.

# Ομάδα Ανάπτυξης
Η ομάδα ανάπτυξης της εφαρμογής αποτελείται απο δύο ατομα, τον Καλδάνη Χρήστο προπτυχιακό φοιτητή στο τμήμα Πληροφορικής του Ιονίου Πανεπιστημίου και υπεύθυνο υλοποίησης της εφαρμογής και από τον Κωνσταντίνο Λύγκουρη που είναι επίσης προπτυχιακός φοιτητής στο τμήμα Πληροφορικής του Ιονίου Πανεπιστημίου.

# Tasks
Τα Tasks που υλοποιήθηκαν από κάθε μέλος είναι:

O Καλδάνης Χρήστος ανέλαβε τα εξής: Raw Data, 2D Visualization, Classification Algorithms, Clustering Algorithms, Docker, Github, Αναφορά σε LaTeX

O Λύγκουρης Κωνσταντίνος ανέλαβε τα εξής: UML Diagrams, Κύκλος Ζωής Έκδοσης Λογισμικού, Συγγραφή των Result και Info tabs.

# URL Εφαρμογής
Για να δοκιμάσετε την εφαρμογή μας, **έπειτα από αίτημα του χρήστη προς τον υπεύθυνο της εφαρμογής Καλδάνη Χρήστο**, θα ενεργοποιηθεί το παρακάτω URL για deploy: http://192.168.1.3:8501/
