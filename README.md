## Implementasi Tutorial 8

**1. Membuat Particle Environment (Hujan)**

- Menambahkan GPUParticles2D dan menentukan process material
- Merubah amount dan lifetime agar partikel terlihat banyak dan lama
- Tentukan scale dan emission shape untuk merubah lokasi titik hujan agar menjadi luas
- Velocity, spreadm dan gravitasi untuk mengatur arah jatuh dan persebaran hujan
- Agar meliputi seluruh map, dapat meningkatkan visibility rect
- Penggunaan trail agar hujan seperti air jatuh, tidak sekedar butir

**2. Membuat Particle Trail saat Player Jalan**

- Menambahkan GPUParticles2D pada scene player
- Untuk partikel player ubah lifetime menjadi 0.5 agar tidak terlalu banyak
- Gravity y menjadi negatif agar terbang ke atas
- Spread 180 derajat agar tersebar merata dan local coord enabled=false agar mengikuti posisi player
- Pada GDScript dapat dilakukan implementasi lebih lanjut agar pertikel hanya hidup ketika player berjalan dan di darat

**3. Balancing pada Spawn Rate Musuh**

- Atur jumlah spawning time pada node spawner untuk mengurangi spawn rate musuh
- Jumlah tersebut dapat diatur lebih lanjut agar game tidak terlalu mudah maupun sulit
