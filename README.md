print("hello if you want to play write play")

while True:
    player = input("")
    
    if player == "play":
        print("jungle or desert or country")
        user = input("")

        while True:
            if user == "jungle" or user == "1":
                print("I am in the middle of some Trees and scary snakes")
                print("I am lost in the jungle in the middle of the jungle and you should go to the north")
                print("if you want to go north write 1")
                man = input("")
                
                if man == "1" :
                    print("There are apple Trees")
                    print("to eat them write eat or 1")
                    apple = input("")
                    
                    if apple == "1"or apple == "eat":
                        print("Ymm ymm the apple was very delicious")
                        print("I got a map")
                        print("if you want to know what is inside it write map")
                        map_input = input("")
                        
                        if map_input == "map" :
                            print("written in it the distance from cario to s farm is 1 km")
                            print("you will go to the river then walk next to river then you will be in cario")
                            print("you want to run or walk to the river")
                            walk_river = input("")
                            
                            if walk_river == "run" :
                                print ("hu hu hu this is the river")
                                print ("what is your opinion I ride fayrouz boat or dance yacht write 1 for fayrouz and 2 for yacht")
                                boat_yacht = input("")
                            elif walk_river == "walk" :
                                print("this is so far but fanialy this is the sea")
                                print ("what is your opinion I ride fayrouz boat or dance yacht write 1 for fayrouz and 2 for yacht")
                                boat_yacht = input("")
                                 
                            if boat_yacht == "1" :
                                print("The fayrouz boat is very Nice ")
                                print("write go to start the trip with the boat")
                                move = input("")
                            elif boat_yacht == "2" :
                                print("The dance yacht is very Nice ")
                                print("write go to start the trip with the yacht")
                                move = input("")
                            
                            else :
                                print("You are still lost")     
                                
                            if move == "go" :
                                print("we have arrived")
                                print("to get down from yacht to cario write get down ")
                                down = input("")
                                if down == "get down" :
                                    print("this is the street where I live in the middle of it")
                                    print("Thank You for your help")
                        else :
                            print("You are still lost") 
                    else:
                        print("You chose not to eat the apple.")
                        print("You are still lost")
                
                else:
                    print("You chose not to go north.")
                    print("You are still lost")
                
                break
            
            elif user == "desert" or user == "2":
                print("I am in a cave in a big mountain")
                print("I am lost in the desert, the center of the desert")
                man = input("")
                
                if man == "1" :
                    print("There are cranberry")
                    print("to eat them write eat or 1")
                    cranberry = input("")
                    
                    if cranberry == "1"or cranberry == "eat":
                        print("Ymm ymm the cranberry was very delicious")
                        print("I saw Bedouin men,I will ask them about the way ")
                        print("to ask them write ask or 1 ")
                        map_input = input("")
                        
                        if map_input == "ask" or map_input == "1" :
                            print("written in it the distance from cario to s farm is 1 km")
                            print("you will go to the river then walk next to river then you will be in cario")
                            print("you want to run or walk to the river")
                            walk_river = input("")
                            
                            if walk_river == "run" :
                                print ("hu hu hu this is the river")
                                print ("what is your opinion I ride fayrouz boat or dance yacht write 1 for fayrouz and 2 for yacht")
                                boat_yacht = input("")
                            elif walk_river == "walk" :
                                print("this is so far but fanialy this is the sea")
                                print ("what is your opinion I ride fayrouz boat or dance yacht write 1 for fayrouz and 2 for yacht")
                                boat_yacht = input("")
                                 
                            if boat_yacht == "1" :
                                print("The fayrouz boat is very Nice ")
                                print("write go to start the trip with the boat")
                                move = input("")
                            elif boat_yacht == "2" :
                                print("The dance yacht is very Nice ")
                                print("write go to start the trip with the yacht")
                                move = input("")
                            
                            else :
                                print("You are still lost")     
                                
                            if move == "go" :
                                print("we have arrived")
                                print("to get down from yacht to cario write get down ")
                                down = input("")
                                if down == "get down" :
                                    print("this is the street where I live in the middle of it")
                                    print("Thank You for your help")
                        else :
                            print("You are still lost") 
                    else:
                        print("You chose not to eat the apple.")
                        print("You are still lost")
                
                else:
                    print("You chose not to go north.")
                    print("You are still lost")
                
                break

            elif user == "country" or user == "3":
                print("I am on a long road I did not know")
                print("I am lost in the country in the center of the country")
                man = input("")
                
                if man == "1" :
                    print("There are apple Trees")
                    print("to eat them write eat or 1")
                    apple = input("")
                    
                    if apple == "1"or apple == "eat":
                        print("Ymm ymm the apple was very delicious")
                        print("I got a map")
                        print("if you want to know what is inside it write map")
                        map_input = input("")
                        
                        if map_input == "map" :
                            print("written in it the distance from cario to s farm is 1 km")
                            print("you will go to the river then walk next to river then you will be in cario")
                            print("you want to run or walk to the river")
                            walk_river = input("")
                            
                            if walk_river == "run" :
                                print ("hu hu hu this is the river")
                                print ("what is your opinion I ride fayrouz boat or dance yacht write 1 for fayrouz and 2 for yacht")
                                boat_yacht = input("")
                            elif walk_river == "walk" :
                                print("this is so far but fanialy this is the sea")
                                print ("what is your opinion I ride fayrouz boat or dance yacht write 1 for fayrouz and 2 for yacht")
                                boat_yacht = input("")
                                 
                            if boat_yacht == "1" :
                                print("The fayrouz boat is very Nice ")
                                print("write go to start the trip with the boat")
                                move = input("")
                            elif boat_yacht == "2" :
                                print("The dance yacht is very Nice ")
                                print("write go to start the trip with the yacht")
                                move = input("")
                            
                            else :
                                print("You are still lost")     
                                
                            if move == "go" :
                                print("we have arrived")
                                print("to get down from yacht to cario write get down ")
                                down = input("")
                                if down == "get down" :
                                    print("this is the street where I live in the middle of it")
                                    print("Thank You for your help")
                        else :
                            print("You are still lost") 
                    else:
                        print("You chose not to eat the apple.")
                        print("You are still lost")
                
                else:
                    print("You chose not to go north.")
                    print("You are still lost")
                
                break

            else:
                print("Choose one of the following:")
                user = input("")
        # finding-the-lost
