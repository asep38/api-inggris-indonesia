### link
```
live API : [https://asep38.github.io/api-inggris-indonesia/data/vocab/animals.json]
```

### JavaScript (fetch API)
```markdown
```js
fetch("https://asep38.github.io/api-inggris-indonesia/data/vocab/animals.json")
  .then(res => res.json())
  .then(data => {
    data.forEach(item => {
      console.log(`${item.word} = ${item.translation}`);
    });
  });
```

- `id`: Nomor urut unik
- `word`: Kosakata Bahasa Inggris
- `translation`: Terjemahan Bahasa Indonesia
- `audio`: *(opsional)* nama file audio pengucapan
- `example`: *(opsional)* contoh penggunaan dalam kalimat

## 📚 Kategori Vocabulary

Berikut adalah daftar kategori kosakata yang tersedia:

| No. | Kategori     | File JSON       | Link API                                                                 |
|-----|--------------|-----------------|--------------------------------------------------------------------------|
| 1   | 🐾 Animals    | `animals.json`  | [Lihat](https://asep38.github.io/api-inggris-indonesia/data/vocab/animals.json) |
| 2   | 🍔 Food       | `food.json`     | *(coming soon)*                                                          |
| 3   | 👕 Clothes    | `clothes.json`  | *(coming soon)*                                                          |
| 4   | 👨‍🏫 Jobs      | `jobs.json`     | *(coming soon)*                                                          |

## 🧑‍💻 Kontribusi
Pull Request sangat diterima! Kamu bisa:

- Menambahkan kategori baru (file baru)
- Menambahkan suara/audio
- Menambahkan contoh kalimat

## 📌 Langkah kontribusi:
- Fork repo ini
- Tambahkan file JSON baru di folder /data/vocab/
- Buat Pull Request

## 📄 License
MIT © asepzarkasihnoor


