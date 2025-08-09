# 📄 مشخصات عملکردی مدار ستاره مثلث دستی

## 🎯 هدف
راه‌اندازی ایمن و مؤثر موتور سه‌فاز ۱۱ کیلووات با استفاده از مدار دستی ستاره مثلث.

## ⚙️ مشخصات موتور
- توان: ۱۱ کیلووات  
- ولتاژ: ۴۰۰ ولت  
- فرکانس: ۵۰ هرتز  
- ضریب توان: ۰٫۸۵  
- راندمان: ۹۰٪

## 🔁 فرآیند عملکرد
۱. فشردن شستی استارت → فعال شدن کنتاکتور اصلی و ستاره  
۲. پس از زمان مشخص یا سوییچ دستی → قطع ستاره، وصل دلتا  
۳. فشردن شستی استپ → قطع همه کنتاکتورها

## 🔌 ورودی‌ها
- شستی استارت (۲ عدد)  
- شستی استپ (۲ عدد)  
- شستی دوبل (۲ عدد)  
- کنترل فاز

## 🔋 خروجی‌ها
- عملکرد موتور  
- نمایش جریان توسط آمپرمترها  
- وضعیت توسط چراغ‌های سیگنال

## 🛡️ حفاظت و ایمنی
- MCCB با جریان نامی ۳۲ آمپر  
- MPCB با جریان نامی ۲۵ آمپر  
- کنترل فاز برای تشخیص قطع یا جابجایی فاز  
- فیوز مینیاتوری ۲ آمپر برای مدار فرمان

# 📄 Functional Specification – Star-Delta Manual Circuit

## 🎯 Objective
To safely and efficiently start an 11kW three-phase motor using a manual Star-Delta configuration.

## ⚙️ Motor Specifications
- Power: 11 kW  
- Voltage: 400V AC  
- Frequency: 50 Hz  
- Power Factor: 0.85  
- Efficiency: 90%

## 🔁 Functional Flow
1. Press Start → Main and Star contactors engage  
2. After delay or manual switch → Star disengages, Delta engages  
3. Press Stop → All contactors disengage

## 🔌 Inputs
- Start push buttons (2)  
- Stop push buttons (2)  
- Double push buttons (2)  
- Phase control relay

## 🔋 Outputs
- Motor operation  
- Current readings via ammeters  
- Status indication via signal lamps

## 🛡️ Safety Features
- MCCB rated at 32A  
- MPCB rated at 25A  
- Phase control relay for fault detection  
- 2A miniature fuse for control circuit
