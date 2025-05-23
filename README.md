## Катаев Юрий Игоревич группа М8О-410Б-21

Результаты по всем лабораторным:

Лабораторная 7:
| Модель                    | IoU    |
|---------------------------|--------|
| UNet                      | 0.4588 |
| UNet improved             | 0.4814 |
| Custom UNet               | 0.3234 |
| Custom UNet improved      | 0.4531 |
| Segformer                 | 0.5667 |
| Segformer improved        | 0.5924 |
| Custom Segformer          | 0.1608 |
| Custom Segformer improved | 0.3166 |

Лабораторная 8:
| Модель               | mAP50  | mAP50-95 |
|----------------------|--------|----------|
| Yolo                 | 0.806  |    0.631 |
| Yolo improved        | 0.923  |    0.751 |
| Custom               | 0.453  |    0.440 |
| Custom improved      | 0.635  |    0.534 |


В ходе исследований были рассмотрены различные модели семантической сегментации и обнаружения и распознавания объектов. В своих задачах были использованы различные модели, которые показали свои преимущества и недостатки. Лучшие результаты были получены с помощью таких моделей, как Segformer и Yolo. Свои реализации не смогли достичь таких же результатов, как у предобученных моделей. Предобучение делает их более эффективными и точными в специализированных задачах классификации, сегментации и детекции объектов. Тем не менее, разработка и адаптация моделей под специфические условия могут привести к улучшению результатов при точной настройке гиперпараметров и увеличении качества и объема данных для обучения.
