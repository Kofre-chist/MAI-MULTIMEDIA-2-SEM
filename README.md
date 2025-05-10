# MAI-MULTIMEDIA-2-SEM

Раюоту выполнил студент группы М8О-406Б-21 Чистяков Константин Сергеевич

## Выбор датасета
Датасет для ЛР №6: [Fruits Dataset](https://www.kaggle.com/datasets/shreyapmaher/fruits-dataset-images)

Датасет для ЛР №7: [Leaf disease segmentation dataset](https://www.kaggle.com/datasets/fakhrealam9537/leaf-disease-segmentation-dataset?resource=download)

## Лабораторная работа №6
| Модель | Test Accuracy | macro‑F1 |
|--------|---------------|----------|
| ResNet‑18 (baseline) | 0.800 | 0.762 |
| ViT‑B/16 (baseline)  | 0.786 | 0.773 |
| ResNet‑18 (tuned) | 0.766 | 0.736 |
| ViT‑B/16 (tuned)  | 0.600 | 0.578 |
| SimpleCNN (baseline) | 0.343 | 0.298 |
| SimpleCNN (tuned)  | 0.382 | 0.356 |

## Лабораторная работа №7
| Модель | Test mIoU | Dice |
|--------|-----------|------|
| U‑Net (baseline) | 0.534 | 0.696 |
| FPN  (baseline)  | 0.552 | 0.711 |
| U‑Net (tuned)    | 0.663 | 0.797 |
| FPN  (tuned)     | 0.596 | 0.747 |
| UNet‑Light (baseline) | 0.428 | 0.600 |
| UNet‑Light (tuned)    | 0.441 | 0.612 |


## Вывод
По данным, представленным в таблицах, можно заключить, что модели, реализованные с использованием встроенных библиотек, демонстрируют более высокую эффективность по сравнению с моделями, написанными самостоятельно. Улучшенные базовые показатели часто демонстрируют более высокие результаты. В некоторых случаях показатели могут быть хуже, что может быть связано с неправильным выбором параметров.
