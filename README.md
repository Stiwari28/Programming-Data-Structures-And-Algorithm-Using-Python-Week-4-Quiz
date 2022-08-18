# Programming-Data-Structures-And-Algorithm-Using-Python-Week-4-Quiz
NPTEL Programming, Data Structures and Algorithm Using Python Week 4 Quiz answers.
answer in square brackets and use commas to separate list items.
1) Consider the following Python function.
def mystery(l):
    if l == []:
        return(l)
    else:
        return(mystery(l[1:])+l[:1])
What does mystery([22,14,19,65,82,55]) return?
[55, 82, 65, 19, 14, 22]

2) What is the value of pairs after the following assignment?
pairs = [ (x,y) for x in range(4,1,-1) for y in range(5,1,-1) if (x+y)%3 == 0 ]
[(4, 5), (4, 2), (3, 3), (2, 4)]

3) Consider the following dictionary.
wickets = {"Tests":{"Bumrah":[3,5,2,3],"Shami":[4,4,1,0],"Ashwin":[2,1,7,4]},"ODI":{"Bumrah":[2,0],"Shami":[1,2]}}
Which of the following statements does not generate an error?
wickets["ODI"]["Ashwin"] = [4,4]

4) Assume that hundreds has been initialized as an empty dictionary:
hundreds = {}
Which of the following generates an error?
hundreds[["Tendulkar","international"]] = 100
