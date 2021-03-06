The sample dataset contains 50 snippets extracted from chemical patents and their corresponding labels.
The 50 snippets indexed from 0000 to 0049. They are provided in BRAT standoff format. For each snippet, the raw text of the snippet is provided in a text file (\*.txt) and the corresponding labels of the snippet is provided in a different annotation file with the same file name but the annotation file extension (\*.ann). For more information about the brat standoff format, please checkout the website: https://brat.nlplab.org/standoff.html

The chemu_sample consists of two subfolders: "ner" (for task 1) and "ee" (for task 1 and task 2). Each subfolder consists of the raw texts of the 50 snippets (txt files), and their corresponding annotated files (ann files). In addition, the configuration files (annotation.conf, visual.conf, and tools.conf) are included in each subfolder, to facilitate visualizing the data using the brat tool. 

Due to some inconsistencies in how character entities were handled, we have corrected the sample and create a new version of the sample dataset: chemu_sample.v2.zip
Note that the file index numbers in this version of the sample differ from in the original version.

We have removed the labeled trigger words from the annotation files in "ner", since those words are not the target output in task 1. Please find the updated 3rd version of the sample dataset: chemu_sample.v3.zip
