def ButtonClick(id):
    global ActivePlayer
    global p1,p2
    global mov

    if(ActivePlayer ==1):
        SetLayout(id,"X")
        p1.append(id)
        mov +=1
        root.title("Tic Tac Toe : Player 2")
        ActivePlayer =2

    elif(ActivePlayer==2):
        SetLayout(id,"O")
        p2.append(id)
        mov +=1
        root.title("Tic Tac Toe : Player 1")
        ActivePlayer =1
    CheckWinner()
