# menu calc
Calculator for Rofi/dmenu(2)  
[Screencast](https://gfycat.com/SociableDopeyHerald)

#####usage:
menu calc uses bc as the backend and will accept any operations bc is able to do  
`= -h` show help  
`= "4+4"`  
`= "(4+2)/(4+3)"`  
`= "4^2"`  
`= "sqrt(4)"`  
`= "c(2)"`

Operations may work without quotations, but are not guarenteed to do so

The answer can me used for further calculations inside Rofi/dmenu

#####dependencies
bc  
xclip  
Rofi or dmenu(2)
