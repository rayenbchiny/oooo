FUNCTION palindrome(word:STRING;start,end:INTEGER) : BOOLEAN
VAR
 
    start =0
 end = word.length-1
BEGIN
WHILE (start <= end) DO
 IF (word[start] == word[end]) THEN
      
   RETURN TRUE
 ELSE
    RETURN FALSE
 ELSE 
   palindrome(word,start+1,end-1)
 END_IF 
 
 
