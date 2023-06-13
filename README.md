# ITI8565-2023-ML-FinalProject

## Downloading the Models
The following commands can be used to download the respective models:

Unconditional Music Transformer
```bash
gsutil cp "gs://magentadata/models/music_transformer/checkpoints/unconditional_model_16.ckpt.data-00000-of-00001" ./models/music_transformer/
gsutil cp "gs://magentadata/models/music_transformer/checkpoints/unconditional_model_16.ckpt.index" ./models/music_transformer/
gsutil cp "gs://magentadata/models/music_transformer/checkpoints/unconditional_model_16.ckpt.meta" ./models/music_transformer/
```

Score-Conditioned Music Transformer
```bash
gsutil cp "gs://magentadata/models/music_transformer/checkpoints/melody_conditioned_model_16.ckpt.data-00000-of-00001" ./models/music_transformer/
gsutil cp "gs://magentadata/models/music_transformer/checkpoints/melody_conditioned_model_16.ckpt.index" ./models/music_transformer/
gsutil cp "gs://magentadata/models/music_transformer/checkpoints/melody_conditioned_model_16.ckpt.meta" ./models/music_transformer/
```

## Downloading the SoundFont
To download the soundfont file, you can use the following command:

```bash
gsutil cp "gs://magentadata/soundfonts/Yamaha-C5-Salamander-JNv5.1.sf2" ./soundfonts/
```