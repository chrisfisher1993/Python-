
leave_program=0
while leave_program !='q':  
  import random
  print ("This is a dice rolling simulator")
  print ("Press enter to roll")
  input()
  number=random.randint(1,6)
  if number ==1:
     print ("[--------------]")
     print ("[              ]")
     print ("[       O      ]")        
     print ("[              ]")
     print ("[--------------]")
     print()
     print("Type 'q' to quit")
     leave_program=input()
  if number ==2:
     print ("[--------------]")
     print ("[              ]")
     print ("[       O      ]")        
     print ("[              ]")
     print ("[--------------]")
     print("Type 'q' to quit")
     leave_program=input()
  if number ==3:
     print ("[--------------]")
     print ("[     O   O    ]")
     print ("[       O      ]")
     print ("[              ]")
     print ("[--------------]")
     print("Type 'q' to quit")
     leave_program=input()
  if number ==4:  
     print ("[--------------]")
     print ("[    O     O   ]")
     print ("[              ]")
     print ("[    O     O   ]")
     print ("[--------------]")
     print("Type 'q' to quit")
     leave_program=input()
  if number ==5:  
     print ("[--------------]")
     print ("[    O     O   ]")
     print ("[       O      ]")
     print ("[    O     O   ]")
     print ("[--------------]")
     print("Type 'q' to quit")
     leave_program=input()
  if number ==6: 
     print ("[--------------]")
     print ("[    O     O   ]")
     print ("[    O     O   ]")
     print ("[    O     O   ]")
     print ("[--------------]")
     print("Type 'q' to quit") 
     leave_program=input()
      
