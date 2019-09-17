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

