#Τίτλος Εργασίας: Augmented D&D

Σκεντερίδης Κωνσταντίνος
Π2014221

##Παραδοτέο 1

Augmented Reality Application

##Παραδοτέο 2

ΓΡΑΠΤΗ ΑΝΑΦΟΡΑ---

![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/DungeonsAndDragonsLogo_zps0hrx2zpp.jpg)
**Δημιουργία εφαρμογής Augmented Reality**

***AUGMENTED DUNGEONS & DRAGONS***

Σκεντερίδης Κωνσταντίνος

Α.Μ.: Π2014221

Η Ανάπτυξη της συγκεκριμένης εφαρμογής, έχει ως σκοπό την ενίσχυση (enhance) ενός προϋπάρχοντος επιτραπέζιου παιχνιδιού, με την χρήση εργαλείων ανάπτυξης επαυξημένης πραγματικότητας.

Το επιτραπέζιο παιχνίδι με το οποίο θα ασχοληθεί η εφαρμογή αυτή, είναι το παιχνίδι ρόλων Dungeons & Dragons.

Το παιχνίδι περιλαμβάνει μηχανισμούς και κανόνες που είναι κατάλληλοι για ενίσχυση του περιεχομένου του με την χρήση επαυξημένης πραγματικότητας.

Στόχος είναι η εφαρμογή να παρέχει ένα επιπλέον επίπεδο λεπτομέρειας στο παιχνίδι, χρήση ήχων και γραφικών που να ενισχύουν την εμπειρία (gaming experience) και γενικά να το κάνουν ακόμα πιο ελκυστικό στους παίκτες.

Τα εργαλεία με τα οποία θα υλοποιηθεί η εφαρμογή επαυξημένης πραγματικότητας είναι, η game engine της Unity 5 και το εργαλείο Vuforia ως plugin στην Unity.

Επιπλέον η υλοποίηση θα γίνει για εκτέλεση σε android smartphone.

Δεν κατέβασα κάποια συγκεκριμένα παραδείγματα για να χρησιμοποιήσω και να αλλάξω κάποιον κώδικα, αλλά μελέτησα μέσα από διάφορα tutorials, τον βασικό τρόπο λειτουργίας της Vuforia στην Unity και την διαδικασία δημιουργίας διαφόρων μοτίβων για tracking.

**Χαρακτηριστικά της εφαρμογής**

Η εφαρμογή συνοδεύεται από διάφορα μοτίβα tracking που έχω ορίσει και εκτυπώσει σε απλό χαρτί Α4, τα οποία αφού έκοψα σε μικρά τετράγωνα, κόλλησα λίγα επίπεδα χαρτιού παραπάνω ώστε να είναι πιο ανθεκτικά.

Η εφαρμογή ξεκινάει στο android smartphone όπου και κάνει χρήση της κάμερας της συσκευής, ώστε να πραγματοποιήσει το tracking των παραπάνω μοτίβων (patterns).

Εδώ βλέπουμε 2 από τα tracking μοτίβα που χρησιμοποιώ στα παραδείγματα.

![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/previewTracking1_zpshyuju08r.jpg)![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/previewTracking2_zpslcahe2u4.jpg)

Η κάμερα όταν δει και καταλάβει αυτά τα μοτίβα, εμφανίζει επάνω τους το ανάλογο 3D αντικείμενο που έχει οριστεί στην Unity.

Η εφαρμογή περιλαμβάνει ένα Graphical User Interface (GUI) με το οποίο ο παίκτης μπορεί να έχει πρόσβαση σε κάποιες λειτουργίες.

Στα δεξιά εμφανίζονται τα πορτραίτα των χαρακτήρων/παικτών που συμμετέχουν, τα οποία όταν πατηθούν, ανοίγουν την καρτέλα με τα αντικείμενα που κατέχει ο κάθε παίκτης, διάφορες πληροφορίες για τα στοιχεία του χαρακτήρα και άλλες χρήσιμες πληροφορίες που αφορούν τον κάθε παίκτη.

Στα αριστερά της οθόνης εμφανίζονται κάποια εικονίδια που το καθένα παρέχει κάποια λειτουργία. Μια λειτουργία εμφανίζει κάποιον χάρτη που έχουν αγοράσει οι παίκτες ( τον εμφανίζει μονάχα εάν έχουν αγοράσει κάποιον χάρτη, επομένως είναι στοιχείο του gameplay). Μια άλλη λειτουργία εμφανίζει μια γενική εικόνα του τοπίου/περιβάλλοντος (Environment) στο οποίο βρίσκονται οι παίκτες. Η επόμενη λειτουργία εμφανίζει τον τοπικό χάρτη του περιβάλλοντος που έχουν εξερευνήσει επιτυχώς οι παίκτες.

Επιπλέον το κάθε 3D μοντέλο του κάθε παίκτη/χαρακτήρα, εμφανίζει μια health\_bar έτσι ώστε ο παίκτης να βλέπει ανά πάσα στιγμή το ποσοστό ενέργειας που έχει απομείνει στον χαρακτήρα του.

