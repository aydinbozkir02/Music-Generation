# Müzik Üretimi ve Tahmini

Bu proje, derin öğrenme kullanarak müzik üretimi ve tahmini yapan bir yapay zeka modelini içerir. Model, MIDI formatındaki müzik verilerini kullanarak eğitilir ve yeni melodiler üretebilir.

## İçerik

- `music_prediction.py`: Müzik verilerini işleyerek modeli eğitir.
- `make_music.py`: Eğitilmiş model kullanılarak yeni müzik üretir.
- `weights-improvement-196-0.2000-bigger.keras`: Eğitilmiş model ağırlıkları.
- `test_output1.wav`, `test_output (1).wav`: Model tarafından üretilen örnek ses dosyaları.

## Kurulum ve Kullanım

1. Gerekli kütüphaneleri yükleyin:
   ```bash
   pip install numpy keras tensorflow music21
