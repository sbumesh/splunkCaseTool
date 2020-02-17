# splunkCaseTool
Splunk Computer Aided software Engg Tool

Software used : Python, 
                Tkinter (https://docs.python.org/3/library/tkinter.html)  
                Splunk Search utility (https://docs.splunk.com/File:8.0.0_new_searchView-compressor.png)

This   is a  CASE tool for Splunk search utility (https://docs.splunk.com/File:8.0.0_new_searchView-compressor.png), where it generates entire Search command (https://docs.splunk.com/Documentation/SplunkInvestigate/Current/SearchReference/SearchCommandExamples)  such as select, filter, group by, and  rename commands based on file selected from your folders.
                  
                  Case Tool Output  
                  
                  
Input: ![Input csv file](/imdb_Internet_Movies_Database.csv)

Splunk output :![Case tool output](splunkCaseToolutput.txt)

                  Gui Features   


![Main Screen](/splunkcasetool.PNG)

                   Textbox Popup Menu(https://developer.android.com/reference/android/widget/PopupMenu) 

left click on text area to display popup menu(https://developer.android.com/reference/android/widget/PopupMenu) related for textBox with additional commans to assist.
text box utility popup to copy text from text box , or select all and even pase from clipboard, it also has option to wrap long text.
![Popupmenu For text](/popupmenuhiForTextbox.PNG)

Sort by popup has option to change Code generated the sort order from descndign to ascending
![Popupmenu For text](/popupmenuhiForTextboxSortBY.PNG)


Where by popup can be used  to change the default != to = , and or to and condition
![Popupmenu For text](/popupmenuhiForTextboxwhereby.PNG)

Replace using Dialog box :  can be used  to change text content in the text box area.
![Popupmenu For text](/replaceusingdialog.PNG)
