# BIKE SALES ANALYSIS
Bike Sales Analysis Project using Excel. This repo on Bike Sales Analysis will help to understand the various crucial functions available in Excel, such as Conditional Formating, Text Functions, Statistical Function, Vlookup, Pivot Tabel and Pivot Chart to make Visualization

- Dashboard : https://public.tableau.com/views/MarketingConcernDashboard/Dashboard43?:language=en-US&:display_count=n&:origin=viz_share_link. In this dashboard, you have the flexibility to filter the data by day, enabling you to update and analyze the specific information you are interested in.
- Report : https://drive.google.com/drive/folders/1WRmrndqBUmNAg-i7HVBQILoVbMOvBq7a?usp=sharing

## Business Understanding
Objectives: 
- To understand bike sales in December 2021 and user preferences for the products (You can access my report through this link:
https://drive.google.com/drive/folders/1WRmrndqBUmNAg-i7HVBQILoVbMOvBq7a?usp=sharing)
- To understand purchasing patterns of different demographic groups to identify areas where it needs to concentrate its marketing efforts (You can access my dashboard in Tableau through this link: https://public.tableau.com/views/MarketingConcernDashboard/Dashboard43?:language=en-US&:display_count=n&:origin=viz_share_link).

## Business Questions:
1. How was the sales performance in December 2021?
2. Which product generated the highest revenue?
3. Which product is most favored by customers?
4. What is the demographic profile of customers?
5. What are the trends among customers regarding the products?
6. Which country, state and product should be the focus of concentrated marketing efforts?

## Data Understanding
- Sales Order: order ID
- Date: date when the customer placed the order
- Day: day when the customer placed the order
- Month: month when the customer placed the order (December)
- Year: year when the customer placed the order (2021)
- Customer Age: age of the customer
- Age Group: age group based on age range (Youth(<25), Young Adults(25-34), Adults(35-64))
- Customer Gender: gender of the customer (F, M)
- Country: country of origin of the customer
- State: state of origin of the customer
- Product_Category: product category (Bikes)
- Subcategory: product subcategory (Mountain Bikes)
- Product_Description: product description (Model, Color, and Size)
- Order_Quantity: quantity of products purchased
- Unit_Cost: production cost per unit
- Unit_Price: selling price per unit
- Profit: profit per unit
- Cost: total production cost per quantity of products purchased
- Revenue: total revenue per quantity of products purchased

## Data Cleaning and Preparation 
- Fixing and Removing Duplicate Data
- Fixing missing data
- Fixing Inaccurate Values
- Creating a new feature (Total_Profit, Sales Summary)
- Parse Product_Description to move bike, size and color (Using text function)

## Analysis the Data
- Apply statistical functions to perform aggregations
- Using Pivot Tabel and Pivot Chart to make Visualization
- Using VLOOKUP to find data by Sales Order

## Conclusion and Recomendation Action
- Model produk yang memiliki jumlah order terbanyak adalah Mountain 200, sedangkan yang memiliki jumlah order paling rendah adalah Mountain 100. Oleh karena itu, tim pemasaran dapat mempertimbangkan strategi khusus untuk meningkatkan penjualan Mountain 100 serta memperkuat posisi Mountain 200 melalui promosi tambahan atau penyesuaian strategi pemasaran.
- Canada memiliki jumlah pelanggan, jumlah order, dan revenue yang paling rendah. Dalam konteks Gender dan Age Group, target pelanggan di Canada baru mencakup satu kelompok usia, yaitu Young Adults, sementara kelompok usia Adults dan Youth belum terjangkau di negara tersebut. Oleh karena itu, tim pemasaran dapat mempertimbangkan strategi khusus di Canada, terutama untuk kelompok usia Adults dan Youth yang belum terjangkau.
- Target pelanggan di Germany juga baru mencakup satu kelompok usia, yaitu Adults, sementara kelompok usia Young Adults dan Youth belum terjangkau di negara tersebut. Selain itu
  Dari segi Gender, terjadi perbedaan signifikan antara revenue customer perempuan dibandingkan laki-laki. Oleh karena itu, tim pemasaran dapat mempertimbangkan strategi khusus di Germany, terutama untuk kelompok usia Young Adults dan Youth yang belum terjangkau, serta untuk pelanggan laki-laki yang jumlahnya terbatas.
- Perempuan cenderung lebih memilih sepeda dengan warna Silver, sementara Pria lebih cenderung memilih sepeda dengan warna Hitam. Disarankan untuk menawarkan opsi warna kepada pelanggan baru dengan mempertimbangkan dominasi warna yang umumnya dipilih oleh pelanggan sebelumnya. warna Silver direkomendasikan untuk pelanggan Perempuan, sementara warna Hitam direkomendasikan untuk pelanggan Laki-Laki.
- Perempuan dengan kategori usia Adults (35-64) cenderung memilih sepeda dengan size 46, ketegori usia Young Adults(25-34)cenderung memilih sepeda dengan size 42 dan kategori usia Youth (<25) cenderung memilih sepeda dengan size 38. Pria dengan kategori usia Adults (35-64) cenderung memilih sepeda dengan size 38, kategori usia Young Adults(25-34) cenderung memilih sepeda dengan size 38 dan kategori usia Youth (<25) cenderung memilih sepeda dengan size 46. Disarankan untuk menawarkan size sepeda kepada pelanggan baru dengan mempertimbangkan
dominasi size yang umumnya dipilih oleh pelanggan sebelumnya

Visualization/Result
https://public.tableau.com/views/MarketingConcernDashboard/Dashboard43?:language=en-US&:display_count=n&:origin=viz_share_link
https://drive.google.com/drive/folders/1WRmrndqBUmNAg-i7HVBQILoVbMOvBq7a?usp=sharing 
 
