Instructions on how to use Bus Driver Diary App

# Bus1
![Bus Image](https://github.com/MarkBozinovic/BusReadMe/blob/main/bus.jpg)
<!---https://stackoverflow.com/questions/41604263/how-do-i-display-local-image-in-markdown--->
<!---https://www.online-tech-tips.com/free-software-downloads/combine-text-files/--->
<!---https://www.transdevmelbourne.com.au/news/latest-news/latest-news/media-release-first-victorian-built-electric-bus-to-hit-the-road/--->


# Bus Driver Shift Application
In this project, data is stored on an android device for
Bus Operators to record their shifts by date, day, shift number,
the bus they drove and any associated notes.
Shifts can be updated and deleted. The app requires
the user to allow permission to store the file in 
your mobile device in: Settings-> Apps-> Goto the App
in this case "Bus1"-> Permissions-> allow.
Facets of Java Android programming used include
SQLite, Text File commit and Data Manipulation

Use of the application:

1. **Record data in fields**\
  i) Date ddmmyy eg. 240121\
  ii) Day eg. Mon, Tue,.... Accessed by a pull down preselected menu\
  iii) Shift eg. 6401, 6308, .......\
  iv) Bus - record the bus number driven\
  v) Note - any incidents, issues with bus can be written
2. **Add Shift** - once fields completed, "ADD SHIFT" button
3. **View Shifts in database** - select "VIEW DATA" button and a pop up 
of the shifts added will appear preceded by the "record number" created 
by the database in your phone
4. **Display Record** - from the record number in the database, enter this number
in the "Get Record" field and select the "DISPLAY RECORD" button. This will
populate the fields of Date, Day, Shift, Bus and Note on the app.
5. **Change Record** - after selecting the display record, details of
that particular record can be change (Note for example, or any field)
and then once completed, select the "UPDATE" button
6. **Delete Record** - to delete a record, from the database insert
the record number to be deleted in the "Record # to Delete" field 
and then select the "DELETE" button. 
7. **Clear all fields** - if populated with any data and you want
to simply clear the fields without deleting, changing or inserting
and data, select the "CLEAR" button.
