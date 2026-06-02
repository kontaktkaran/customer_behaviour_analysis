**# customer_behaviour_analysis**

*Summery*

Analysis of customer purchase behavior across categories, demographics, and segments. This project includes Python notebooks for data validation, SQL scripts for deriving business insights, and an interactive Power BI dashboard to visualize revenue drivers, discount effectiveness, product performance, and customer segmentation.

notebooks/customer_data_cleaning.ipynb — Python notebook for reproducible cleaning, validation, and export of sample dataset.
customer_behaviour_analysis.pbix -- PowerBI reports
dashboardScreenshots.png- Power BI dashboard Screenshots



**sql/ — SQL scripts:**


01_category_revenue.sql — revenue by product category.

02_discount_effectiveness.sql — impact of discounts on purchase value.

03_gender_revenue.sql — revenue contribution by gender segments.

04_high_spenders_discount.sql — identify premium discount‑sensitive customers.

05_top_bottom_ratings.sql — top/bottom products by average review rating.

06_shipping_type.sql — compare average purchase by shipping type.

07_subscription_analysis.sql — subscription vs non‑subscription spend.

08_discount_usage_products.sql — products with highest discount usage %.

09_customer_segmentation.sql — new, returning, loyal customer segmentation.

10_top_products_per_category.sql — top 3 products within each category.

11_loyalty_vs_subscription.sql — repeat buyers vs subscription adoption.

12_age_group_revenue.sql — revenue contribution by age group.


**------------------------------------**
*Business problems solved*
**---------------------------------------**

💡 1️⃣ Category Revenue (01_category_revenue.sql)
Insight: Electronics dominate revenue (≈ 0.49 M), while outerwear lags.
Recommendation: Reallocate marketing spend — reduce low‑performing categories by 20 % and boost electronics promotions by 30 % to maximize ROI.

💡 2️⃣ Discount Effectiveness (02_discount_effectiveness.sql)
Insight: Discounted purchases show higher average spend (≈ ₹ 650 vs ₹ 341 non‑discount).
Recommendation: Introduce tiered discounts (5 %, 10 %, 15 %) for high‑value items to lift conversion by 15 %.

💡 3️⃣ Gender Revenue (03_gender_revenue.sql)
Insight: Female customers contribute ≈ 35 % of total spend, slightly behind “Other” (≈ 39 %).
Recommendation: Launch gender‑specific campaigns and personalized recommendations to increase female segment revenue by 10 %.

💡 4️⃣ High‑Spenders Discount (04_high_spenders_discount.sql)
Insight: Premium customers respond strongly to discounts.
Recommendation: Create a VIP loyalty tier offering exclusive 20 % discounts and early access — expected +25 % retention among top spenders.

💡 5️⃣ Top/Bottom Ratings (05_top_bottom_ratings.sql)
Insight: Gloves (3.9 ⭐) vs Phones (2.9 ⭐).
Recommendation: Improve low‑rated product quality and post‑purchase support; aim to raise average rating from 3.62 → 3.9 within Q3.

💡 6️⃣ Shipping Type (06_shipping_type.sql)
Insight: Free shipping and store pickup yield highest average spend (≈ ₹ 650).
Recommendation: Expand free‑shipping threshold and store‑pickup options to lift overall average spend by 20 %.

💡 7️⃣ Subscription Analysis (07_subscription_analysis.sql)
Insight: Subscribers spend ≈ ₹ 200 vs ₹ 150 non‑subscribers.
Recommendation: Promote subscription benefits (free shipping, loyalty points) to grow subscriber base by 30 % and total spend by ₹ 100 K.

💡 8️⃣ Discount Usage Products (08_discount_usage_products.sql)
Insight: Accessories and clothing show high discount usage.
Recommendation: Bundle these with electronics in cross‑category offers to increase accessory sales by 15 %.

💡 9️⃣ Customer Segmentation (09_customer_segmentation.sql)
Insight: Loyal customers (≥ 2 orders pre‑crisis) form ≈ 20 % of base but drive > 50 % revenue.
Recommendation: Target churned loyal customers with personalized win‑back emails — expected 10 % reactivation.

💡 🔟 Top Products per Category (10_top_products_per_category.sql)
Insight: Headphones, phones, and bags lead category revenue.
Recommendation: Feature these in homepage banners and influencer campaigns to boost visibility and maintain > 10 % MoM growth.

💡 11️⃣ Loyalty vs Subscription (11_loyalty_vs_subscription.sql)
Insight: Repeat buyers show higher subscription adoption.
Recommendation: Offer subscription discounts after 3 purchases to convert 20 % of repeat buyers into subscribers.

💡 12️⃣ Age Group Revenue (12_age_group_revenue.sql)
Insight: Age 26–35 drives ≈ 40 % of total spend.
Recommendation: Focus digital ads on this demographic — expected +15 % CTR and +12 % sales uplift.








