# PowerPoint and Excel data extraction prototype

Python scripts for exploring a sample brand performance exercise stored in Excel and PowerPoint files. The scripts print worksheet previews and slide text, then write a short text report from the supplied workbooks.

## What is in this repository

The sample files and scripts are in [Automated Data Extraction & Analytics Engine](Automated%20Data%20Extraction%20%26%20Analytics%20Engine/):

- `read_data.py` previews every sheet in `Exercise 2.2 (1).xlsx` and prints PowerPoint slide text matching the exercise.
- `read_details.py` previews the exercise and solution workbooks and prints text from each slide in `Brand Performance Measures (1).pptx`.
- `analyze_exercise.py` writes `output8.txt` with a preview of the `Data` sheet and the first sheet of the solution workbook.

These are exploratory scripts for the included exercise files. They do not calculate the market-share table previously shown in this README or provide a production ETL pipeline. PowerPoint text extraction uses a simple XML pattern and may miss some slide content.

## Run locally

Python 3 and the supplied sample files are required. From a terminal:

```bash
git clone https://github.com/Bonifacethuo/Automated-Data-Extraction-Analytics-Engine.git
cd Automated-Data-Extraction-Analytics-Engine/'Automated Data Extraction & Analytics Engine'
python -m pip install pandas openpyxl
python read_data.py
python read_details.py
python analyze_exercise.py
```

The scripts read files from their own directory. `analyze_exercise.py` creates `output8.txt` there. Run them one at a time; they are separate explorations rather than stages of one pipeline.

## Skills demonstrated

Python file handling, Excel inspection with pandas and openpyxl, and extraction of slide text from PPTX archives. The next improvement would be to turn these scripts into functions with command-line file arguments, structured outputs, and validation against known expected values.

[Portfolio](https://boniface-thuo-m-portifolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/boniface-thuo-52ab3816a/) · [GitHub profile](https://github.com/Bonifacethuo)
