# Kesehatan-Mental-Menggunakan-Model-LSTM

## Latar Belakang Proyek

Kesehatan mental adalah aspek penting dari kesejahteraan individu yang mencakup keseimbangan emosional, psikologis, dan sosial. Masalah kesehatan mental, seperti depresi, kecemasan, dan stres, telah menjadi tantangan global yang signifikan, dengan prevalensi yang terus meningkat akibat tekanan sosial, ekonomi, dan kehidupan modern. Menurut Organisasi Kesehatan Dunia (WHO), lebih dari 280 juta orang di seluruh dunia mengalami depresi, dan hampir satu dari delapan individu diperkirakan hidup dengan gangguan kesehatan mental. Kesehatan mental yang terganggu tidak hanya memengaruhi kualitas hidup individu, tetapi juga berdampak pada produktivitas, hubungan sosial, dan stabilitas komunitas. Dalam upaya memberikan dukungan awal terhadap masalah kesehatan mental, proyek ini mengembangkan chatbot berbasis kecerdasan buatan (AI) yang dirancang untuk mengenali tanda-tanda awal gangguan mental dan memberikan dukungan emosional. Chatbot ini menggunakan model Long Short-Term Memory (LSTM) untuk memahami pola komunikasi pengguna dan mengklasifikasikan maksud percakapan mereka ke dalam kategori tertentu, seperti "depresi," "kecemasan," atau "stres." Dengan pendekatan ini, chatbot dapat berperan sebagai langkah awal bagi individu sebelum mendapatkan akses ke profesional kesehatan mental.

## Deskripsi Proyek

Model LSTM yang dikembangkan dalam proyek ini dirancang untuk memproses data sekuensial seperti teks percakapan. Model ini melibatkan lapisan embedding untuk mengubah teks menjadi representasi numerik, lapisan LSTM bertingkat untuk menangkap hubungan temporal antar kata, serta lapisan dense untuk klasifikasi intent. Regularisasi dengan dropout digunakan untuk mencegah overfitting. Model ini dilatih selama 60 epoch menggunakan optimasi Adam dan fungsi loss sparse categorical cross-entropy, dengan batch size sebesar 10. Pada akhir proses pelatihan, model mencapai akurasi sebesar 98.3%, menunjukkan kemampuan yang sangat baik dalam mengklasifikasikan intent dari input pengguna.

Aplikasi chatbot ini dibangun menggunakan Streamlit untuk menyediakan antarmuka web yang interaktif. Fitur utama meliputi riwayat percakapan yang memungkinkan pengguna melihat pesan sebelumnya dan respons chatbot, serta respons adaptif yang dipersonalisasi untuk memberikan rasa empati kepada pengguna. Dengan pendekatan ini, chatbot dapat memberikan dukungan awal yang cepat dan efisien, meningkatkan kesadaran pengguna akan pentingnya kesehatan mental, serta membantu mereka memahami bahwa berbicara tentang perasaan adalah langkah pertama menuju pemulihan.

Proyek ini bertujuan untuk mendeteksi tanda-tanda awal gangguan mental, memberikan dukungan awal, dan meningkatkan aksesibilitas informasi tentang kesehatan mental. Meskipun chatbot ini tidak dimaksudkan untuk menggantikan profesional medis, keberadaannya dapat menjadi langkah awal yang signifikan, terutama di wilayah dengan keterbatasan akses ke layanan kesehatan mental. Dengan inovasi berbasis AI ini, proyek ini menunjukkan potensi teknologi dalam mendukung kesehatan mental masyarakat secara lebih luas.


Referensi:

https://www.kaggle.com/datasets/elvis23/mental-health-conversational-data/data

https://github.com/Mazcho/Implementasi-Sequential-LSTM-Model-dalam-Chatbot-Kesehatan-Mental-Remaja-Menggunakan-TensorFlow?tab=readme-ov-file

https://github.com/Vikranth3140/Mental-Health-Support-Chatbot

https://www.who.int/news-room/fact-sheets/detail/depression

https://docs.streamlit.io

Hochreiter, S. (1997). Long Short-term Memory. Neural Computation MIT-Press.

