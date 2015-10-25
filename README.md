# MusicDB
Automating record creation of all the music I own


I have a 200 GB collection of music. I like to maintain an Excel sheet of Artist - Album that I populate manually once every few months.
I'm trying to automate this process.

Directory structure I am following: 

  Subfolders may contain tracks
  
  Artist folders may contain tracks that are not contained in any album sub folder
  

  Music
  |
  |-Adele
    |-19
      -song1.mp3
      -song2.mp3
    |-21
      -song1.mp3
      -song2.mp3
  |-Savages
    |- Silence Yourself
        |- Shut Up.mp3
        |- Husbands.mp3
  |- Iron Maiden
      |- Powerslave
          |-Powerslave.mp3
      |- Number of the beast (LIVE).mp3
      
      
      
I want these in Excel to be written as 

ARTIST                          ALBUM                               SONGS



Prerequisites: 

Install openpyxl 

      $ pip install openpyxl
      
      OR
      
      $ easy_install openpyxl



      
