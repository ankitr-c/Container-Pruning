
# the below code needs modification:

setVariables()
{
    #Defines the max number of continers running at specific instance of time.
    threshold=2

    #Defines the max allowed age of the containers. 
    timelimit=30
    
    #Defines the path of the data.txt file to store the record of deleted continers.
    path="/home/ankitraut0987/"

}

1. set the max threshold according to your requirements.
2. define the time limit according to your limits. [By default its 30 mins] [you can change it to days as well just use the commented days logic]
3. set the path where you want to store your data.
4. create data.txt file in the same path.