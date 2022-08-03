ALGORITHM Sentence
sentence_length, words_number, i, vowels:INTEGER;
phrase:STRING;
VAR
    sentence_length = 0 ;
    words_number = 0 ; 
    vowels = 0 ; 
BEGIN
read phrase ;
    FOR i FROM 0 TO sentence_length-1 STEP 1 DO
   
    var charachter = phrase.CHAR(i)
    IF (charachter==" ") THEN
        words_number = words_number + 1 ;
    ELSE_IF (charachter=="a" || charachter="e" || charachter="i" || charachter="o" || charachter="u" || charachter="y")
    vowels = vowels + 1 ;
    END_IF
    END_FOR
     sentence_length=i+1;
write ("the sentence length is"  sentence_length );
write ( "the number of words is"  words_number) ; 
write ( "the number of vowels is"  vowels) ; 
END