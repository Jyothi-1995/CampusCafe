What did you predict for Warmup.java, and what did it actually print? Explain the lines that surprised you.
my prediction was:
 7 5.0 ?
 two

Type casting from int to byte was unknown, Also in switch block missing Break;  statment made both the case 2 and 3 print on console.

********************
What is the difference between the static variable totalProducts and the instance variable name?
static variable totalProducts is shared across all the objects of Products class and gets incremented whenever a new product gets created using any of the constructers. Instance variable name is specific to the object ( product ) created and is not shared with other products.

*******************
What does the copy constructor do, and why does changing p2.name not change p1.name?
copy constructer creates a new object by copying a already existing object and its parameters. Changing p2.name doesnt not change p1.name since they p1 and p2 are two different objects.

******************
Why does Java force you to write (int) average when converting a double to an int, and what happens to the decimal part?
Java requires (int) as part of Type Casting because converting a double to an int can lose information. The decimal part is discarded and keeps the whole number portion.

******************
