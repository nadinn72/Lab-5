# Lab-5
**Pertemuan10-Dictionary**

1. **delete-Dicti.py**

File ini menunjukkan cara menghapus elemen dan seluruh dictionary di Python:
- `del dict['Name']`: Menghapus item dalam dictionary yang memiliki kunci `'Name'`.
- `dict.clear()`: Menghapus semua item dalam dictionary, tetapi dictionary itu sendiri tetap ada.
- `del dict`: Menghapus seluruh dictionary dari memori.
- Setelah `del dict`, script mencoba mencetak nilai dari kunci `'Age'` dan `'School'`, tetapi akan menyebabkan **error** karena dictionary telah dihapus sepenuhnya.

2. **Updating-Dicti.py**

File ini menggambarkan cara memperbarui dan menambahkan item ke dalam dictionary:
- `dict['Age'] = 8`: Memperbarui nilai kunci `'Age'` menjadi `8`.
- `dict['School'] = "DPS School"`: Menambahkan item baru dengan kunci `'School'` dan nilai `"DPS School"`.
- Script ini mencetak nilai dari kunci `'Age'` yang diperbarui dan `'School'` yang baru ditambahkan.

3. **access-Dicti.py**

File ini berfokus pada akses data dalam dictionary:
- `name = dict["Name"]`: Mengakses nilai dari kunci `'Name'`.
- `age = dict["Age"]`: Mengakses nilai dari kunci `'Age'`.
- `class= dict.get("Class")`: Mengambil nilai dari kunci `'Class'` menggunakan metode `.get()`; lebih aman jika kunci mungkin tidak ada.
- `class= dict.get("Class", "Alternate value")`: Menggunakan nilai default `"Alternate value"` jika kunci `'Class'` tidak ditemukan.
**Catatan:** Penamaan variabel `class` akan menyebabkan **error** karena `class` adalah kata kunci Python.

4. **dictionary.py**

File ini memperlihatkan cara mencetak nilai-nilai dalam dictionary:
- `print ("dict['Name']: ", dict['Name'])`: Mencetak nilai dari kunci `'Name'`.
- `print ("dict['Age']: ", dict['Age'])`: Mencetak nilai dari kunci `'Age'`.

Script ini sederhana, hanya menunjukkan bagaimana cara membaca nilai-nilai dari dictionary dan mencetaknya.
