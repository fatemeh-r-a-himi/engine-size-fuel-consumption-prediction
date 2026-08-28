# 🚗 Engine Size & Fuel Consumption Prediction

یک پروژه‌ی ساده و آموزشی در زمینه‌ی **Machine Learning** با استفاده از Python و الگوریتم **Linear Regression**.

در این پروژه، رابطه‌ی بین **حجم موتور خودرو** و **مصرف سوخت** بررسی می‌شود و تلاش می‌شود مصرف سوخت بر اساس حجم موتور پیش‌بینی شود.

> 🌱 این پروژه یکی از پروژه‌های آموزشی من در مسیر یادگیری Machine Learning است.

---

## 🎯 هدف پروژه

هدف این پروژه بررسی این سؤال است:

**آیا می‌توان میزان مصرف سوخت خودرو را بر اساس حجم موتور آن پیش‌بینی کرد؟**

برای این کار از مدل **Linear Regression** استفاده شده است.

---

## 📊 Dataset

دیتاست این پروژه شامل دو ستون اصلی است:

| ستون | توضیح |
|---|---|
| `Engine_Size_L` | حجم موتور بر حسب لیتر |
| `Fuel_Consumption_L_per_100km` | مصرف سوخت بر حسب لیتر در ۱۰۰ کیلومتر |

این دیتاست شامل **300 نمونه** است.

---

## 🛠️ Technologies

- 🐍 Python
- 📊 Pandas
- 🔢 NumPy
- 📈 Matplotlib
- 📊 Seaborn
- 🤖 Scikit-learn
- 📓 Jupyter Notebook

---

## 🔎 مراحل پروژه

در این پروژه مراحل زیر انجام شده است:

1. وارد کردن کتابخانه‌ها
2. خواندن Dataset
3. بررسی آماری داده‌ها
4. رسم نمودار و بررسی داده‌ها
5. مشخص کردن Feature و Target
6. تقسیم داده‌ها به Training و Testing
7. ساخت مدل Linear Regression
8. آموزش مدل
9. پیش‌بینی روی داده‌های تست
10. نمایش نتایج به صورت نمودار

---

## 🤖 Machine Learning Model

مدل استفاده‌شده در این پروژه:

**Linear Regression**

- **Feature:** `Engine_Size_L`
- **Target:** `Fuel_Consumption_L_per_100km`

---

## 📁 Project Structure

```text
engine-size-fuel-consumption-prediction/
│
├── engine-size-fuel-consumption-prediction.ipynb
├── engine_size_fuel_consumption.csv
└── README.md
```

---

## ▶️ How to Run

ابتدا کتابخانه‌های مورد نیاز را نصب کنید:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```

سپس Jupyter Notebook را اجرا کنید:

```bash
jupyter notebook
```

و فایل زیر را باز کنید:

```text
engine-size-fuel-consumption-prediction.ipynb
```

> توجه: فایل `engine_size_fuel_consumption.csv` باید در کنار فایل Notebook قرار داشته باشد.

---

## 📚 Learning Purpose

این پروژه برای تمرین مفاهیم پایه‌ی **Machine Learning** ساخته شده و بخشی از مسیر یادگیری من در زمینه‌ی هوش مصنوعی است.

---

## 👩‍💻 Author

**Fatemeh Rahimi**

Beginner AI & Machine Learning Developer 🌱

⭐ اگر این پروژه برای شما مفید بود، خوشحال می‌شوم به آن Star بدهید.

