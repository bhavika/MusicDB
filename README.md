# MusicDB
Automating record creation of all the music I own


I have a 200 GB collection of music. I like to maintain an Excel sheet of Artist - Album that I populate manually once every few months.
I'm trying to automate this process.

Directory structure I am following: 

1.Subfolders may contain tracks
2. Artist folders may contain tracks that are not contained in any album sub folder
  

I want these in Excel to be written as 

|ARTIST|--------------------|ALBUM|------------------------|SONGS|


I need to account for new lines between artists and albums. 


Prerequisites: 

Install openpyxl 

      $ pip install openpyxl
      
      OR
      
      $ easy_install openpyxl



      
