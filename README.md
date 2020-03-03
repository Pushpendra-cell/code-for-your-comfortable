# solution for week 4 quiz assignment for python with DSA
Week 4 Quiz
The due date for submitting this assignment has passed.Due on 2020-02-26, 23:59 IST.
Score: 10/10=100%

Assignment submitted on 2020-02-25, 23:15 IST
All questions carry equal weightage. All Python code is assumed to be executed using Python3. You may submit as many times as you like within the deadline. Your final submission will be graded.
Note:

If the question asks about a value of type string, remember to enclose your answer in single or double quotes.
If the question asks about a value of type list, remember to enclose your answer in square brackets and use commas to separate list items.
Consider the following Python function.

def mystery(l,v):
  if len(l) == 0:
    return (v)
  else:
    return (mystery(l[:-1],l[-1]+v))
What does mystery([22,14,19,65,82,55],1) return?

258
Yes, the answer is correct.
Score: 2.5
Accepted Answers:
(Type: Regex Match) \s*258\s*
2.5 points
What is the value of triples after the following assignment?
triples = [ (x,y,z) for x in range(2,4) for y in range(2,5) for z in range(5,7) if 2*x*y > 3*z ]
[(2,4,5),(3,3,5),(3,4,5),(3,4,6)]
Yes, the answer is correct.
Score: 2.5
Accepted Answers:
(Type: Regex Match) \s*\[\s*\(\s*2\s*,\s*4\s*,\s*5\s*\)\s*,\s*\(\s*3\s*,\s*3\s*,\s*5\s*\)\s*,\s*\(\s*3\s*,\s*4\s*,\s*5\s*\)\s*,\s*\(\s*3\s*,\s*4\s*,\s*6\s*\)\s*\]\s*
2.5 points
2.5 points
Consider the following dictionary.
runs = {"Test":{"Rahul":[90,14,35],"Kohli":[3,103,73,42],"Pujara":[53,15,133,8]},"ODI":{"Sharma":[37,99],"Kohli":[63,47]}}
Which of the following statements does not generate an error?
 runs["ODI"]["Rahul"].append([74])
 runs["ODI"]["Rahul"].extend([74])
 runs["ODI"]["Rahul"][0]=74
 runs["ODI"]["Rahul"]=[74]
Yes, the answer is correct.
Score: 2.5
Feedback:
runs["ODI"]["Rahul"] creates a new key, so one can only assign it a fresh value, not access parts of the value or append to or extend the value.
Accepted Answers:
runs["ODI"]["Rahul"]=[74]
2.5 points
Assume that actor has been initialized as an empty dictionary:
actor = {}
Which of the following generates an error?
 actor["Star Wars"] = ["Rey","Ridley"]
 actor["Star Wars, Rey"] = "Ridley"
 actor[["Star Wars", "Rey"]] = "Ridley"
 actor[("Star Wars", "Rey")] = "Ridley"
Yes, the answer is correct.
Score: 2.5
Feedback:
Dictionary keys mus be immutable values.
Accepted Answers:
actor[["Star Wars", "Rey"]] = "Ridley"
