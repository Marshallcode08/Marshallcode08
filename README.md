Ryan Marshall 
Data Analytics Bootcamp
09/14/2022

            
            
                                                     **Module 1 Challenge**
                                                     

**Introduction of the Project**

      The purpose of this project is to display our ability to look through and excel spreadsheet and extract raw data, then turn it into 
an organized format so other can interpret the data. Using excel we were able to extract the data she need to see statistics on the kickstarters
she was involved in. Louise is counting on us to show her the data in concise and organize way, so she is able to make the best well informed 
decision using the data as the backbone of her decision. The purpose of this project is to use our skills with excel to give Louise the information 
on her Kickstarters and to find information to support her questions.

**Analysis Methods**

   Step 1: Gathering the data.
         The first step was to procure the data from the database in order to start. The data was raw and had no organization to it and was very
      Difficult to gather any information. This made it very difficult to start, which created the first challenge.
      
   Challenge 1: Organizing the data.
         The first step figure out what to do with this data. I had to come up with a way to get the information Louise wanted for her decision
         making process.I had to familiarize myself with data figure out how much columns and rows there were in this data set,There were 4115 rows
         and 14 columns. I created a new column using the round function and created a cell to find the percentage funded to determine to see if the
         goals were met.
         
   Challenge 2: Rounding
         This is a more personal reason this is all new to me. I understand the logic, but writing it out was very difficult. Now, you have to pick 
         the right data. The data I needed was the pledges and the goals. Once it was all calculated we we able to move on to the next step.
         
    Challenge 3: Errors
         I kept getting error messsages in some cells and could not understanbnd why? Upon further analysis I discovered the isssue and why I kept
         getting the error massage #DIV/0!. This only comes up when you are dividing by zero and the computer cannot calculate that correctly because
         number are not divisible by zero. This is where I learned about the IFERROR() function that eliminates the issue. This runs in conjunction
         with round function, which is a mathmatical function and when the #DIV/0! and replaces it with an input I put in. Now, we figured how to start
         having complete data.
         
    Step 2. Pivot Table
           Purpose of this is to give Louise the data anaylsis and displays it to her in a visual way. This way she can see the outcomes of each category
           utilizing tables, charts, and graphs. A pivot table allows you to take elements from data and develop tables to display information needed 
           for Louise to see.
           
     Challenge 1: Creating the table.
           I am a novice and I had some difficulties with developing the table, but excel makes it so easy. Once you figure out the data you can
           mix and match the data. To show how each Parent category and sub category success and fail, we would use a graph.
           
     Challenge 2: Creating Graph
           I had to create a graph, but what type of graph should I use a bar graph, line graph, or box chart. That depends what you want to see 
           I used a bar graph to show the parent category success or fail rate. The line chart was use display the Theater based on outcomes so 
           Lousie can see success and failures of specific category just by altering our chart data that derives from our pivot table. Once all the 
           graph was created we were able to use the data in all sorts of ways.
           
       The Biggest Challenge 
            The biggest issue I had with this whole project was using the conditional function Countifs() and I am sure the data  is incorrect, but 
            Cannot figure out why the information is calculating incorrectly because the formula is written correctly. The steps are all correct, but
            I cannot figure out why it is not working.
            
      Outcome 1: Success rate
            From March til June you can see alot of successful theater kickstarter then failures.
            
      Outcome 2: Failure rate
            The failure rate was very consisted through out the year.
            
      Outcomes Based on Goals
             The information I have in this chart is wrong and cannot get good data to give a a reasonable conclusion. The process was done correctly,
             But I think there are characters in my formula that I cannot see. This I will have to ask for help.
             
      Data Limitations
             Lacking more data needed to figure out more causes other than goal and pledge amounts. According to this data it says more times then not 
             if a kickstarter fails it fails for not meeting goals with pledge dollars. That is not always correct, which means there are other factors
             that the data does not show.
             
       Charts
             We could have used a pie chart that would show comparative data to figure out succcess and fail between catergories.
           
        
        
      

<!---
Marshallcode08/Marshallcode08 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
