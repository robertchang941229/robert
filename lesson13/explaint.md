# lesson13_1.py 說明

## 功能簡介
本程式為「學生成績管理系統」，主要功能如下：
1. 從 `names.txt` 檔案隨機取出 3 位學生姓名。
2. 為每位學生產生「國文」、「英文」、「數學」三科隨機分數（50~100）。
3. 列印每位學生的姓名、各科分數及平均分數。

## 主要函式說明

- `sample_names_from_file(file_name: str, nums: int = 1) -> list[str]`
    - 從指定檔案讀取所有姓名，並隨機取出指定數量的姓名。

- `generate_scores_for_names(names: list[str]) -> list[dict]`
    - 為每個姓名生成三科隨機分數，回傳包含姓名與分數的字典列表。

- `print_student_scores(students: list[dict])`
    - 列印所有學生的姓名、分數及平均分數。

- `main()`
    - 程式進入點，負責呼叫上述函式並執行主要流程。

## 執行方式
直接執行 `lesson13_1.py` 即可看到隨機三位學生的成績表。

## 檔案需求
- 需有一個 `names.txt` 檔案，內容為每行一個學生姓名