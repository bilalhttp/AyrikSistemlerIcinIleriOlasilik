
# Kırmızı, Yeşil, Mavi, Sarı ve Beyaz renkli topların bulunduğu bir torbadan belirtilen sayı kadar aynı renkte top elde edebilmek için 
# en az kaç top çekilmesi gerektiğini bulan fonksiyon

def pigeOnHole(redBallCount, greenBallCount, blueBallCount, yellowBallCount, whiteBallCount, sameBallCount):
  aboveSameBallCount = 0
  
  if(sameBallCount > redBallCount and sameBallCount > yellowBallCount and sameBallCount > greenBallCount and sameBallCount > whiteBallCount and sameBallCount > blueBallCount):
    return 0;
    
  else:
  
    if(sameBallCount > redBallCount):
      aboveSameBallCount += redBallCount
    else:
      aboveSameBallCount += sameBallCount - 1
   
    if(sameBallCount > yellowBallCount):
      aboveSameBallCount += yellowBallCount
    else:
      aboveSameBallCount += sameBallCount - 1
   
    if(sameBallCount > greenBallCount):
      aboveSameBallCount += greenBallCount
    else:
      aboveSameBallCount += sameBallCount - 1
    
    if(sameBallCount > whiteBallCount):
      aboveSameBallCount += whiteBallCount
    else:
      aboveSameBallCount += sameBallCount - 1

    if(sameBallCount > blueBallCount):
      aboveSameBallCount += blueBallCount
    else:
      aboveSameBallCount += sameBallCount - 1

    aboveSameBallCount += 1
   
    return aboveSameBallCount;
