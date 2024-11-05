# Python-Big-Data-Analytics-Project
## Project Description——User Purchase Behavior Prediction
This project is based on the user access data provided by the existing server (e.g., what pages users have previously viewed, how long they have viewed them, some attributes of the page, whether it is a holiday, etc.), 
to conduct big data analysis and predict whether certain visits will result in purchasing behaviors
## Introduction to the data
The data attributes include: 10 numerical attributes and 8 category attributes, and the meanings indicated by the variables in each column are as follows:
“User-Related Pages”, ‘User Page Duration’, ‘Information-Related Pages’, ”Information-Related Page Duration ”, “product-related pages” and “product-related page visit duration” 
indicate the number of different types of pages visited by the visitor in the session and the total time spent in these page categories. The values for these characteristics are derived from the URL Session information of the page visited by the user, 
and the Session records real-time updated information about the actions taken by the user (e.g., moving from one page to another).   
The “Bounce Rate”, “Exit Rate” and “Page Value” characteristics represent metrics calculated by Google Analytics for each page of an e-commerce site. Bounce Rate. 
Bounce rate is the percentage of visits to a group of pages or a page that are made by users who leave after reading only one page. Bounce count is the number of times a visitor exits from an entry page without visiting any other page on your site.    
The dataset also includes “OS Type”, “Browser Type”, “Region”, “Traffic Type” , “Visitor Type” (old or new), and “Weekend”.
The last column of the training set, train.csv, has the attribute “Purchase” labeled as a category, with 1 being purchased and 0 being not purchased.
