 Homework-1 for CS582: Information Retrieval
 
 Name: Rahul Sai Samineni
 
 Dataset Used : Citiseer
 
Steps to run:
 1. Download the zip file and unzip it.
 2. Open the citiseer.ipynb in jupyter notebook.
 3. Run each cell to get output.
 
Implementation:

TASK-1:
    1. Parsed all the files in citeseer folder to one file called combination.txt.
    2. Next, using this combination file, changed the text into lower case.
    3. removed the punctuations of all words in combination folder.
    4. removed white spaces using split() to remove white spaces.
    5. Then added all the words to a file called a1.txt

TASK-2:
    1. Declared a variable count and read every word from a1 file.
    2. added if statement to check weather, the word is already present in count. if present, add +1 to it, or add word to list.
    3. using split() on a1.txt, and then using length() to find the total number of words.
    4. found number of unique words using length(count), where count is a dictionary of key,value pairs.
    5. In order to find top20 words, first sorted the count in decreasing order and found top20 words using Lambda function.
    6. Used keys from top20 words and comparing them with stoplist words to check if any match found and print them.
    7. finding minimum number of unique words accounting for 15% of the total number of words in the collection.

TASK-3:
    1. Integrate Porter Stemmer Object.
    2. Next, using this combination file, changed the text into lower case.
    3. removed the punctuations of all words in combination folder.
    4. removed white spaces using split() to remove white spaces.
    5. stemming is used on words to remove stop words.
    6. After stemming, added the words to a2.txt
    7. Declared a variable count and read every word from a1 file.
    8. added if statement to check weather, the word is already present in count. if present, add +1 to it, or add word to list.
    9. using split() on a1.txt, and then using length() to find the total number of words.
    10. found number of unique words using length(count), where count is a dictionary of key,value pairs.
    11. In order to find top20 words, first sorted the count in decreasing order and found top20 words using Lambda function.
    12. Used keys from top20 words and comparing them with stoplist words to check if any match found and print them.
    13. finding minimum number of unique words accounting for 15% of the total number of words in the collection.
    
RESULTS:

TASK-2:
    1. Total Number of Words : 476203
    2. Vocabulary size (number of unique words) : 19889
    3. Top 20 words : ['the', 'of', 'and', 'a', 'to', 'in', 'for', 'is', 'we', 'that', 'this', 'are', 'on', 'an', 'with', 'as', 'by', 'data', 'be', 'information']
    4. Stop-words in top 20 words : [the,of,and,a,to,in,for,is,we,that,this,on,are,an,with,as,by,be]
    5. minimum number of unique words accounting for 15% of the total number of words in the collection : 6
        the : 25662
        of : 18638
        and : 14131
        to : 11536
        web : 1432
        factor : 31

TASK-3:
    1. Total Number of Words : 294261
    2. Vocabulary size (number of unique words) : 13781
    3. Top 20 words : ['system', 'use', 'agent', 'base', 'data', 'inform', 'model', 'paper', 'queri', 'user', 'learn', '1', 'algorithm', 'problem', 'web', 'comput', 'applic', 'approach', 'present', 'databas']
    4. Stop-words in top 20 words : No Stop Words.
    5. minimum number of unique words accounting for 15% of the total number of words in the collection : 23
        system : 3741
        use : 3740
        data : 2691
        agent : 2688
        inform : 2398
        model : 2315
        paper : 2246
        queri : 1905
        user : 1756
        learn : 1740
        algorithm : 1584
        1 : 1552
        approach : 1544
        problem : 1543
        applic : 1522
        present : 1507
        base : 1486
        web : 1439
        databas : 1424
        comput : 1411
        method : 1223
        result : 1202
        provid : 1185
        address : 297
    
