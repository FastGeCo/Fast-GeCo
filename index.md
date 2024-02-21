# <center> A Generative Correction Method for Noise-robust Speech Separation </center>

<center> Anonymous submission to Interspeech 2024 </center> 

<!-- ## Abstract

Speech separation, the process of isolating multiple speech sources from a mixed audio signal, remains a challenging task in noisy environments. 
In this paper, we introduce a generative correction method that refines the output of a discriminative model using a generative model for single-channel speech
separation. Furthermore, we fine-tune the generative model by optimizing a predictive loss to streamline the reverse process into a single step and correct errors resulting from solving the reverse process. Our method achieves state-of-the-art results on the LibriMix noisy dataset and demonstrates strong generalization to out-of-domain data.

## Model Overview
<img src="imgs/model.png" alt="Overall Architecture" /> -->


## Demo
### Samples 1 from LibriMix noisy test set.

| Mixture | Reference (speaker 1) | Estimated (SepFormer) | Estimated (GeCo) | Estimated (Fast-GeCo) |
| :--- | :--- | :--- | :--- | :--- |
| <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> |
| <audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |
| | <strong>Reference (speaker 2)</strong> | <strong>Estimated (SepFormer)</strong> | <strong>Estimated (GeCo)</strong> | <strong>Estimated (Fast-GeCo)</strong> |
| | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> |
| |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |

### Samples 2 from LibriMix noisy test set.
| Mixture | Reference (speaker 1) | Estimated (SepFormer) | Estimated (GeCo) | Estimated (Fast-GeCo) |
| :--- | :--- | :--- | :--- | :--- |
| <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> |
| <audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |
| | <strong>Reference (speaker 2)</strong> | <strong>Estimated (SepFormer)</strong> | <strong>Estimated (GeCo)</strong> | <strong>Estimated (Fast-GeCo)</strong> |
| | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> | <img src="demo_img/sepformer/item0_mix.png" alt="Image"> |
| |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |<audio src="demo/sepformer/item0_mix.wav" controls preload></audio> |