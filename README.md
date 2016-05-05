# statresult

1.txt:english terms with length 1  
else_words.txt.bak:terms with non-eng,non-jp char  
else_words.txt:edited manually  
onlyonce.txt:terms appeared only once  
gen.txt:gen like terms  
gen2.txt:gen like terms with length > 4  
stopword2.txt:terms apeared in almost every doc  
stopword3.txt:old version  
stopword4.txt:1.txt || else_words.txt || onlyonce.txt || gen2.txt  
wordslist.txt:stopword2.txt used  
wordslist_dsw.txt.bak:stopword3.txt used  
wordslist_dsw.txt:stopword4.txt used
  
---------------------------------------------------
\In Data  
NTCIR.txt  
NTCIR_dsw.txt:stopword4.txt used  
NTCIR_dsw.txt.bak:stopword3.txt used  
NTCIR_dsw.data:wordslist_dsw.txt used
NTCIR.dat:wordslist_dsw.txt.bak used(unusable) 
fqterm.txt.bak:NTCIR.dat used(min-supp = 10000)
fqterm.txt:

