# Predict Exited Employee
Selamat datang dalam proyek mengenai "Pengaruh Keluarnya Karyawan di Suatu Perusahaan". Dalam proyek ini, saya akan melakukan tahapan tahapan seperti persiapan data ,melakukan pemodelan dengan tiga model supervised learning,dan membandingkan hasil akurasi dari ketiga model.Data yang didapat mencakup berbagai kolom seperti RowNumber,CustomerId,Geography,Gender, Age,Tenure,Balance, NumOfProducts, HasCrCard,IsActiveMember, EstimatedSalary, dan Exited.

Data : https://raw.githubusercontent.com/Rietaros/kampus_merdeka/main/SC_HW1_bank_data.csv

  
## Persiapan Data 
Proyek ini dimulai dengan tahap persiapan data, di mana saya akan mengimpor perpustakaan-perpustakaan yang diperlukan, mengimpor dataset, dan melakukan proses pra-pemrosesan seperti mencari missing value,inacurated value,inconsisten value,data duplikat, dan mencari korelasi antar kolom fitur dan target untuk memastikan data dalam kondisi yang optimal . Langkah selanjutnya adalah pembagian dataset menjadi data pelatihan dan data uji (Train-Test Split), yang akan mengukur performa model dengan lebih akurat.

## Supervised Learning Model
Setelah data data sudah clean dan optimal, selanjutnya dilakukan pemodelan menggunakan pendekatan supervised learning karena data tersebut berlabel.Dalam proses ini, saya akan membangun, melatih, dan menguji tiga model supervised learning yang berbeda seperti Logistic Regression,K-Nearsest Neighbors (KNN), dan Random Forest.Tidak hanya itu , performa model dioptimalkan dengan melakukan hyperparameter tuning menggunkan GridSearchCV.Saya akan membandingkan hasilnya, mempertimbangkan faktor-faktor seperti akurasi, presisi, recall, dan F1-score, untuk mendapatkan pemahaman yang mendalam tentang efektivitas masing-masing model.

## Kesimpulan  
Kesimpulan yang komprehensif berdasarkan hasil evaluasi model, termasuk hasil dari proses hyperparameter tuning. Kesimpulan ini akan memberikan wawasan yang mendalam tentang faktor-faktor apa yang paling memengaruhi keputusan karyawan untuk meninggalkan perusahaan, serta model mana yang paling efektif untuk memprediksi perilaku tersebut.
