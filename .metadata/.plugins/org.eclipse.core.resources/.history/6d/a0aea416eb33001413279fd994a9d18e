'''
Created on 28/08/2014

This class will contain a player class that allows 

@author: Corey McDougall
'''
class Player():
    def __init__(self, pName):
        self.name = pName
        self.score = list()
    
    def addBowl(self, bowlIn):
        bowl = int
        if ((bowlIn >= 0 and bowlIn <= 9) or bowlIn == "/" or bowlIn == "X"):
            bowl = bowlIn
        if (self.score[-1] == "/"):
            self.score[-1] = bowl
            self.score.append(bowl)
        elif (self.score[-1] == "X"):
            self.score.append(bowl)
        elif (self.score[-2] == "X"):
            self.score[-2] = self.score[-1] + bowl
            self.score.append(bowl)
        else:
            self.score.append(bowl)
    
    def getSCore(self):
        for i in range(0, len(self.score)):
            if (self.score[i] == "/" or self.score[i] == "X"):
                X = int
                break
            else:
                X += self.score[i]
        return(X)