Τα 3D αντικείμενα μπορούν να αλληλεπιδρούν μεταξύ τους όταν και όπου αυτό κριθεί χρήσιμο, περισσότερο για trigger/ενεργοποίηση κάποιον λειτουργιών παρά για physics simulation των μοντέλων.

Το smartphone θα ήταν καλό να έχει κάποιου είδους στήριξη σε σταθερό σημείο και να κοιτάει σε ένα grid τυπωμένο σε απλό χαρτί Α4. Το grid αυτό μπορεί με την χρήση ενός άλλου tracker να επαυξηθεί και να παρουσιάζει με γραφικά οτιδήποτε χρειάζεται από το παιχνίδι. Απλά το grid θα είναι ορατό και θα μετακινούν οι παίκτες τους χαρακτήρες τους (trackers) πάνω σε αυτό.

Ιδανικά η εφαρμογή θα υποστηρίζει multiplayer, έτσι ώστε το grid να είναι στην μέση , και ο κάθε παίκτης να έχει μπροστά του το smartphone του παρακολουθώντας την ίδια σκηνή από διαφορετικές οπτικές γωνίες και αλληλεπιδρώντας ο καθένας με τον χαρακτήρα του.

**Development Log**

Μέχρι στιγμής έχω υλοποιήσει αρκετά στοιχεία της εφαρμογής , από την βασική λειτουργία της επαυξημένης πραγματικότητας, μέχρι ένα βασικό GUI που λειτουργεί ως σκελετός για οποιαδήποτε αλλαγή χρειαστεί να γίνει.

Στην συνέχεια θα προσπαθήσω να υλοποιήσω το multiplayer και ότι άλλο χρειαστεί.

**ΑΡΧΙΚΑ ΣΚΙΤΣΑ ΠΡΟΣΧΕΔΙΑΣΜΟΥ ΤΗΣ ΕΦΑΡΜΟΓΗΣ**

**(**διάφορα γρήγορα σκίτσα και κείμενο στα οποία σχεδίασα πώς ήθελα να λειτουργεί η εφαρμογή**)**

![D&D logo](https://github.com/courses-ionio/mm/blob/master/projects_2016/%CE%A02014221/Images/AugmentationToolForDnD_roughSketch.jpg)![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/Sketching_zpsxzqycbyj.jpg)
**ΕΙΚΟΝΕΣ**
**(**διάφορες εικόνες από την εφαρμογή**)**
![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/PB081557_zps7iqvlbya.jpg)

![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/PB081558_zpsath3iwj9.jpg)![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/PB081559_zpsgzycj0tp.jpg)

![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/PB081560_zpstwzjkbc5.jpg)

![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/PB081561_zpsnp4exchi.jpg)

![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/PB081564_zpswjc6tv2z.jpg)

![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/PB081565_zpsnubbn3dp.jpg)

![D&D logo](http://i1380.photobucket.com/albums/ah166/Konstantinos_Skenteridis/PB081566_zpsmzmvhgmx.jpg)

**Links απο σχετικά εκπαιδευτικά video που παρακολούθησα**

https://library.vuforia.com/articles/Solution/Compiling-a-Simple-Unity-Project
https://unity3d.com/learn/tutorials/modules/intermediate/live-training-archive/modal-window
https://www.youtube.com/watch?v=87R0PziLDJ0&index=2&list=PLj0TSSTwoqAyOvc2zvdWNoO-jtMZkMDIC
https://www.youtube.com/watch?annotation_id=annotation_3111735289&feature=iv&index=10&list=PLj0TSSTwoqAyOvc2zvdWNoO-jtMZkMDIC&src_vid=87R0PziLDJ0&v=ViZto58MgjM
https://www.youtube.com/watch?v=H28AJulyJ3w
https://www.youtube.com/watch?v=LiPYy2DnLIQ
https://www.youtube.com/watch?v=tFyN4AlYN6w


Για τους 3d animated χαρακτήρες, έκανα μια αναζήτηση για free 3d animated models.
http://tf3dm.com/download-page.php?url=death-knight-rig-12712

Για τα 2d γραφικά του GUI πήρα διάφορα screenshots απο κάποια games και τα ένωσα/άλλαξα όπως ήθελα στο photoshop.
Τα γραφικά αυτά λειτουργούν ώς placeholders γιατί τα γραφικά θα πρέπει να προσαρμόζονται στο ανάλογο "party" που δημιουργούν οι παίκτες που παίζουν D&D. Δηλαδή θα δημιουργούνται custom πορτραίτα χαρακτήρων, custom 3d model για κάθε χαρακτήρα κτλ.Επομένως μου ήταν πιο χρήσιμο να τα στρώσω πρώτα αυτά ώστε να μπορώ να αλλάζω άνετα τις εικόνες που θέλω και τα ανάλογα models όταν αυτά δημιουργηθούν.

##Παραδοτέο 3

...

##Παραδοτέο 4

...

##Tελική Αναφορά

...