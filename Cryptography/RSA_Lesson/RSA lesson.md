## RSA lesson (200 points)

That just a simple RSA solving question

regarding the question, we got:

p = 67
q = 91
e = 65537
M = 5201314
Flag format: EECTF{ value of C }

Solution:

p * q = 6097 = N

e = 65537

M = 5201314

C = M^e mod N = 2575

so, the flag is : EECTF{2575}

