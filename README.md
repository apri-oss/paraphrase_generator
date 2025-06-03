# Quora Paraphrasing Id

## Task Mini Transformer
**Deskripsi Task**  
Paraphrase Generator yang bertujuan untuk menghasilkan kalimat baru dengan makna yang sama atau mirip dari kalimat yang diberikan/input.


## Nama Dataset
**Quora Paraphrasing Id**  
Disediakan oleh: [Quora Paraphrasing Id](https://github.com/louisowen6/quora_paraphrasing_id)

## 🔗 Link Asli Dataset
[https://github.com/louisowen6/quora_paraphrasing_id](https://github.com/louisowen6/quora_paraphrasing_id)

## Informasi Statistik Dataset Asli

| Split       | Jumlah Baris | Fitur                          |
|-------------|--------------|--------------------------------|
| Train       | 134,084      | `question_1`, `question_2`     |
| Validation  | 14,927       | `question_1`, `question_2`     |

- **`question_1`**: Kalimat pertama
- **`question_2`**: Kalimat kedua

## 🔍 Contoh Isi Dataset (Format JSON)
Note : Dataset yang diupload di github ini merupakan dataset yang sudah dilakukan preprocessing untuk keperluan tugas ini

```json
[
  {
    "question_1": "Apa beberapa teknik yoga yang baik untuk menurunkan berat badan?",
    "question_2": "Apa asana yoga untuk menurunkan berat badan?"
  },
  {
    "question_1": "Bagaimana musik memicu emosi?",
    "question_2": "Mengapa musik bertanggung jawab untuk memicu emosi?"
  }
]
