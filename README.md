# Анализ эффективности нового алгоритма рекомендаций в условиях асимметричного и зашумленного распределения

Этот проект анализирует результаты A/B-теста для оценки эффективности алгоритма рекомендаций с использованием статистических методов и визуализации данных. Он включает Jupyter-ноутбук с подробным анализом и CSV-датасет.

## Технический стек
<p align="left">
  <a href="https://www.python.org"><img src="https://img.shields.io/badge/Python-3.12-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python 3.12" /></a>
  <a href="https://pandas.pydata.org/"><img src="https://img.shields.io/badge/Pandas-2.3.3-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas 2.3.3" /></a>
  <a href="https://numpy.org"><img src="https://img.shields.io/badge/NumPy-2.4.0-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy 2.4.0" /></a>
  <a href="https://scipy.org"><img src="https://img.shields.io/badge/SciPy-1.16.3-0C55A5?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy 1.16.3" /></a>
  <a href="https://matplotlib.org"><img src="https://img.shields.io/badge/Matplotlib-3.10.8-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib 3.10.8" /></a>
  <a href="https://seaborn.pydata.org/"><img src="https://img.shields.io/badge/Seaborn-0.13.2-3776AB?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn 0.13.2" /></a>
</p>

## Структура проекта

```bash
tree ./ -I '3.12venv'
./
├── ab_test_results.csv
├── Homework_with_answers_modul_2.ipynb
├── LICENSE
├── README.md
├── requirements.txt

```


## Начало работы

### Предварительные требования
- Python 3.12
- Git

### Установка

1. Клонируйте репозиторий:
   ```
   git clone https://github.com/Liuboshenko/AB_test_HW_2_Analysis_effectiveness_recommendation_algorithm.git
   ```
   
2. Перейдите в директорию проекта:
   ```
   cd AB_test_HW_2_Analysis_effectiveness_recommendation_algorithm
   ```

3. Создайте и активируйте виртуальное окружение с Python 3.12:
   ```
   python3.12 -m venv 3.12venv
   source 3.12venv/bin/activate  # На Unix/macOS
   ```

4. Установите зависимости:
   ```
   pip install -r requirements.txt
   ```

### Использование
- Откройте Jupyter-ноутбук `Homework_with_answers_modul_2.ipynb` для запуска анализа.
- Датасет находится в `ab_test_results.csv`. 
- md5sum ./ab_test_results.csv af0595f5cea8abd9140c33bae48dee63
- Убедитесь, что виртуальное окружение активировано перед запуском ноутбука.