# Лабораторная работа 1 — CV (оценка 3)

Обнаружение нефтяных пятен (oil spill detection) в море/океане на SAR-снимках с помощью
`ultralytics` (семейство моделей **YOLOv11**).

## Датасет

[Oil Spill YOLOv8 Complete Dataset (LSGI)](https://universe.roboflow.com/lsgi/oil-spill-yolov8-complete-dataset)
— ~1000 SAR-изображений, разметка в YOLO-формате, 4 класса: `oil spill`, `look-alike`, `ship`, `land`.
Скачивается прямо из ноутбука через Roboflow API.
---

## Запуска в Google Colab

1. Загрузите `Lab1_OilSpill_YOLOv11.ipynb` в <https://colab.research.google.com/> (`File → Upload notebook`).
2. `Runtime → Change runtime type → GPU`
3. `Runtime → Run all`. Полный прогон ~45–60 минут.