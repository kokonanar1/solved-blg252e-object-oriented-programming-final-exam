Download Link: https://assignmentchef.com/product/solved-blg252e-object-oriented-programming-final-exam
<br>






<strong>Question #1 </strong>

Design and develop a program for a war game.  Create a class for warlords who has two integer attributes showing how powerful they are in the war arena, such as <strong>power</strong> and <strong>magic</strong>. When two warlords have compared, the sum of their power and magic shows the more powerful one. No warlord can have nonpositive magic or negative power. If a warlord object initialized with non-positive magic or negative power, then the program should interrupt/prevent the creation of such an object and warn the user in these exceptional cases: “<strong>A warlord cannot be a non-magic wielder!</strong>”, “<strong>A warlord cannot have negative power!</strong>”

In the main function, you should put the given warlords in a container and sort them in descending order. Notice that the comparison function must be available for all sorts of types. You can use STL vector for the container.  Use the warlord’s <strong>Print</strong> function to print the magic and power of all warlords after they are sorted.

Download the skeleton code <strong>question1_skeleton.cpp</strong> from Ninova, fill in necessary parts to ensure the requirements listed above. Then, upload your program as <strong>question1.cpp</strong> to the Ninova system. You shouldn’t remove or change the given codes in the <strong>question1_skeleton.cpp</strong> file, but you should add your codes to appropriate locations.

Attention: You can use your course slides. STL is <strong>allowed only for the container, iterator, and algorithm.</strong>

<strong>Getting help</strong> from any other person, or from the internet is <strong>not allowed</strong>, <strong>and will be punished.</strong>

When you fill the given code as expected, you should get the following sample output:




<strong>Output: </strong>

Unsorted Warlords

Power: 1 Magic: 1

Power: 2 Magic: 2

Power: 2 Magic: 1




Sorted Warlords

Power: 2 Magic: 2

Power: 2 Magic: 1

Power: 1 Magic: 1

A warlord cannot be a non-magic wielder!