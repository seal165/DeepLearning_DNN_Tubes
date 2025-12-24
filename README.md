# DeepLearning_DNN_Tubes

📌 Deskripsi Singkat
Project ini merupakan penerapan Deep Neural Network (DNN) untuk menyelesaikan permasalahan klasifikasi biner pada data numerik menggunakan Python dan TensorFlow di Google Colab. Tujuannya untuk melihat bagaimana deep learning dapat mempelajari pola non-linear dari data numerik.

🎯 Tujuan
- Membangun dan mengevaluasi model deep learning yang mampu:
- Mempelajari pola pada data numerik
- Melakukan klasifikasi biner dengan akurasi tinggi
- Menunjukkan proses training melalui grafik loss dan accuracy

📊 Dataset
- Dataset yang digunakan berupa data numerik dengan target biner (0 dan 1).
- Dataset ini digunakan untuk studi kasus klasifikasi dan dibagi menjadi data latih dan data uji sebelum masuk ke tahap training.
Sumber dataset: https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset)

🏗️ Arsitektur Model
Model yang digunakan adalah Deep Neural Network dengan struktur:
- Input layer: sesuai jumlah fitur
- Hidden layer 1: 64 neuron (ReLU)
- Hidden layer 2: 32 neuron (ReLU)
- Hidden layer 3: 16 neuron (ReLU)
- Dropout di setiap layer untuk mencegah overfitting
- Output layer: 1 neuron (Sigmoid)

⚙️ Konfigurasi Training
- Optimizer: Adam
- Loss function: Binary Crossentropy
- Metrics: Accuracy
- Epoch: 50
- Batch size: 16

📈 Hasil
- Model berhasil mencapai akurasi sekitar 97% pada data uji.
- Grafik loss dan accuracy menunjukkan proses pembelajaran yang stabil dan tidak mengalami overfitting.

Project untuk tugas besar Deep Learning
