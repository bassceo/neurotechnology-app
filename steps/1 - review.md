# Анализ предметной области: Айтрекинг и визуализация данных

## Содержание
1. [Веб-дизайн и айтрекинг](#1-веб-дизайн-и-айтрекинг)
2. [Визуализация данных айтрекинга](#2-визуализация-данных-айтрекинга)
3. [Валидация WebGazer](#3-валидация-webgazer)
4. [WebGazeTrack](#4-webgazetrack)
5. [Электронное устройство определения морганий](#5-электронное-устройство-определения-морганий)
6. [Классификация визуальных объектов по ЭЭГ](#6-классификация-визуальных-объектов-по-ээг)

---

## 1. Веб-дизайн и айтрекинг

### Webcam Eye-Tracking Browser Extension for General Navigation [[1]](#ссылки-на-источники)

| Характеристика | Описание |
|----------------|----------|
| **Название статьи** | "Webcam Eye-Tracking Browser Extension for General Navigation" |
| **Публикация** | Procedia Computer Science |
| **Год** | 2025 (апрель) |

**Выжимка по теме:** Статья представляет JavaScript-расширение, которое превращает обычную веб-камеру в полноценный трекер взгляда. Решение рассчитано на массовое использование в браузере, что делает технологию айтрекинга более доступной для широкого круга пользователей.

---

## 2. Визуализация данных айтрекинга

### Automation of the Visualisation of Eye-Tracking Data [[5]](#ссылки-на-источники)

| Характеристика | Описание |
|----------------|----------|
| **Название статьи** | "Automation of the Visualisation of Eye-Tracking Data with Animated Heatmaps" |
| **Публикация** | Сборник HCI-конференции |
| **Год** | 2023 (август) |

**Выжимка по теме:** Работа представляет open-source фреймворк для генерации статических и анимированных карт внимания, специально разработанный для веб-экспериментов. Это решение значительно упрощает процесс визуализации данных айтрекинга и делает его более доступным для исследователей.

---

## 3. Валидация WebGazer

### Validation of an Open-Source, Remote Web-Based Eye-Tracking Platform [[2]](#ссылки-на-источники)

| Характеристика | Описание |
|----------------|----------|
| **Название статьи** | Validation of an open source, remote web-based eye-tracking method (WebGazer) |
| **Публикация** | Infancy |
| **Авторы** | Adrian Steffan, Lucie Zimmer и др. |
| **Год** | 2023 |

#### Ключевые findings:

##### Целевая группа
- Дети 18-27 месяцев

##### Преимущества
- ✅ Доступное решение
- ✅ Низкие затраты
- ✅ Возможность удаленных исследований

##### Ограничения
- ⚠️ Низкая доля пригодных данных
- ⚠️ Высокий процент отсева
- ⚠️ Необходимость больших AOIs

##### Технические особенности
- 🔧 Использование веб-камер
- 🔧 Регрессионная модель для определения взгляда

**Выжимка по теме:** В статье представлена валидация открытого веб-метода айтрекинга WebGazer для исследований с маленькими детьми в удаленном формате. WebGazer.js использовался для определения положения взгляда по видео с веб-камеры. Метод аппроксимирует положение взгляда с помощью регрессионной модели.

---

## 4. WebGazeTrack

### WebGazeTrack: A Web-based Eye Tracking Tool [[7]](#ссылки-на-источники)

| Характеристика | Описание |
|----------------|----------|
| **Название статьи** | WebGazeTrack: A Web-based Eye Tracking Tool |
| **Публикация** | 6-я Европейская конференция по образованию в области разработки ПО |
| **Авторы** | Simon Röhrl, Florian Hauser, Timur Ezer, Lisa Grabinger, Prof. Dr. Jürgen Mottok |
| **Год** | 2025 |

#### Ключевые особенности:
- 🔌 Реализация как расширение Chrome
- 🎯 CSS-селекторы для динамических AOIs
- 🔗 WebUSB интеграция
- 🎮 Поддержка Tobii Pro Fusion
- 🚀 Принцип "подключи и работай"

**Выжимка по теме:** В статье представлен WebGazeTrack - легкий веб-инструмент для айтрекинга, реализованный в виде расширения для Chrome. Инструмент разработан для упрощения исследований айтрекинга в веб-среде, преодолевая ограничения традиционного программного обеспечения.

---

## 5. Электронное устройство определения морганий

### Decoding Brain Signals from Rapid-Event EEG [[3]](#ссылки-на-источники)

| Характеристика | Описание |
|----------------|----------|
| **Название статьи** | "Decoding Brain Signals from Rapid-Event EEG for Visual Analysis of Attention" |
| **Публикация** | Frontiers in Neuroscience |
| **Год** | 2024 (ноябрь) |

#### Основные аспекты:
- 🎯 Фокус на доступном взаимодействии
- 📊 Калибровка: 9-точечная и 42-точечная шкалы
- 📝 Факторы точности:
  - Расстояние между точками
  - Освещение
  - "Нейтральные граничные условия"

**Выжимка по теме:** Статья посвящена классификации визуальных объектов с использованием ЭЭГ-сигналов. Предлагается методология обработки ЭЭГ-сигналов и обучение классификаторов.

---

## 6. Классификация визуальных объектов по ЭЭГ

### Measuring Student Attention Based on EEG Brain Signals [[4]](#ссылки-на-источники)

| Характеристика | Описание |
|----------------|----------|
| **Название статьи** | "Measuring Student Attention Based on EEG Brain Signals Using a Double Deep Q-Network" |
| **Публикация** | Expert Systems with Applications |
| **Год** | 2025 (апрель) |

#### Методология:
- 🧠 Обработка ЭЭГ-сигналов
- 🤖 Сравнение моделей машинного обучения

#### Результаты:
- 📈 Модели MCCFF показывают улучшение до 33.17%
- 📊 Необработанные данные часто эффективнее фильтрованных
- ⚠️ Сложности достижения высокой точности

---

## Ссылки на источники

1. [Webcam Eye-Tracking Browser Extension For General Navigation][1]
2. [Validation of an open source, remote web‐based eye‐tracking][2]
3. [Decoding Brain Signals from Rapid-Event EEG for Visual Analysis][3]
4. [Measuring student attention based on EEG brain signals using deep][4]
5. [Automation of the visualisation of eye-tracking data with animated heatmaps][5]
6. [(PDF) REAL-TIME EYE TRACKING USING HEAT MAPS][6]
7. [WebGazeTrack: A Web-based Eye Tracking Tool - ACM Digital Library][7]

[1]: https://www.sciencedirect.com/science/article/pii/S1877050925008087/pdf?md5=f25b1f85e90430bd59ced42833bfee28&pid=1-s2.0-S1877050925008087-main.pdf
[2]: https://onlinelibrary.wiley.com/doi/10.1111/infa.12564
[3]: https://pmc.ncbi.nlm.nih.gov/articles/PMC11548637
[4]: https://www.sciencedirect.com/science/article/abs/pii/S095741742500048X
[5]: https://www.researchgate.net/publication/373088209_Automation_of_the_visualisation_of_eye-tracking_data_with_animated_heatmaps
[6]: https://www.researchgate.net/publication/364976077_REAL-TIME_EYE_TRACKING_USING_HEAT_MAPS
[7]: https://dl.acm.org/doi/10.1145/3723010.3723024
