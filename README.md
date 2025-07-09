# **Amazon-Product-Review**
Welcome to the Amazon Product Review Repository! In this repository, I analyzed and reviewed Amazon Products by categories, discount, reviews, revenue and more. The project serves as a guide to sellers on the Amazon Platform to guide them in making informed decisions.

## Understanding the Project
Upon receiving this project to work on, the first thing I did was to read carefully through the Case Study for the Amazon Product Review Analysis. This gave me the understanding of what the required outputs from this Dataset are. With the understanding of what the required outputs are, I went on to load the data-set into my Excel Application. I spent quite a number of hours going through the entire data-set, having in mind the required results. This gave me clear understanding of the required columns I need to retain, the columns that are not need for my analysis, and the missing columns that I would need to create to ensure that I am able to analyze the Data-set and come out with the desired report that would make Sellers on the Amazon Platform reach an informed decision.

I also found out that the data-set contains 1466 Rows and 16 Columns with the first row being the Header.

The 16 columns are: product_id, product_name, category, discounted_price, actual_price, discount_percentage, rating, rating_count, about_product, user_id, user_name, review_id, review_title, review_content, img_link, product_link


## Project Highlights
- **Name of Client:** RetailTech Insights
- **Industry:** E-commerce Analytics
- **Tools Used:** Microsoft Excel ( Excel Power Query | Excel Functions | Pivot Tables |  Conditional Formatting |  Charts | Slicers )
- **Colour Scheme:** Amazon Logo Color (Black and Orange)

## Methodology
•	Data Set Ingestion  |  Transformation  |  Modeling  |  Visualization |  Analysis  |  Presentation.


## Dataset Provided
- **Numbers of Columns:** 16
- **Numbers of Records:** 1,465
- **Source Data Set:** Web-scraped Amazon product review data
- **Columns Headers:** (Product ID  |  Product Name  |  Category  | Discounted Price  | Actual Price  |  Discount Percentage  | Rating  |  Ranting Count  | About Product  |  User ID  | User Name | Review ID  |  Review Title  |  Review Content  |  Img Link  |  Product Link


## Data Cleaning Process
- Deleting Columns that are not required
- Deleting Rows that are not required (Remove Duplicates)
- Deleting Rows with black cells (Using Find and Replace and Blank)
- Using Left and Find delimiter function to Create a new Category Column: =LEFT(D4,FIND("|", D4)-1
- Reducing the Product Name to 30 Characters with left function: =LEFT(C2,30)
- Use of IF function to create additonal column: =IF(F2<=10%, "0  to 10%",IF(F2<=20%,"11 to 20%",IF(F2<=30%,"21 to 30%",IF(F2<=40%,"31 to 40%",IF(F2<=50%,"41 to 50%",IF(F2<=60%,"51 to 60%",IF(F2<=70%,"61 to 70%",IF(F2<=80%,"71 to 80%",IF(F2<=90%,"81 to 90%","Above 90%")))))))))
- Using Excel Power Query to create addictional columns
  
![Remove Duplicate](https://github.com/user-attachments/assets/553701a5-10cf-4a82-87ea-ac3bb21e4e94)

![Remove blank cell rows](https://github.com/user-attachments/assets/6aa9aa89-9598-42ca-98e9-0a093fc3c778)


## Pivot Table
The Pivot Table aspect was pretty straightforward using the Amazon Product Review Analysis Tasks as a guide. 
After cleaning the Data-set, I click on the Insert Tab and click Pivot Table and left the default setting of creating the pivot table on a new excel sheet.
One after the other, I created all the Pivot Table required.

![Pivot Table creation](https://github.com/user-attachments/assets/a84a8e8b-99d0-481c-bc25-5db993da0a3f)


**Completed Pivot Tables**

![Pivot table together](https://github.com/user-attachments/assets/22c26749-604e-4cbc-b823-c05ca901337d)


## Dashboard

![Amazon Dashboard](https://github.com/user-attachments/assets/cf0b7da2-9e9e-4c35-9a66-ffc96ddc8744)

## Dashboard Key Highlights
- **Total Numbers of Products:** 1348
- **Total Numbers of Reviews:** 23,801,431
- **Average Discount Percentage:** 47%
- **Total Potential Revenue:** $113,641,266,52200  

### *Dashboard Bulding Process*

I started the building of the Dashboard by Adding a New Excel Sheet, and hiding the gridelines to make the environment clean. then I added a text box where I Typed the Product Name with Bold Character and using Amazon Logo and Colour (Orange and Black) as the Dashboard Color. I also added my name. I when went further to added some major Findings like the Total Numbers of Product, Total Revenue, etc. as the first Row of the dashboard.

Thereafter I started adding the charts and created from the Pivot Table by Clicking PivotChart under the Insert Tab, and formating each chart to my preference. 

![Pivot Chart 1](https://github.com/user-attachments/assets/019cddde-de1d-4298-aa21-805f98d217a2)

Defining Chart Setting

![Pivot Chart 2](https://github.com/user-attachments/assets/b1027742-9869-40fc-818c-41d4e5da414f)

Formating Chart According

![Pivot chART 3](https://github.com/user-attachments/assets/13c2ce2b-81a9-48ab-8511-314f21823ea7)



## Findings

### **Average discount percentage by product category**

![image](https://github.com/user-attachments/assets/a646f3d3-c7b0-4f97-b891-5d3bb2b00a41)

### **Numbers of products listed under each category**

![image](https://github.com/user-attachments/assets/ea063fc7-483a-4dc1-aa1c-1aa180df3fc3)

### **Numbers of review by category**

![image](https://github.com/user-attachments/assets/2c43d281-3608-4c55-ae94-6491092e0129)

### **Top 10 Products with highest average ratings**  

![image](https://github.com/user-attachments/assets/d71d1f06-4220-479e-b8e0-95a61049312f)

### **Average actual price vs the discounted price by category**

![image](https://github.com/user-attachments/assets/83feca03-acea-4870-8945-f4a727feb9e4)

### **Products with the highest number of reviews**

![image](https://github.com/user-attachments/assets/665ba550-a840-4bc6-876b-91b632d78904)

### **660 Products have Discount of 50% and above**


### **Total potential Revenue Per ategory**

![image](https://github.com/user-attachments/assets/f6763fa8-ce89-4d6d-b305-3ea9e07abeed)


## About Me
Friday Agboro ( Brand Management  |  Graphics Designer | PowerPoint Presentation Formatting |  Data Analyst )

## Contact
- Phone: +234 08059002119
- Email: widercoast@gmail.com


Thank you
