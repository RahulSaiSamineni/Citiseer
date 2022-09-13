 # Homework-1 for CS582: Information Retrieval
 
---
Name: Rahul Sai Samineni
---
 
## Dataset Used : Citiseer
 
### Steps to run:
 - Download the zip file and unzip it.
 - Open the citiseer.ipynb in jupyter notebook.
 - Run each cell to get output.
 
### Implementation:

### TASK-1:
   - Parsed all the files in citeseer folder to one file called combination.txt.
   - Next, using this combination file, changed the text into lower case.
   - removed the punctuations of all words in combination folder.
   - removed white spaces using split() to remove white spaces.
   - Then added all the words to a file called a1.txt

### TASK-2:
   - Declared a variable count and read every word from a1 file.
   - added if statement to check weather, the word is already present in count. if present, add +1 to it, or add word to list.
   - using split() on a1.txt, and then using length() to find the total number of words.
   - found number of unique words using length(count), where count is a dictionary of key,value pairs.
   - In order to find top20 words, first sorted the count in decreasing order and found top20 words using Lambda function.
   - Used keys from top20 words and comparing them with stoplist words to check if any match found and print them.
   - finding minimum number of unique words accounting for 15% of the total number of words in the collection.

### TASK-3:
   - Integrate Porter Stemmer Object.
   - Next, using this combination file, changed the text into lower case.
   - Removed the punctuations of all words in combination folder.
   - Removed white spaces using split() to remove white spaces.
   - Stemming is used on words to remove stop words.
   - After stemming, added the words to a2.txt
   - Declared a variable count and read every word from a1 file.
   - Added if statement to check weather, the word is already present in count. if present, add +1 to it, or add word to list.
   - using split() on a1.txt, and then using length() to find the total number of words.
   - found number of unique words using length(count), where count is a dictionary of key,value pairs.
   - In order to find top20 words, first sorted the count in decreasing order and found top20 words using Lambda function.
   - Used keys from top20 words and comparing them with stoplist words to check if any match found and print them.
   - finding minimum number of unique words accounting for 15% of the total number of words in the collection.
    
## RESULTS:

### TASK-2:
```
Total Number of Words : 476203
Vocabulary size (number of unique words) : 19889
Top 20 words : ['the', 'of', 'and', 'a', 'to', 'in', 'for', 'is', 'we', 'that', 'this', 'are', 'on', 'an', 'with', 'as', 'by', 'data', 'be', 'information']
Stop-words in top 20 words : [the,of,and,a,to,in,for,is,we,that,this,on,are,an,with,as,by,be]
minimum number of unique words accounting for 15% of the total number of words in the collection : 6
   the    : 25662
   of     : 18638
   and    : 14131
   to     : 11536
   web    : 1432
   factor : 31
```
TASK-3:
```
Total Number of Words : 294261
Vocabulary size (number of unique words) : 13781
Top 20 words : ['system', 'use', 'agent', 'base', 'data', 'inform', 'model', 'paper', 'queri', 'user', 'learn', '1', 'algorithm', 'problem', 'web', 'comput', 'applic', 'approach', 'present', 'databas']
Stop-words in top 20 words : No Stop Words.
minimum number of unique words accounting for 15% of the total number of words in the collection : 23
   system    : 3741
   use       : 3740
   data      : 2691
   agent     : 2688
   inform    : 2398
   model     : 2315
   paper     : 2246
   queri     : 1905
   user      : 1756
   learn     : 1740
   algorithm : 1584
   1         : 1552
   approach  : 1544
   problem   : 1543
   applic    : 1522
   present   : 1507
   base      : 1486
   web       : 1439
   databas   : 1424
   comput    : 1411
   method    : 1223
   result    : 1202
   provid    : 1185
   address   : 297
```    
