# 🧪 گزارش تست عملی مدار ستاره مثلث دستی

## ⚙️ تنظیمات تست
- موتور سه‌فاز ۱۱ کیلووات  
- ولتاژ ۴۰۰ ولت  
- اجزای مدار طبق لیست قطعات

## ✅ موارد تست

| مورد تست              | انتظار              | نتیجه | وضعیت |
|-----------------------|---------------------|--------|--------|
| راه‌اندازی در حالت ستاره | جریان کم            | ✅     | Pass   |
| سوییچ دستی به دلتا     | رسیدن به سرعت کامل  | ✅     | Pass   |
| حفاظت اضافه‌بار        | توقف موتور          | ✅     | Pass   |
| قطع فاز                | قفل مدار            | ✅     | Pass   |
| نمایش جریان توسط CT    | مقدار دقیق           | ✅     | Pass   |

## 📌 مشاهدات
- سوییچ دستی نیاز به دقت اپراتور دارد  
- چراغ‌های سیگنال وضعیت را واضح نشان می‌دهند  
- مدار فرمان پایدار و ایمن است

## 🏁 نتیجه‌گیری
مدار عملکرد قابل‌اعتمادی در شرایط نرمال و خطا دارد.

# 🧪 Test Report – Star-Delta Manual Circuit

## ⚙️ Test Setup
- 11kW three-phase motor  
- 400V AC supply  
- Components as listed in the BOM

## ✅ Test Cases

| Test Case              | Expected Outcome      | Result | Status |
|------------------------|-----------------------|--------|--------|
| Start in Star mode     | Reduced current        | ✅     | Pass   |
| Manual switch to Delta | Full speed achieved    | ✅     | Pass   |
| Overload protection     | Motor stops            | ✅     | Pass   |
| Phase failure detection | System lockout         | ✅     | Pass   |
| CT current readings     | Accurate measurement   | ✅     | Pass   |

## 📌 Observations
- Manual switching requires operator timing  
- Signal lamps clearly indicate status  
- Control circuit is stable and safe

## 🏁 Conclusion
The circuit performs reliably under both normal and fault conditions.
