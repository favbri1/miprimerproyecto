t = int(input())
for _ in range(t):
    s = input().strip()  # cadena completa
    sub = input().strip()  # subcadena
    if sub in s:
        print("si")
    else:
        print("no")
