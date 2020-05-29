# E-HARVEST (Ευφυής Συγκομιδή)

Έργο του Εσπερινού ΕΠΑΛ Ευόσμου με στόχο τη συμμετοχή στον 2ο Πανελλήνιο Διαγωνισμό Ρομποτικής Ανοιχτών Τεχνολογιών.

Τίτλος Έργου: E-HARVEST - Ευφυής Συγκομιδή

Όνομα Ομάδας: HARVEL

Συμμετέχοντες μαθητές:Αγοραστούδης Θωμάς, Βαρσάμης Νικόλαος, Θεοφανίδης Αντώνης, Κύριος Νικόλαος, Πασχαλίδης Νικόλαος, Σαμουρέλης Χρήστος, Σιώπης Ιωάννης, Τσουφλίδης Λεωνίδας, Φράγκος Θωμάς

Υπεύθυνη Εκπαιδευτικός: Τσαβέλη Δάφνη, ΠΕ84

ΓΕΝΙΚΑ

Η ολοκληρωμένη διαχείριση μιας αγροτικής δραστηριότητας με την αξιοποίηση των  σύγχρονων τεχνολογιών αποτελεί τα τελευταία χρόνια αντικείμενο ερευνών και μελέτης τόσο σε επιστημονικό επίπεδο όσο και από την πλευρά ιδιωτικών εταιριών. Ο στόχος είναι η καλύτερη αγροτική εκμετάλλευση, με πολλαπλά οφέλη για τους αγρότες, την παραγωγή αλλά ταυτόχρονα και την προστασία του  περιβάλλοντος. Είναι μια καινοτόμα κατασκευή με στόχο τη βελτίωση της συγκομιδής γεωργικών - αγροτικών προϊόντων.

Η κατασκευή μας στηρίζεται ακριβώς σε αυτή την ιδέα. Αποτελείται από ένα αυτοκινούμενο όχημα που μεταφέρει 1 καλάθι συγκομιδής. Το όχημα ακολουθεί μια συγκεκριμένη πορεία, πηγαίνοντας στο σημείο όπου βρίσκετε ο αγρότης που μαζεύει την παραγωγή του. Όταν το καλάθι γεμίσει, το όχημα πηγαίνει στο σημείο εκφόρτωσης όπου ένας ρομποτικός μηχανισμός αδειάζει το φορτίο. Στη συνέχεια φορτώνει ένα άδειο καλάθι στο όχημα και αυτό επιστρέφει στον αγρότη. Ο αγρότης μπορεί και ελέγχει το όχημα μέσα από  κουμπιά. Η κίνηση του οχήματος γίνεται με 2 κινητήρες που ελέγχονται από ένα Arduino Uno.    

ΑΝΑΛΥΤΙΚΑ

*Αυτοκινούμενο όχημα*

Είναι ένα ερπυστριοφόρο όχημα που μετακινείται αυτόνομα. Ο στόχος του είναι να μεταφέρει ένα καλάθι στον αγρότη. Με το πάτημα ενός πλήκτρου το όχημα ακολουθεί, με τη χρήση ενός αισθητήρα υπερήχων, μια συγκεκριμένη διαδρομή. Ο αισθητήρας του επιτρέπει να διατηρεί ορισμένη απόσταση από ένα αντικείμενο π.χ. ταινιο-λωρίδα. Όταν συναντήσει τον αγρότη στο τέλος της διαδρομής, σταματάει. Το σταμάτημα γίνεται διαβάζοντας ένα αισθητήριο υπερήχων. Ο αγρότης το απενεργοποιεί μέσω ενός κουμπιού. Όταν φορτωθεί το καλάθι, ο αγρότης με ένα άλλο κουμπί, στέλνει το ερπυστριοφόρο όχημα στην βάση για να γίνει η εκφόρτωση του καλαθιού.     

*Ρομποτικός μηχανισμός εκφόρτωσης*

Ο μηχανισμός εκφόρτωσης είναι ένα ρομποτικό σύστημα που εκφορτώνει από το όχημα το γεμάτο από προϊόντα καλάθι και το μεταφέρει ένα σημείο συλλογής. Όταν το όχημα βρεθεί στο σημείο εκφόρτωσης, εντοπίζεται από έναν αισθητήρα υπερύθρων και δίνεται η εντολή σε ένα  βραχίονα να εκταθεί και σηκώσει το καλάθι. Στη συνέχεια ο βραχίονας στρίβει και τοποθετεί το καλάθι στο σημείο μεταφόρτωσης. Κατόπιν περιστρέφεται 180ο και φορτώνει ένα άδειο καλάθι και το μεταφέρει στο όχημα. Τέλος επανέρχεται στην αρχική του θέση. 
Η κατασκευή πραγματοποιήθηκε με τη χρήση του πακέτου Gigo S4A Programming Bricks. Το πακέτο αποτελείται από μια πλακέτα βασισμένη σε Arduino Leonardo. Ο προγραμματισμός έγινε από την προγραμματιστική πλατφόρμα S4A (Scratch για Adruino). Περιέχει αισθητήρια και  διάφορα δομικά υλικά για κατασκευή ρομποτικών εφαρμογών. Το συγκεκριμένο πακέτο δόθηκε δωρεάν στο σχολείο από την WRO.

*Υλικά*

1. Eρπυστριοφόρο όχημα
2. Arduino Uno
3. Αισθητήρες Υπερήχων HC-SR04
4. L298N Dual H-Bridge Motor Driver 
5. GIGO S4A programming Bricks
6. Μπαταρίες 9V
7. Μακετόχαρτο
8. Χρώματα

