# RunLengthEncoding
<p> doing a run length encoding thing as a project whilst using another file or something <p/>

<p> this is a tiny bit confusing, but i can probably do it </p>

<p> !!!Pseudocode Below!!! </p>

function RLE()
  count = 1
  RLEcount = 0
  Pass1 = TRUE
  
  while count < 20
    symbolValue = randInt(0,2)
    if symbolValue == 0:
      symbolValue = R
    elif symbolValue == 1:
      symbolValue = G
    else:
      symbolValue == B

    if symbolValue == heldValue OR Pass1 = True
      RLEcount = RLEcount + 1
    else:
      RLEAns = RLEAns + parseSTR(RLEcount) + heldValue
      RLEcount = 0

    Pass1 = False
    RLESeq = RLESeq + symbolValue
    heldValue = symbolValue
    count = count + 1
  endwhile
  
  userAns = input("What is the RLE version  
