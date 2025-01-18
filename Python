path = 'dr.txt'
with open(path, "r+") as f:
	for line in f.readline().splitlines():
		split_line = line.split(",")
		split_line = str(int(split_line) - 1)
	data.append(split_line)

with open(path, 'w') as file:
	for line in data:
		newnumbers = ','.join(line)
		file.write(newnumbers)```
