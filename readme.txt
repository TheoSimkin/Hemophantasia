Make a copy of body_template and store it where you feel like, then edit it. 
You can define your body then load it into the game. Its a proto save system that I'm using to make it possible faster, I'll have a proper UI in game soon(tm). 
Organ slots correspond with left to right, top to bottom. The format is [ORGAN,HP] check the option list, set HP to be 0 for it to set it to max. 
Limb format is [NAME,TYPE,Length,Muscle,HP] NAME can be anything, its just a reference. TYPE has to be one from the option list. 
Muscle and length have to be integers from 0 to 7. More muscle = more damage and HP, more length = more accuracy. 
HP sets its current HP, set it to be 0 for full health. 

Read option_list for organ and limb details
Don't fuck it up, I don't have error handling.