# highest-digits
a="1-10-2024"
b=""
for i in a:
    if i.isdigit():
        b=b+i
    else:
        b=b+","
print(b)
print(b.split(","))
print(max(b.split(",")))
