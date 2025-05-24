# ID Paraphrase Detection Dataset

## 📂 Nama Dataset
**Indonesian Paraphrase Detection Dataset**  
Disediakan oleh: [Jakarta Research](https://huggingface.co/jakartaresearch)

## 🔗 Link Asli Dataset
[https://huggingface.co/datasets/jakartaresearch/id-paraphrase-detection](https://huggingface.co/datasets/jakartaresearch/id-paraphrase-detection)

## 📊 Informasi Statistik Dataset Asli

| Split       | Jumlah Baris | Fitur                          |
|-------------|--------------|--------------------------------|
| Train       | 4,076        | `sentence1`, `sentence2`, `label` |
| Validation  | 1,725        | `sentence1`, `sentence2`, `label` |

- **`sentence1`**: Kalimat pertama
- **`sentence2`**: Kalimat kedua
- **`label`**: 1 jika kalimat merupakan parafrase, 0 jika bukan

## 🔍 Contoh Isi Dataset (Format JSON)

```json
[
  {
    "sentence1": "Amrozi menuduh saudaranya, yang dia sebut \"saksi\", dengan sengaja mendistorsi buktinya.",
    "sentence2": "Mengacu padanya hanya sebagai \"saksi\", Amrozi menuduh saudaranya dengan sengaja mendistorsi buktinya.",
    "label": 1
  },
  {
    "sentence1": "Mereka telah menerbitkan iklan di internet pada 10 Juni, menawarkan kargo untuk dijual, tambahnya.",
    "sentence2": "Pada 10 Juni, pemilik kapal telah menerbitkan iklan di internet, menawarkan bahan peledak untuk dijual.",
    "label": 1
  },
  {
    "sentence1": "Saham naik $ 2,11, atau sekitar 11 persen, ditutup Jumat dengan $ 21,51 di New York Stock Exchange.",
    "sentence2": "Saham PG&E Corp. melonjak $ 1,63 atau 8 persen menjadi $ 21,03 di New York Stock Exchange pada hari Jumat.",
    "label": 1
  }
]
