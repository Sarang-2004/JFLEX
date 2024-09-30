# JFLEX
java -jar lib\jflex-1.6.1.jar Lexer.flex
javac -cp "lib\*;." Lexer.java
java -cp "lib\*;." Lexer input.txt
