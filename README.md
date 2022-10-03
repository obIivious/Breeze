# Breeze
Basic scripting language

!! See wiki for more info !!
https://github.com/ObliviousFuture/Breeze/wiki


Variables

-  var variable = "Hello World";
-  var variable = "Hello, "+"World";

Print

-  log[variable];

Open

-  run["C:\Windows\notepad.exe"];

Request

-  request["https://pastebin.com/raw/eT0iu9C8"];

Function

-  func function = (log["hello"], log["world"]);

Call Function

-  schedule[function, 1];

Save value

-  save["name", variable];

Load value

-  load["name"];

Input

-  input name = ">";

If statement

-  if x = y [function, delay];

Delay

-  delay[second]

Random

-  var variable = random[1, 5];

Clear

-  clear[];

For range

-  for 3, do[function, 1];

Lists

-  list myList = "hello", "world";
-  log[myList{0}];
