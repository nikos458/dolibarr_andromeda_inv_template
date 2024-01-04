# dolibarr_andromeda_inv_template
Invoice template based on sponge template for dolibarr. Greek QR code AAEDE

Το template περιέχει το QR code από την ΑΑΕΔΕ μέσω του mydata module v1.8.

Το QR εμφανίζεται αφού έχουμε ενεργοποιήσει το swiss QR του  dolibarr pdf settings.
Επίσεις εμφανίζεται το mark και uid στο κάτω μέρος της σελίδας.

Στο κάτω μέρος του τιμολογίου κατώ από την μεθοδο πληρωμής εμφανίζεται η παρακράτιση που έχουμε στο extrafield του mydata και το πληρωτέο ποσό το οποίο υπολογίζεται αυτόματα από το συνολικό ποσό του τιμολογίου μείον την παρακράτηση. Εάν δεν έχουμε βάλει ποσό στην παρακράτηση ή είναι 0 τότε τα extafields δεν εμφανίζονται.


![qrTempInv](https://github.com/nikos458/dolibarr_andromeda_inv_template/assets/60128801/12b5ae37-52ba-4722-a321-c7415122b74c)


Εάν θέλουμε να εμφανίζονται οι Δνσεις αποστολής ενεργοποιούμε την επιλογή στο pdf settings. Σε αυτή την περίπτωση η δνση αποστολής εμφανίζεται μόνο όταν έχουμε επιλέξει στο τιμολόγιο shipping contact διαφορετικά δεν θα εμμφανίζεται.

![header_delivery_address2](https://github.com/nikos458/dolibarr_andromeda_inv_template/assets/60128801/cf0d28db-2693-476d-800c-f0fca12b062b)


Για να το χρησιμοποιήσετε πρέπει να το βάλετε στο folder htdocs/core/modules/facture/doc/ του dolibarr και το ενεργοποιείτε στο invoice module. 

Έχει δοκιμαστεί με την έκδοση 18.0.4.
