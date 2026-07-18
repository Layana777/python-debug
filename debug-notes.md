Debug Notes. 

reproduce: ran buggy.py,
 IndexError on line. 
 hypothesis: the loop goes one index too far.
 isolate: range(len+1) reaches index 4,
  but the list ends at 3\n4. test: printed i and saw it hit. 
  fix: removed + 1 from range\n