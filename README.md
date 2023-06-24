# Average_Interger

def compute_average(N):
    total = sum(range(1, N+1))
    average = total / N


N = int(input("Enter an interger N greater than 1: "))
if N > 1:
    avg = compute_average(N)
    print("The average of all intergers from 1 to", N, "is", avg)
else:
    print("Error: N must be greater than 1.")
