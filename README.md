# Akıllı Metin Özetleyici (Gradio & Hugging Face)

Bu proje, Hugging Face `transformers` kütüphanesi ve `t5-small` modeli kullanılarak oluşturulmuş, uzun metinleri özetleyen basit bir web uygulamasıdır. Kullanıcı arayüzü Gradio ile geliştirilmiştir.

![Uygulamanın ekran görüntüsünü buraya ekleyebilirsiniz.]

## 🚀 Kullanılan Teknolojiler

- **Python 3.8+**
- **Gradio:** Web arayüzü için.
- **Hugging Face Transformers:** NLP pipeline ve önceden eğitilmiş T5 modeli için.
- **PyTorch:** Transformers kütüphanesinin altyapısı için.

## 🛠️ Kurulum ve Çalıştırma

Projeyi yerel makinenizde çalıştırmak için aşağıdaki adımları izleyin:

1.  **Depoyu klonlayın (Eğer GitHub'a yüklediyseniz):**
    ```bash
    git clone [DEPO_URL'Sİ]
    cd day-21-summarizer-gradio
    ```

2.  **Gerekli kütüphaneleri yükleyin:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Uygulamayı çalıştırın:**
    ```bash
    python app.py
    ```

4.  Tarayıcınızda `http://127.0.0.1:7860` adresini açarak uygulamayı kullanmaya başlayın.