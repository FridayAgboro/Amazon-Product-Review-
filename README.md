# Amazon-Product-Review-
Welcome to the Amazon Product Review Repository! In this repository, I analyzed and reviewed Amazon Products by categories, discount, reviews, revenue and more. The project serves as a guide to sellers on the Amazon Platform to guide them in making informed decisions.

## Understanding the Project
Upon receiving this project to work on, the first thing I did was to read carefully through the Case Study for the Amazon Product Review Analysis. This gave me the understanding of what the required outputs from this Dataset are.

With the understanding of what the required outputs are, I went on to load the data-set into my Excel Application. I sent quite a number of hours going through the entire data-set, having in mind the required results. This gave me clear understanding of the required columns I need to retain, the columns that are not need for my analysis, and the missing columns that I would need to create to ensure that I am able to analyze the Data-set and come out with the desired report that would make Sellers on the Amazon Platform reach an informed decision.

I also found out that the data-set contains 1466 Rows and 16 Columns with the first row being the Header.

The 16 columns are: product_id, product_name, category, discounted_price, actual_price, discount_percentage, rating, rating_count, about_product, user_id, user_name, review_id, review_title, review_content, img_link, product_link

## Data Cleaning
I started the Data Cleaning by deleting the columns that are not required just by holding down the control-key and selecting all the columns to be delected, then right-clicking and clicking delete.

![deleting columns](https://github.com/user-attachments/assets/2393eb22-9294-478b-9f2a-a7fa60a433ed)

Having delected the columns that I don't require, I went further in the Data-Cleaning by deleting duplicate rows by clicking Remove Duplicate under the Data Tab. This reduced the numbers of rows to 1351 from the initial 1466 Rows.

![Remove Duplicate](https://github.com/user-attachments/assets/553701a5-10cf-4a82-87ea-ac3bb21e4e94)

I also search for Blank Cells within the dataset and found 3 blank cells using the find and also blank and deleted the rows. This further reduced the number of rows to 1348 Rows.

![Remove blank cell rows](https://github.com/user-attachments/assets/6aa9aa89-9598-42ca-98e9-0a093fc3c778)

Using function Left and Find =LEFT(D4,FIND("|", D4)-1) , and Find and replace I was able to clean the Category Column.

![Category Column](https://github.com/user-attachments/assets/126ef761-c056-49ef-b3a9-437d0a9bffb5)

For the Product Name Column, I also used the Left function, =LEFT(C2,30) to reduce the number of character to 30.

Still in the Data wranging process, I created additional columns using excel functions and Excel Power Query. Example is the "Discount % Level" Column which I created with the If Function =IF(F2<=10%, "0  to 10%",IF(F2<=20%,"11 to 20%",IF(F2<=30%,"21 to 30%",IF(F2<=40%,"31 to 40%",IF(F2<=50%,"41 to 50%",IF(F2<=60%,"51 to 60%",IF(F2<=70%,"61 to 70%",IF(F2<=80%,"71 to 80%",IF(F2<=90%,"81 to 90%","Above 90%")))))))))

![If multiple](https://github.com/user-attachments/assets/687c7ce7-680b-45f0-b049-b0b90ef1b61a)

After using a couple of excel functions and Excel Power Query, I got the Dataset cleaned and ready for building my Pivot Tables.

## Pivot Table
The Pivot Table aspect was pretty straightforward using the Amazon Product Review Analysis Tasks as a guide. 
After cleaning the Data-set, I click on the Insert Tab and click Pivot Table and left the default setting of creating the pivot table on a new excel sheet.
One after the other, I created all the Pivot Table required.

![Pivot Table creation](https://github.com/user-attachments/assets/a84a8e8b-99d0-481c-bc25-5db993da0a3f)

Worthy of note is the fact that since the Data-set is about Amazon, I decided the use the Amazon Logo Color (Black and Orange) as the colour of my Pivot Table, and Dashboard.

Upon completng the creation of my Pivot Tables, I added some slicers to make for better interactions.

![Pivot Table done](https://github.com/user-attachments/assets/8e6099aa-df9d-46c8-9329-e61c43050606)

## Dashboard
I staeted the building of the Dashboard by Adding a New Excel Sheet, and hiding the gridelines to make the environment clean. then I adde a text box where I Typed the Product Name with Bold Character and using Amazon Logo and Colour (Orange and Black) as the Dashboard Color. I also added my name. I when went further to added some major Findings like the Total Numbers of Product, Total Revenue, etc. as the first Row of the dashboard.

Thereafter I started adding the charts and created from the Pivot Table by Clicking PivotChart under the Insert Tab, and formating each chart to my preference. 

![Pivot Chart 1](https://github.com/user-attachments/assets/019cddde-de1d-4298-aa21-805f98d217a2)

Defining Chart Setting

![Pivot Chart 2](https://github.com/user-attachments/assets/b1027742-9869-40fc-818c-41d4e5da414f)

Formating Chart According

![Pivot chART 3](https://github.com/user-attachments/assets/13c2ce2b-81a9-48ab-8511-314f21823ea7)

I organized the allign them properly and added slicers which I created from the Pivot Tables.

## Others
I have uploaded the Excel File containing this Project.

## Conclusion.
In conclusion, I am quite happy to work on this project knowing the Sellers on the Amazon Platform would be able to make a more informed decision as a result of the project.

THank you
