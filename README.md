# lab3
# Лабораторна робота №3
## Нейронні мережі для класифікації

### Використані датасети

**1. Student Dropout and Academic Success (MLP)**

- Джерело: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success)
- Кількість записів: 4424
- Класи: Dropout, Enrolled, Graduate
- Файл: `data.csv` (роздільник `;`)

**2. Oxford-IIIT Pet (CNN)**

- Джерело: [Oxford-IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/)
- Класи: Cat, Dog
- Для експерименту використано 2881 локально доступне зображення.
- Потрібні папки `images/` та `annotations/`, що містить `trainval.txt` і `test.txt`.

**3. 20 Newsgroups (BiLSTM)**

- Джерело: [Scikit-learn — 20 Newsgroups](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_20newsgroups.html)
- Категорії: comp.graphics, rec.sport.hockey, sci.space
- Датасет автоматично завантажується через `fetch_20newsgroups()`.

**4. GloVe Pretrained Embeddings**

- Джерело: [Stanford GloVe](https://nlp.stanford.edu/projects/glove/)
- Модель: GloVe 6B, 50 dimensions
- Файл: `glove.6B.50d.txt`
- Якщо файл відсутній, модель автоматично завантажується через `gensim.downloader`.
