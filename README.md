# Early-Warning-System-Apps

Early Warning System adalah sebuah system yang berguna untuk memantau hingga memberitahukan aktivitas gunung vulkanik. Perancangan System ini terdiri atas 3 bagian yakni :
- Early Warning Arduino : berisikan Code untuk arduino yang menjadi device pemantau (Transmitter sebagai pengirim yang berada pada daerah aktivitas vulkanik dan receiver sebagai penerima dan pengunggah ke Firebase)
- Early Warning System : aplikasi berbasis Flutter yang digunakan sebagai pemantau aktivitas vulkanik dengan mengambil data dari device pemantau melalui Firebase
- Early Warning System Notification : aplikasi berbasis native Android yang digunakan sebagai pemberitahuan dengan notifikasi apabila ada aktivitas vulkanik yang mulai meningkat 
