# ErythrocytesRheologyAI

## Описание

**ErythrocytesRheologyAI** — открытый репозиторий на платформе GitHub, содержащий коллекцию Jupyter-блокнотов для анализа реологических свойств эритроцитов с использованием методов машинного обучения. Репозиторий разработан в рамках магистерского исследования по изучению кинетики агрегации и деформируемости эритроцитов человека в потоке.

## Основные возможности

- **Автоматизированная сегментация эритроцитов** с использованием Cellpose
- **Сегментация агрегатов эритроцитов** на основе Omnipose
- **Классификация морфологических состояний** с помощью EfficientNet
- **Количественный анализ деформируемости** и параметров агрегации
- **Статистический анализ** распределений

## Структура репозитория

```
ErythrocytesRheologyAI/
├── Cellpose/                  # Сегментация отдельных эритроцитов
│   ├── deformability_analysis.ipynb
│   ├── cellpose_segmentation.ipynb
│   └── distribution_analysis.ipynb
├── Omnipose/                  # Анализ агрегации эритроцитов
│   ├── aggregation_kinetics.ipynb
│   ├── omnipose_segmentation.ipynb
│   └── aggregate_parameters.ipynb
├── Efficient net/             # Классификация с глубоким обучением
│   ├── efficientnet_training.ipynb
│   ├── classification_analysis.ipynb
│   └── explainability_analysis.ipynb
├── Additional notebooks/      # Дополнительные блокноты
│   ├── data_preprocessing.ipynb
│   ├── statistical_analysis.ipynb
│   └── correlation_analysis.ipynb
├── README.md
└── LICENSE
```

## Научные результаты

Разработанные методы позволяют:

- **Выявлять клеточную гетерогенность** в образцах крови
- **Обнаруживать малые фракции** эритроцитов с измененной деформируемостью  
- **Классифицировать агрегаты** с точностью >80%

## Цитирование работы

Если вы используете код или методы из этого репозитория в своих исследованиях, пожалуйста, процитируйте нашу работу:

### Формат BibTeX:

```bibtex
@mastersthesis{ladynin2025erythrocytes,
  title={Кинетика агрегации и деформируемости эритроцитов человека в потоке: исследование с применением методов машинного обучения in vitro},
  author={Ладынин, Александр Иванович},
  year={2025},
  school={Московский государственный университет имени М.В. Ломоносова, Физический факультет},
  address={Москва, Россия},
  type={Магистерская диссертация},
  supervisor={Сергеева, И.А. and Луговцов, А.Е.},
  url={https://github.com/Lannix/ErythrocytesRheologyAI}
}
```

### Формат текстового цитирования:

**Русский язык:**
```
Ладынин А.И. Кинетика агрегации и деформируемости эритроцитов человека в потоке: исследование с применением методов машинного обучения in vitro. Магистерская диссертация. М.: МГУ имени М.В. Ломоносова, Физический факультет, 2025. URL: https://github.com/Lannix/ErythrocytesRheologyAI
```

**English:**
```
Kinetics of human red blood cell aggregation and deformability in flow conditions: a machine learning in vitro study. Master's thesis. Moscow: Lomonosov Moscow State University, Faculty of Physics, 2025. Available at: https://github.com/Lannix/ErythrocytesRheologyAI
```

### Дополнительные ссылки:

При использовании конкретных методов также рекомендуется цитировать:

- **Cellpose:** Stringer, C., Wang, T., Michaelos, M., & Pachitariu, M. (2021). Cellpose: a generalist algorithm for cellular segmentation. *Nature methods*, 18(1), 100-106.
- **Omnipose:** Cutler, K. J., et al. (2022). Omnipose: a high-precision morphology-independent solution for bacterial cell segmentation. *Nature methods*, 19(11), 1438-1448.
- **EfficientNet:** Tan, M., & Le, Q. (2019). Efficientnet: Rethinking model scaling for convolutional neural networks. *International conference on machine learning*.

## Лицензия

Данный проект распространяется под лицензией Apache-2.0. См. файл [LICENSE](LICENSE) для подробностей.
