# MAI-MULTIMEDIA-2-SEM

Раюоту выполнил студент группы М8О-406Б-21 Чистяков Константин Сергеевич

## Выбор датасета
Датасет для ЛР №6: [Fruits Dataset](https://www.kaggle.com/datasets/shreyapmaher/fruits-dataset-images)

Датасет для ЛР №7: [Leaf disease segmentation dataset](https://www.kaggle.com/datasets/fakhrealam9537/leaf-disease-segmentation-dataset?resource=download)

Датасет для ЛР №8: [crop and weed detection data with bounding boxes](https://www.kaggle.com/datasets/ravirajsinh45/crop-and-weed-detection-data-with-bounding-boxes)

## Лабораторная работа №6
| Модель | Test Accuracy | macro‑F1 |
|--------|---------------|----------|
| ResNet‑18 (baseline) | 0.800 | 0.762 |
| ViT‑B/16 (baseline)  | 0.786 | 0.773 |
| ResNet‑18 (tuned) | 0.766 | 0.736 |
| ViT‑B/16 (tuned)  | 0.600 | 0.578 |
| Собственная реализация SimpleCNN (baseline) | 0.343 | 0.298 |
| Собственная реализация SimpleCNN (tuned)  | 0.382 | 0.356 |

## Лабораторная работа №7
| Модель | Test mIoU | Dice |
|--------|-----------|------|
| U‑Net (baseline) | 0.534 | 0.696 |
| FPN  (baseline)  | 0.552 | 0.711 |
| U‑Net (tuned)    | 0.663 | 0.797 |
| FPN  (tuned)     | 0.596 | 0.747 |
| Собственная реализация UNet‑Light (baseline) | 0.428 | 0.600 |
| Собственная реализация UNet‑Light (tuned)    | 0.441 | 0.612 |

## Лабораторная работа №8
| Модель | mAP@0.5 | mAP@0.5:0.95 | Precision | Recall |
|--------|---------|--------------|-----------|--------|
| YOLOv8‑n baseline | 0.905 | 0.646 | 0.874 | 0.834 |
| YOLOv8‑s tuned    | 0.906 | 0.613 | 0.854 | 0.842 |
| Собственная реализация RetinaNet‑R50     | 0.862 | 0.753 | 0.901 | 0.846 |

## Вывод
По данным, представленным в таблицах, можно заключить, что модели, реализованные с использованием встроенных библиотек, демонстрируют более высокую эффективность по сравнению с моделями, написанными самостоятельно. Улучшенные базовые показатели часто демонстрируют более высокие результаты. В некоторых случаях показатели могут быть хуже, что может быть связано с неправильным выбором параметров.
