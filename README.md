# PDF Information Extractor

استخراج خودکار اطلاعات از فایل‌های PDF با رابط کاربری گرافیکی

## ویژگی‌ها
- رابط کاربری گرافیکی ساده و کاربرپسند
- امکان پردازش چندین PDF به صورت همزمان
- استخراج خودکار اطلاعات با استفاده از OCR و LayoutLMv3
- خروجی در قالب فایل Excel

## نیازمندی‌ها
- Python 3.8 یا بالاتر
- حداقل 8GB RAM
- سیستم‌عامل: Windows/Linux/MacOS

## نصب و راه‌اندازی

```bash
# کلون کردن مخزن
git clone https://github.com/YourUsername/pdf-extractor.git
cd pdf-extractor

# ایجاد محیط مجازی
python -m venv venv

# فعال‌سازی محیط مجازی
# در Windows:
venv\Scripts\activate
# در Linux/MacOS:
source venv/bin/activate

# نصب وابستگی‌ها
pip install -r requirements.txt

# اجرای برنامه
python main.py
