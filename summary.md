# Questions:
1. What is the knowledge point of the test? Where is the offical document to the knowledge point?
1. Why the test failed at first?
1. Why you corrected the test that way?
1. Do you have further questions on this knowledge point?

## StringTest

### should_be_immutable
1. To check if String is immutable and to learn use of Optional. 
    Documents: https://docs.oracle.com/javase/8/docs/api/java/util/Optional.html 
               https://javarevisited.blogspot.com/2013/07/java-string-tutorial-and-examples-beginners-programming.html
2. Not familiar with Optional class. 
3. Since original is immutable and not equals to modified string. Then I used optional to set 'false' 
4. How to use other Optional.class methods?

### all_modification_method_will_create_new_string
1. To check if spaces will not be trimmed. And to check if all new String will create a new obfject while modifying the original String without changing the original object. Same Doc as above.
2. Per normal point of view I thought spaces will be auto trimmed. 
3. Since original is not auto trimmed and not equals to modified string. Then I used optional to set 'false' 
4. Same as above.

### will_create_new_string_when_concat
1. To check if the copy of String will create new String and will not be affected if the original String is changed. Same Doc as above
2. No errors. 
3. Same as above answers.
4. None.

### should_taken_string_apart
1. To learn how to modify string to a new value using String methods
2. No errors.
3. Changed it that way to retain the Expected String. used trim to dynamically remove spaces before/ after the given String.
4. None.

### should_taken_string_apart_continued
1. Same as above
2. No errors. Default values are failed in just one look
3. The easiest way for me to get the "is" value is to split the sentence and get the word
4. None.

### should_break_string_into_words
1. To learn other String functions. Use of split
2. Same as above.
3. Because it's just a conversion of String to array and removing spaces and regex which is easily done by split function
4. None

### should_break_string_into_words_customized
1. Same as above
2. Same as above
3. Same as above
4. None

### should_create_ascii_art
1. To learn and use StringBuilder
2. Same as above
3. Because StringBuilder have a method to append strings. Code wise it's better to use append than to use "+" to concat strings when usin StringBuilder
4. None

### should_calculate_checksum_of_a_string
1. To learn the checksum of Strings 
2. Same as above.
3. Because checksum is per char value of a string. So to get the per char value of the sentence, I get the char value of the String and iterate it by adding to the result
4. None.

### should_convert_unicode_escape
1. To learn unicodes in String and how to escape unicodes.
2. Same as above
3. Because unicode in String literals are represented by small u and to return the correct value need to escape the unicode and add escape string "\" 
4. None

### should_reverse_a_string
1. To learn how to reverse a whole String
2. Same as above
3. Because there is a default method in StringBuilder class to reverse a string. 
4. None

### should_compare_string_with_different_cases
1. To learn the difference between equals() and equalsIgnoreCase()
2. Same as above
3. Because equals() checks the letter case during comparison while equalsIgnoreCase() doesn't
4. None

### should_format_string
1. To be able to learn String.format() or how to format string and different specifier of format(). Document: https://www.javatpoint.com/java-string-format
2. Same as above.
3. Just set the string directly with the specified args given 
4. None

