# GloVe Word Embedding Analizi

Bu proje, Stanford tarafından geliştirilen GloVe (Global Vectors for Word Representation) kelime gömme modeli kullanılarak, `teacher`, `doctor` ve `artist` kavramları üzerinde semantik analizler yapılmasını amaçlamaktadır.

## İçerik

Notebook dosyasında aşağıdaki adımlar gerçekleştirilmiştir:

1. 📦 Gerekli Python kütüphanelerinin kurulumu (gensim, sklearn, matplotlib)
2. 📂 GloVe vektörlerinin Word2Vec formatına dönüştürülmesi (`glove2word2vec`)
3. 📥 Modelin yüklenmesi (`KeyedVectors`)
4. 🔍 `teacher`, `doctor`, `artist` kelimeleri için benzerlik analizi
5. ➕ Vektör aritmetiği (`teacher - doctor + artist`)
6. 📊 TSNE algoritması ile görselleştirme

## Nasıl Kullanılır?

1. `glove.6B.50d.txt` dosyasını Colab veya Jupyter ortamına yükleyin.
2. Notebook dosyasını adım adım çalıştırın.
3. GloVe dosyası otomatik olarak dönüştürülüp yüklenecektir.
4. Sonuçları görsel olarak inceleyebilirsiniz.

## Kaynaklar

- [GloVe: Global Vectors for Word Representation](https://nlp.stanford.edu/projects/glove/)
- [Gensim Documentation](https://radimrehurek.com/gensim/)
- [scikit-learn TSNE](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html)

---


