# MyBigNumber Project

## Mô tả
Dự án cài đặt thuật toán cộng 2 số lớn bằng Python theo cách học sinh Tiểu học. Hàm `sum` nằm trong lớp `MyBigNumber`.

## Cách chạy chương trình

### 1. Cài đặt môi trường
bash
python -m venv venv
source venv/bin/activate  # Windows dùng venv\Scripts\activate
pip install -r requirements.txt

### 2. Chạy chương trình
from src.mybignumber import MyBigNumber

calc = MyBigNumber()
print(calc.sum("1234", "897"))  # Kết quả: 2131

### 3. Chạy Unit Test
python -m unittest discover tests
