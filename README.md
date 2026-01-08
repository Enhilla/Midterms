Loops
n = int(input())

for i in range(n):
    print(i * i)
Print Funcs
n = int(input())

for i in range(1, n + 1):
    print(i, end="")
Find a string
string = input()
sub = input()

count = 0
for i in range(len(string) - len(sub) + 1):
    if string[i:i+len(sub)] == sub:
        count += 1

print(count)
