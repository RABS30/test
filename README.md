# Monitoring IoT dengan Django dan bot telegram
## 📌 Fitur 
- ✅ Authentication 
- ✅ Real-time monitoring and device control
- ✅ Bot telegram
- 

## 📑 Detail
### Authentication
- Menggunakan django-allauth sebagai dasar authentication. 
- Pengguna login dengan menggunakan email.
- pengguna dapat mengubah dan mereset kata sandi yang akan dikirim melalui email.
- terdapat fitur lupa kata sandi. Pengguna menggunakan emailnya dan URL untuk membuat kata sandi baru akan dikirim melalui email.

### Real-time monitoring and device control
- Terdapat grafik yang menampilkan data secara real-time yang dikirm langsung dari perangkat IoT menggunakan protokol MQTT.
- Terdapat grafik yang menampilkan data dalam periode waktu tertentu, seperti harian, mingguan, bulanan dan tahunan.
- Kendalikan perangkat IoT hanya dengan menekan button.

### Bot telegram
- Kendalikan perangkat IoT dari telegram secara real-time.
- Bot telegram dilengkapi authentication untuk memastikan tidak sembarang orang dapat menggunakannya.
- Authentication menggunakan token JWT untuk memverifikasi pengguna dan membatasi waktu login pengguna.
- Satu akun website hanya bisa digunakan pada satu akun telegram (tidak bisa login di banyak akun telegram secara bersamaan).
