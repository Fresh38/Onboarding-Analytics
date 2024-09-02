The dataset was analyzed based on department, published topics, liked articles and 
engagement factors. Emp_030 was considered with medium level of engagement.  It looked 
for employees who have similar liked liked articles and published topics.  
To find the top 3 employees which are most similar to emp_030, I imported pandas, NumPy 
and cosine similarity libraries. The dataset was loaded by using pandas to load the csv file into 
a data frame. I preprocessed the data by ensuring that the data is clean by handling missing 
values if necessary. I converted categorical data into numerical using techniques like one.hot 
encoding. For the similarity calculation between emp_030 and other employees, this was done 
with cosine similarity. To rank and retrieve the top 3 employees, their similarity score was used 
to select the top three.  The resulting output identified the top three employees with the highest 
similarity scores. # Onboarding-Analytics
