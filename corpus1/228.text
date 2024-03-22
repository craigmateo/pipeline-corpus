import pandas as pd
import glob

total=0

txt_files = glob.glob("*.txt")
for filename in txt_files:
	with open(filename, "r", encoding="utf-8") as f:
		x = f.readlines()
		text = []
		for line in x:
			text.append(line)
		alltext = " ".join(text)
		words = alltext.split(" ")
		total+=len(words)
print("wordcount: "+str(total/1000000)+ " million")