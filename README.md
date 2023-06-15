# RunLengthEncoding
<p> doing a run length encoding thing as a project whilst using another file or something <p/>

<p> this is a tiny bit confusing, but i can probably do it </p>

<p> !!!Pseudocode Below!!! </p>

function RLE()
  count = 1
  RLEcount = 0
  Pass1 = TRUE
  
  <p> while count < 20 </p>
    <p> symbolValue = randInt(0,2) </p>
    <p> if symbolValue == 0: </p>
      <p> symbolValue = R </p>
    <p> elif symbolValue == 1: </p>
      <p> symbolValue = G </p>
    <p> else: </p>
      <p> symbolValue == B </p>

    if symbolValue == heldValue OR Pass1 = True 
       RLEcount = RLEcount + 1 
    else: </p>
       RLEAns = RLEAns + parseSTR(RLEcount) + heldValue 
       RLEcount = 0 

    <p> Pass1 = False </p>
    <p> RLESeq = RLESeq + symbolValue </p>
    <p> heldValue = symbolValue </p>
    <p> count = count + 1 </p>
  <p> endwhile </p>
  
  <p> userAns = input("What is the RLE version of" RLESeq) </p>
  <p> if userAns = RLEAns: </p>
    <p> print("True") </p>
  <p> else: </p>
    <p> print("False") </p>
