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

- `id`: Nomor urut unik
- `word`: Kosakata Bahasa Inggris
- `translation`: Terjemahan Bahasa Indonesia
- `audio`: *(opsional)* nama file audio pengucapan
- `example`: *(opsional)* contoh penggunaan dalam kalimat
