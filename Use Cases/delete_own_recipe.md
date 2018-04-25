[N|n][U|u][L|l][L|l] {return new Token(Token.NULL, yytext(), yyline+1, yycolumn+1);}

[0-9]+[\.][0-9]*[\^][0-9]+ { return new Token(Token.FRAC, yytext(), yyline+1, yycolumn+1);}

[(0-9|a-z|A-Z)]+ { return new Token(Token.ID, yytext(), yyline+1, yycolumn+1);}