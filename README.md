# -
number = int(input(""))#隊伍數 res = 0#拿來計數  for i in range(number):#檢查每個隊伍是否合格     member = int(input(""))#輸入每隊人數     if member % 3 == 0 and member > 0:#若合格+1，否則不計數         res = res + 1 print(res)#輸出合格結果
