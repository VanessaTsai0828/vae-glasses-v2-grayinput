# vae-remove-glasses
Remove eyeglasses from face images using a simple Variational Autoencoder (VAE).

> 📚 系列作品｜Project Series:
> - [Part 1: Basic VAE](https://github.com/VanessaTsai0828/vae-remove-glasses)
> - [Part 2: Grayscale VAE](https://github.com/VanessaTsai0828/vae-remove-glasses-gray)
> - [Part 3: VAE with VGG loss](https://github.com/VanessaTsai0828/vae-remove-glasses-vgg)
> - [Part 4: VAE-GAN](https://github.com/VanessaTsai0828/vae-remove-glasses-gan)

---

## 🧠 專案內容 | What’s Inside

- 使用 CNN 建立的 VAE 模型，輸入為**灰階影像**
- 訓練資料為 160x160 的人臉（有/無眼鏡）
- 輸出為無眼鏡臉部影像
- 損失：重建誤差 + KL 散度
- 適合在 Colab 或低算力設備快速訓練
  
- A VAE model built with CNN, using grayscale images as input
- Trained on 160x160 facial images (with and without glasses)
- Outputs glasses-free facial images
- Loss function: reconstruction loss + KL divergence
- Suitable for fast training on Colab or low-compute environments



---

## 📸 範例結果 | Sample Result
![image](https://github.com/user-attachments/assets/624121ac-b68a-4f67-8778-f496f877fe05)


---

## 📌 備註 | Notes

- 使用灰階圖可加快訓練、減少過擬合
- 去眼鏡效果清楚、邊緣柔和
- 可作為低資源環境下的 baseline 模型
  
- Grayscale input accelerates training and reduces overfitting
- Clear glass removal with smoother facial contours
- Can serve as a baseline model for low-resource scenarios




