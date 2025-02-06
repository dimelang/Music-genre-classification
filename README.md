## Music Genre Classifiction Using Stacking MFCC and Mel-Spectogram Features and Resnet-18 With Attention Mechanism-Bidirectional LSTM Hybrid Approach

---

Penelitian ini menggunakan model bybrid antara ResNet18 yang dilengkapi dengan attention mechanism CBAM (Convolutional Block Attention Module) dengan BiLSTM untuk meningkatkan akurasi dalam klasifikasi genre musik. Selain itu, input untuk kedua jaringan merupakan gabungan antara dua fitur spektral, yaitu mel-spectrogram dan MFCC.

Hasil eksperimen yang dilakukan menggunakan dataset [GTZAN](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification/data) menunjukkan bahwa kombinasi mel-spectrogram dan MFCC, serta penambahan CBAM, mampu mengklasifikasikan genre musik dengan tingkat akurasi sebesar 95,60% pada validasi dan 95,30% pada pengujian.

----
## Arsitektur
![Architecture](https://github.com/dimelang/Music-genre-classification/architecture.png)



