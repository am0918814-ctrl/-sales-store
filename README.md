# Sales Store

**Team:** Analytix

تحليل بيانات مبيعات متجر بهدف تحديد المنتجات الأكثر مبيعًا، ومراقبة الأداء الشهري، وتحليل العوامل المؤثرة على الإيرادات مثل عدد الطلبات ومتوسط سعر البيع.

## Objectives
- رصد المبيعات شهريًا وتحديد الاتجاهات.
- ترتيب المنتجات والفئات حسب الإيرادات والكمية.
- حساب KPIs: إجمالي الإيرادات، متوسط قيمة الطلب، عدد العملاء/الطلبات.

## Dataset (sample)
File: `data/sales_sample.csv`

Columns:
- `order_id` — معرف الطلب
- `order_date` — تاريخ الطلب (YYYY-MM-DD)
- `product` — اسم المنتج
- `category` — الفئة
- `quantity` — العدد
- `unit_price` — سعر الوحدة
- `total_price` — السعر الإجمالي (quantity * unit_price)
- `city` — المدينة
- `channel` — قناة البيع (Online/Store)

## Quickstart

```bash
# 1) اختياري: إنشاء بيئة عمل افتراضية
python -m venv .venv
# Windows: .venv\Scripts\activate
# Linux/Mac: source .venv/bin/activate

# 2) تثبيت المتطلبات
pip install -r requirements.txt

# 3) تشغيل التحليل المبدئي
python src/analysis.py
```

سيظهر لك مخرجات KPIs سريعة وبعض التجميعات الأساسية في الطرفية.

## Project Structure

```
sales-store/
├─ data/
│  └─ sales_sample.csv
├─ reports/
├─ src/
│  └─ analysis.py
├─ .gitignore
├─ requirements.txt
└─ README.md
```

## Suggested Questions
- ما هي الفئات والمنتجات الأعلى إيرادًا؟
- كيف يتغير حجم المبيعات شهريًا؟
- ما الفرق بين أداء Online و Store؟
- ما هي المدن الأفضل أداءً؟

## Contributors (Team Analytix)
- Abdelrahman Mohamed
- (أضف باقي الأسماء هنا)