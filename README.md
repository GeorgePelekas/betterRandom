# betterRandom

import random
def GeiaSou(name):
    Message="Geia Sou "+name
    return Message
def sit(name):
    Message=GeiaSou(name)
    randomNumber=random.randint(1,1000)
    Message=Message+" your number is: "+str(randomNumber)
    return Message
print(sit("menios"))
