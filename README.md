Nadia’s Extra Spicy Live-Coding Repository
My repository is publicly available at: https://github.com/nadialofaro 
I created this repository with the purpose of live-coding in mind. The recorded samples are short and can be repeated every cycle. I plan to use these samples which I recorded myself in my final project which will feature live-coding through MiniTidal. 

Samples:
•	Thump.wav (00:01)
•	apple_0.wav (00:02)
•	apple_1.wav (00:01)
•	apple_2.wav (00:02)
•	apple_3.wav (00:01)
•	chalk0.wav (00:02)
•	chalk1.wav (00:03)
•	harmonica0.wav (00:02)
•	harmonica1.wav (00:03)
•	harmonica2.wav (00:01)
•	oh.wav (00:01)
•	wa.wav (00:01)
•	wa_1.wav (00:01)
•	wa_2.wav (00:01)
•	wa_3.wav (00:01)
•	wa_4.wav (00:04)
•	wa_5.wav  (00:02)
•	well.wav  (00:01)
•	screech.wav (00:09)
•	cluck0.wav (00:01)
•	cluck1.wav (00:01)
•	tweet.wav (00:02)

The repo.json file in the repository communicates which n number and which sound bank each sample can be accessed from in Estuary.
Instructions:
My repository can be used through Estuary, which can be found at: https://estuary.mcmaster.ca/
In Solo Mode, type this command into the Estuary terminal:
!reslist "https://nadialofaro.github.io/nadia-samples/repo.json"

Now you will be able to hear my sound bank!
Here are some examples you can try:
________________________________
s “oh”
_________________________________
s “well”
___________________________________
stack[ 
s "thump*4",
slow 2$ s "tweet",
slow 2$ s "~cluck/2",
slow 2$ s "~~apples(3,2)"
]
________________________________________
stack[ 
s "chalk/10?",
slow 2$ s "tweet?",
 s "~harmon" # gain 0.7 # note "-30",
 s "~harmon:2" # gain 0.7 # note "-50",
s "~~well/4" # speed "-0.5"
]
¬¬¬¬¬¬¬¬¬¬¬¬¬¬¬¬¬___________________________________________
stack[ 
s "chalk/10?",
s "wa:3/3? wa?" # gain 1.2,
slow 2$ s "tweet?",
 s "~harmon" # gain 0.7 # note "-60",
 s "~harmon:2" # gain 0.7 # note "-50",
s "~~oh/16" 
]
