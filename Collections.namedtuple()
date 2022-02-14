# Enter your code here. Read input from STDIN. Print output to STDOUT
from collections import namedtuple
n, Student = input(), namedtuple('Student', raw_input())
print "%.2f" %( sum([float(stud.MARKS) for stud in [Student(*raw_input().split()) for _ in xrange(n)]]) / n )
