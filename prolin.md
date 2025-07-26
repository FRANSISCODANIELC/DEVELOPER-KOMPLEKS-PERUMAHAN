Buatkan desain game edukasi matematika berbasis web berikut ini:

Judul game: Developer Kompleks Perumahan
Tujuan game: Pemain memaksimalkan keuntungan dengan membangun rumah, taman, jalan, dan Mushollah pada sebidang tanah dengan anggaran terbatas. Ini untuk pembelajaran materi Program Linear di SMA.

Spesifikasi prototype:
- Tampilan 2D sederhana.
- Tampilkan area lahan berbentuk grid 9x9.
- Pemain bisa memilih jenis bangunan melalui tombol yang diwakili icon:
  1. Rumah (biaya 50, nilai jual 120, kebahagiaan 5)
  2. Taman (biaya 15, nilai jual 0, kebahagiaan 7)
  3. Jalan (biaya 5, nilai jual 0, kebahagiaan 5)
  4. Mushollah (biaya 50, nilai jual 0, kebahagiaan 8)
  Keterangan :
	a. biaya = modal pembangunan (efek praktis ke keuntungan/kerugian)
	b. nilai jual = harga jual (efek praktis ke keuntungan/kerugian)
	c. kebahagiaan = tingkat kenyamanan personal membeli unit disini (efek mempengaruhi waktu pembelian unit. semakin tinggi nilai kebahagiaan, semakin cepat unit terjual)
	
- Setelah memilih jenis bangunan, klik di salah satu kotak grid untuk menempatkan bangunan (gunakan ikon sederhana atau warna berbeda untuk tiap jenis).
- Di sisi kanan layar, tampilkan panel informasi:
  - Total biaya
  - Total keuntungan
  - Sisa anggaran (contoh: anggaran awal 100)
- Gunakan HTML, CSS, dan JavaScript (tanpa framework) untuk implementasi awalnya.
- Buatkan kode yang sudah lengkap dalam satu file HTML, dengan CSS internal dan script JavaScript di dalamnya, supaya mudah dicoba.
- Fokus pada logika dasar dan visual sederhana (kotak grid, warna atau ikon sederhana), belum perlu database.

Output:
- Berikan file HTML lengkap dengan CSS dan JavaScript.
- Sertakan komentar di bagian penting agar mudah saya pahami.

Buatkan desain game edukasi matematika berbasis web berikut ini:

Judul game: Developer Kompleks Perumahan
Tujuan game: Pemain memaksimalkan keuntungan dengan membangun rumah, taman, jalan, dan Mushollah pada sebidang tanah dengan anggaran terbatas. Ini untuk pembelajaran materi Program Linear di SMA.

