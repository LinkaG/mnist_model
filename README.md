# mnist_model

Модель распознавания рукописных цифр, обученная на наборе данных MNIST с использованием среды разработки Keras.

## Setting up the environment 

Запустить `bash setup_env.sh`. Загрузится и установится Miniconda с Python 3.9 и все зависимости из `gpu_environment.yml`.

## Experiments

1\. Ноутбук с моделью: [notebook](notebooks/cnn_model.ipynb). Для подбора гиперпараметров был использован keras_tuner. Модель показала 99,23% (accuracy) на тесте. 
