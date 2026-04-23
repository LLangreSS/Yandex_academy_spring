# Machine Learning & Deep Learning: Yandex Academy 

Репозиторий с практическими работами по курсу машинного обучения. Здесь собраны реализации классических алгоритмов, задачи компьютерного зрения и генеративные модели.

##  Структура репозитория

* **`hw1/`** — Основы машинного обучения: реализация линейной регрессии на датасете Travel Insurance.
* **`hw2/`** — Введение в компьютерное зрение: разработка сверточных нейронных сетей (CNN) на датасете MNIST.
* **`hw3/`** — Продвинутые методы в CV:
    * Оптимизация архитектур CNN.
    * Применение аугментации данных.
    * Использование Skip-connections для обучения глубоких сетей.
* **`hw4/`** — Генеративные модели: реализация вариационного автоэнкодера (VAE) с использованием ResNet-блоков.
* **`final_project/`** — Итоговый проект: разработка нейросетевой архитектуры `StyleGanTitanNet` для детектирования сгенерированных изображений (используются BayarConv2d, частотный анализ через FFT и механизмы внимания SE-blocks).

## 🛠 Технологии

- **Frameworks:** `PyTorch`, `scikit-learn`
- **Techniques:**
    - Linear Regression (analytical/sklearn)
    - CNN Architectures (ResNet-like blocks)
    - VAE (Variational Autoencoders)
    - Frequency Analysis (FFT)
    - SRM/Bayar layers for steganalysis
