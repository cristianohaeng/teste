
while 1:
    n=int(input('digite um valor  '))
    def fatorial(n):
        if n<=1:
            return 1
        return n*fatorial(n-1)
    print (fatorial(n))
