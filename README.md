# StyleGAN-NADA-reimplementation-for-DLS-School
В данном репозитории представлена кастомная реализация алгоритма StyleGAN-NADA (Non-Adversarial Domain Adaptation). Метод позволяет адаптировать предобученный генератор StyleGAN под новые стили без использования целевых изображений. Направление изменения стиля кодируется и контролируется с помощью модели CLIP

Для облегчения репозитория все обученные веса моделей вынесены на внешнюю платформу:
* **Базовая модель:** StyleGAN2-FFHQ (Config-F) от Rosinality.
* **Оптимизированные веса стилей:** Доступны в репозитории [Hugging Face Hub (F34723/stylegan2-nada-weights)]([https://huggingface.co](https://huggingface.co/F34723/stylegan2-nada-weights).

<img src="images/person_1_all_styles.png" width="100%">
<img src="images/person_2_all_styles.png" width="100%">
<img src="images/person_3_all_styles.png" width="100%">
<img src="images/person_4_all_styles.png" width="100%">
<img src="images/person_5_all_styles.png" width="100%">
<img src="images/person_6_all_styles.png" width="100%">
<img src="images/person_7_all_styles.png" width="100%">
<img src="images/person_9_all_styles.png" width="100%">
<img src="images/person_10_all_styles.png" width="100%">
