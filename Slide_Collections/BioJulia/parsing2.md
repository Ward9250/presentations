---
name: parsing2
slide_author: Ben J. Ward
---
# Parsers can be a pain!

## So why can you parse ASCII pizzas with FASTA parsers?

```
» seqtk seq -r pizza.txt


>  | "         `.'  "   //      .'  :  "      '         ~  //     `"""   *|  |
,   . *    @ "@    .@.@    )Q(       .   /     ,  )O(   "   ,     ''---..__         .   .   "  ; ,@'.  ~  .@.@ .    ~  ""--- /     , "  _    '''--..,__                  '   .  .    @   .@    *  .   "      ..___/    '. ''---..__          '''--@..@         |  '  \\ ,   .--.   "     ~    '.@    *        __          ''--...__   "  @  '        |  |   \\ " .        "--@    * .@',_'   ,        '"'--..,__ """@   ~      |  |        |  | ~  \\    ))(   .    ' "   '.   '  , '"--..__    ~    ',    .'  ||  , |  |        |  |       '   _  "  .--.      .-"",   __     " )0(    "  ___| |__  ||   *|  |        |  |  )G(     *           @  ~        )@( '...@  _  ,      ~ .-.    ', ~  |  |        |  | "    .    ~  //   )g(  "==== , ~    ,    '  ~   //        .  "       |  |

>,..--'''    .   *  ~   ||   *    ~      / "     *        , ~  `    ~  , (O)  '   .
'.-@                    ''"""""'@                  , @  _.-@                '--..___         ___..--@         /   _.-@  .@              '-.,_      ""--....--@"       _.@     / " .    .@  _.@           '-._     '"-.__   "  @  *  _..-@@   ,    /     // ,   .@  .@         '._     "-._ * )O(      \\     ,    _.,    /   . //    "   .@  .        ',    "-._ ~          *  , \\  )o(  "  /    / )G(  .  *        .  .@      ',   '._ *    '@ '  ~              *    /    /     .  '     )g( ,  @  .     /   '.      "  @', :  ,  ,__.   ~      ,/    /  ~   *  @ "@       ~  .  .@   ',   .  //      '.   '     :   :     "   /    /     "   ; ,@'. * -----  .@  @  /    .  //   )@(  .--,   ||  .-.         /    /,__.      @   .@   _____    @  . ,   ' " ./  *  _  .   "   ||       )O(  ~/    / :   :  j|  .--.   . ~    "   '  '.   '          "    *    . || "   ~  _   /    '   .-.   || "      "   )@(   , |  |
```

This particular parser is used 1615 times on GitHub.

Because formats are not standardized, parsers are often "non-validating" or vaguely defined.
