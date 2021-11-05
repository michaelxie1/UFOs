# UFOs

Overview:
The purpose of this project was to learn the basics of web development through HTML, CSS, and JavaScript. We were able to extract data from a different JavaScript file and allow for user input to find certain data fields. We also learned to utilize tools such as Bootstrap to cut down the time to implement the CSS within our webpage. It allowed for us to have a basic understanding of websites and how we could extract data using these tools.

Results:
In order to perform a search, the user must input results that match the data shown from the JavaScript file. For example, to get the first result of the city Benton, we can extract that one piece of information by entering the date and city exactly how they are displayed (1/10/2010 & “benton”). This allows us to narrow down the search and extract the first piece of data since these two parameters are the only ones necessary to grab that particular piece of data. Different fields can be filled out to narrow down searches and obtain more results. 
![SearchEngineDescription](https://user-images.githubusercontent.com/60826549/140572788-b00c4db2-a4a6-40d7-8814-b7475ae57146.PNG)

For example, if the CEO wanted to utilize all the data from a certain date, entering a certain date like 1/5/2010 would extract the UFO instances observed on that date only.
![SearchEngineDescription2](https://user-images.githubusercontent.com/60826549/140572800-fe9ca875-8725-4fa2-993b-812b9ae4d4dd.PNG)



Summary:
Some drawbacks to this webpage would be the fact that the search engine criteria are case-sensitive, so capitalizing the letters for the cities, states and countries would show invalid results, despite it being “correct”. Also, within the date field, typically 0’s is implemented to show blank space (e.g., 01/10/2010). This would also result in invalid results as well. In order to solve these, a method can most likely be implemented to ignore the space of the characters, and a function can be written to remove the 0’s from the input, should they be unnecessary. 