Alur dan tampilan game
- Login User
- Dashboard berisi tombol Main Menu: 
	- New Game
		- Singleplayer
			- Map_Singleplayer
				- Lahan_1_Map_Singleplayer (9x9)
					- Board game design
					- Menu tersedia
						- Tombol Jual
							Selesai membuat desain, masuk ke mode jual. Disini ada fitur simulasi proses penjualan otomatis. Game akan selesai jika semua unit sudah terjual habis. Menampilkan summary rincian modal, jumlah unit terjual, total hasil penjualan, waktu penjualan (yang sangat dipengaruhi oleh efek kebahagiaan)
							Terdapat tombol Skip (untuk melewati proses langsung ke summary) dan Selesaikan (Berfungsi menyelesaikan game walaupun belum semua unit terjual)
						- Tombol Menu (Pilihan Pop up Box) Berisi:
							- Resume Game (Melanjutkan Game yang sedang Berjalan)
							- Save (Pop up Box untuk Menamai Game yang Disimpan ini)
							- New Game
							- Option
								- Pengaturan Musik (Muncul Pop up Box untuk mengatur volume musik)
							- Quit Map
								-Kembai ke Main Menu
							- Exit
								- Kembali ke Login User
				- Lahan_2_Map_Singleplayer (11x11)
					- Board game design
					- Menu tersedia
						- Tombol Jual
							Selesai membuat desain, masuk ke mode jual. Disini ada fitur simulasi proses penjualan otomatis. Game akan selesai jika semua unit sudah terjual habis. Menampilkan summary rincian modal, jumlah unit terjual, total hasil penjualan, waktu penjualan (yang sangat dipengaruhi oleh efek kebahagiaan)
							Terdapat tombol Skip (untuk melewati proses langsung ke summary) dan Selesaikan (Berfungsi menyelesaikan game walaupun belum semua unit terjual)
						- Tombol Menu (Pilihan Pop up Box) Berisi:
							- Resume Game (Melanjutkan Game yang sedang Berjalan)
							- Save (Pop up Box untuk Menamai Game yang Disimpan ini)
							- New Game
							- Option
								- Pengaturan Musik (Muncul Pop up Box untuk mengatur volume musik)
							- Quit Map
								-Kembai ke Main Menu
							- Exit
								- Kembali ke Login User
				- Lahan_3_Map_Singleplayer (13x13)
					- Board game design
					- Menu tersedia
						- Tombol Jual
							Selesai membuat desain, masuk ke mode jual. Disini ada fitur simulasi proses penjualan otomatis. Game akan selesai jika semua unit sudah terjual habis. Menampilkan summary rincian modal, jumlah unit terjual, total hasil penjualan, waktu penjualan (yang sangat dipengaruhi oleh efek kebahagiaan)
							Terdapat tombol Skip (untuk melewati proses langsung ke summary) dan Selesaikan (Berfungsi menyelesaikan game walaupun belum semua unit terjual)
						- Tombol Menu (Pilihan Pop up Box) Berisi:
							- Resume Game (Melanjutkan Game yang sedang Berjalan)
							- Save (Pop up Box untuk Menamai Game yang Disimpan ini)
							- New Game
							- Option
								- Pengaturan Musik (Muncul Pop up Box untuk mengatur volume musik)
							- Quit Map
								-Kembai ke Main Menu
							- Exit
								- Kembali ke Login User
		- Multiplayer
			- Pilih Pemain (Check Box. Hanya memunculkan User yang sedang login diwaktu yang sama)
				- User_1
				- User_2
				- User_3
			- Map_Multiplayer
				- Lahan_1_Map_Multiplayer (9x9)
					- Board game design
					- Menu tersedia
						- Tombol Jual
							Selesai membuat desain, masuk ke mode jual. Disini ada fitur simulasi proses penjualan otomatis. Game akan selesai jika semua unit sudah terjual habis. Menampilkan summary rincian modal, jumlah unit terjual, total hasil penjualan, waktu penjualan (yang sangat dipengaruhi oleh efek kebahagiaan)
							Terdapat tombol Skip (untuk melewati proses langsung ke summary) dan Selesaikan (Berfungsi menyelesaikan game walaupun belum semua unit terjual)
						- Tombol Menu (Pilihan Pop up Box) Berisi:
							- Resume Game (Melanjutkan Game yang sedang Berjalan)
							- Save (Pop up Box untuk Menamai Game yang Disimpan ini)
							- New Game
							- Option
								- Pengaturan Musik (Muncul Pop up Box untuk mengatur volume musik)
							- Quit Map
								-Kembai ke Main Menu
							- Exit
								- Kembali ke Login User
				- Lahan_2_Map_Multiplayer (11x11)
					- Board game design
					- Menu tersedia
						- Tombol Jual
							Selesai membuat desain, masuk ke mode jual. Disini ada fitur simulasi proses penjualan otomatis. Game akan selesai jika semua unit sudah terjual habis. Menampilkan summary rincian modal, jumlah unit terjual, total hasil penjualan, waktu penjualan (yang sangat dipengaruhi oleh efek kebahagiaan)
							Terdapat tombol Skip (untuk melewati proses langsung ke summary) dan Selesaikan (Berfungsi menyelesaikan game walaupun belum semua unit terjual)
						- Tombol Menu (Pilihan Pop up Box) Berisi:
							- Resume Game (Melanjutkan Game yang sedang Berjalan)
							- Save (Pop up Box untuk Menamai Game yang Disimpan ini)
							- New Game
							- Option
								- Pengaturan Musik (Muncul Pop up Box untuk mengatur volume musik)
							- Quit Map
								-Kembai ke Main Menu
							- Exit
								- Kembali ke Login User
				- Lahan_3_Map_Multiplayer (13x13)
					- Board game design
					- Menu tersedia
						- Tombol Jual
							Selesai membuat desain, masuk ke mode jual. Disini ada fitur simulasi proses penjualan otomatis. Game akan selesai jika semua unit sudah terjual habis. Menampilkan summary rincian modal, jumlah unit terjual, total hasil penjualan, waktu penjualan (yang sangat dipengaruhi oleh efek kebahagiaan)
							Terdapat tombol Skip (untuk melewati proses langsung ke summary) dan Selesaikan (Berfungsi menyelesaikan game walaupun belum semua unit terjual)
						- Tombol Menu (Pilihan Pop up Box) Berisi:
							- Resume Game (Melanjutkan Game yang sedang Berjalan)
							- Save (Pop up Box untuk Menamai Game yang Disimpan ini)
							- New Game
							- Option
								- Pengaturan Musik (Muncul Pop up Box untuk mengatur volume musik)
							- Quit Map
								-Kembai ke Main Menu
							- Exit
								- Kembali ke Login User
	- Load Game
		- Pilihan Game yang Di "Save" Sebelumnya (Muncul Pop up menunjukkan list game yang disimpan sebelumnya)
	- Option
		- Pengaturan Musik (Muncul Pop up Box untuk mengatur volume musik)
	- Exit
		- Kembali ke Login User
		
