# FinalProject_RakaminDS
Stage 1 Exploratory Data Analysis - 259 Analytics
## Content
- Descriptive Analysis
- Univariate Analysis
- Multivariate Analysis
- Business Insight

### 1. Descriptive Statistics

- Kolom dengan tipe data pada dataset E Commerce Dataset
 sudah sesuai
- Beberapa kolom yang memiliki nilai kosong antara lain =
 `Tenure, WarehouseToHome, HourSpendOnApp,
 OrderAmountHikeFromlastYear, CouponUsed, OrderCount,
 DaySinceLastOrder`
- Tidak ada kolom yang memiliki nilai summary 
(min/mean/median/max/unique/top/freq) aneh

### 2. Univariate Analysis

- Terdapat Outliers = `Tenure, WarehouseToHome, HoursSpend OnApp, NumberOfDeviceRegistered, NumberOfAddress, CouponUsed, OrderCount, DaySinceLastOrder, CashbackAmount`
- Skewed = Hampir semua skewed positif
- Untuk Target `Churn` terdapat class imbalance

### 3. Multivariate Analysis

Beberapa hal dapat diperhatikan dari Heatmap:

- `OrderCount` - `CouponUsed` = 0.75 (Korelasi tinggi perlu diperhatikan)
- `Churn` - `Complain` = 0.25 (Semakin tinggi complain semakin besar kemungkinan chum:
- `Churn` - `Tenure` = -0.35 (Semekin rendah Tenure semakin besar kemungkinan untuk Churn)

### 4. Business Insight

Setelah melakukan analisis diatas dapat ditarik beberapa insight

- Customer dengan **Tenure** rendah memiki kecendeningan untuk **Churn** lebih tinggi
- Customer yang pernah melakukan **Complain** lebih banyak memiliki kecenderungan untuk **Churn** lebih tinggi
- Customer dengan **status single** memiliki tingkat **churn** paling tinggi dibandingkan status lainnya
