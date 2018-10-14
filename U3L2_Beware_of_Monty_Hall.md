# 1. Beware of Monty Hall
  When making this problem simple, it is to choose one of three or two of three. Everytime I choose one of the three doors, Monty opens another door which has always a goat. The probability that the door that I chose has a car is 1/3, and the probability that one of the remaining doors has a car is 2/3. Since Monty always notify which door has a goat among the remaining doors, changing my first choice to the other door is 2/3 to have a car in it and is always better than not to change. Again, this problem can be simplified as choosing one door or two doors at once because Monty always opens the wrong door for us, and it is always better to choose opening two doors at once. 
  
  We also can apply Bayes' probability to this problem. Let's assume the situation that I choose the door A, and change my choice after Monty opened the one of remaining doors. The probaility that Monty opened the door B and the car is behind the door C could be expressed as the following fomula : 
  
  p(C|OB)=p(OB|C)xp(OB)%p(C) 
  
  (p(C) means the chance that the car is behind the door C, and p(OB) means the chance that Monty opens the door B)     
  
  p(OB|C) would be 1 because in the situation that I already chose the door A, and if the car is behind the door C, Monty has no other choice than opening door B. p(OB) would be 1/2 because I chose the door A, and Monty has to open the door B or the door C. p(C) is 1/3. Therefore, p(C|OB)=1*1/2%1/3=2/3. Using the identical approach, p(B|OC) also would be 2/3.  
