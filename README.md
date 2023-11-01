![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/ef92f4f9-3f13-46cc-b11c-93471ddd7b17)


# AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes

## Penjelasan :

### 1. Klastering
Berikut ini merupakan data Pengunjung Mall setelah dilakukan klasterisasi untuk menentukan label pada data Pengunjung Mall untuk menentukannya disini menggunakan metode K-Means. Elbow method nilai klaster 5 merupakan nilai yang paling optimal karena penurunan inersia pada nomor klasternya seterusnya tidak lagi signifikan (perubahannya nilainya kecil). Kemudian cluster terbaik dilakukan pengujian dengan Silhouette Score dan Inertia didapatkan dengan nilai Silhouette Score: 0.554 dan Inertia : 44448.45544793369. Setelah mendapatkan hasil cluster terbaik kemudian disimpan kedalam file.csv disini saya menyimpan file dengan nama Mall_Customers_Clustered.csv.

![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/4b8c2782-7413-4b89-913c-6429f053cbd7)

Gambar 1.1 Import Library dan Import Dataset Mall_Customers.csv


![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/482dbe6d-84d8-475f-a7b4-33ad7e58eb8b)

Gambar 1.2 Membuat Elbow Method untuk menentukan nilai klaster terbaik
 
 
![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/45dfa3be-a58b-4564-812b-01342f3be640)

Gambar 1.3 Membuat Klasterisasi


![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/33955c41-cbba-49b1-9f9c-14a93f9b5724)

Gambar 1.4 Menentukan nilai Silhoutter Score dan Inertia


![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/eb1d9bc6-e26d-4b27-b922-478de554bd8f)

Gambar 1.5 Menyimpan Hasil Kluster dan Menampilkan Data yang Telah di Label


### 2.	Klasifikasi menggunakan SVM, K-NN, dan Naïve Bayes.
   
SVM :
Pada klasifikasi menggunakan SVM didapatkan hasil akurasi dari 3 jenis kernel yaitu Linear sebesar : 1.0, kernel RBF sebesar : 0.975, dan kernel Polynomial : 0.975.
 
 ![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/b2e59f47-b224-4900-af7a-70a93688a349)

Gambar 2.1 Klasifikasi menggunakan SVM

K-NN :
Pada klasifikasi menggunakan K-NN didapatkan hasil akurasi sebesar 0.97.

![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/f5432db4-0d48-4e3d-85b0-6f342482ead6)

Gambar 2.2 Klasifikasi menggunakan K-NN

Naive Bayes :
Pada klasifikasi menggunakan Naive Bayes didapatkan hasil akurasi sebersar 0.97.
 
![image](https://github.com/Rifqiakmals12/AI-Project-Classification-of-Mall-Visitors-Using-SVM-KNN-and-Naive-Bayes./assets/72428679/5bcebb53-8232-42ed-bd27-52aa1cb29dc8)
 
Gambar 2.3 Klasifikasi menggunakan Naive Bayes


Kesimpulannya metode klasifikasi yang paling baik yaitu menggunakan SVM dengan kernel linear yang hasil akurasinya mencapai 100%.
