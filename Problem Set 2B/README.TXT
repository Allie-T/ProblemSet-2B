------------------------------------------------------------------------
This is the project README file. Here, you should describe your project.
Tell the reader (someone who does not know anything about this project)
all they need to know. The comments should usually include at least:
------------------------------------------------------------------------

PROJECT TITLE: Problem Set 2B
PURPOSE OF PROJECT: The Ordered Pair
VERSION or DATE: September 24th, 2023
HOW TO START THIS PROJECT:
AUTHORS: Alicia Tang
USER INSTRUCTIONS:

CONSIDER: How would you create an OrderedPair object with values (4.0, -5.0) using BlueJ?
    
    First right click on the OrderedPair class, and click on new OrderedPair. 
    Click the one with the formal parameters, and then input 4.0 for the x value 
    then -5.0 for the y value. When finished click on ok, and then a new object
    will be created and will show up in the bottom left corner.
    
CONSIDER: How could you do this with code instead? What happens if you print an OrderedPair 
          object to the console, the way you might print an int? What does this output mean?

    First make a new class, and then in the class type make a main string class. Next, 
    write a new OrderedPair within the main string, and give the x and y values within the parameters.
    Finally, system out print the new variable. 
    It'll look like this:
    
    public class OrderedPairDriver{
        public static void main (String[] args) {
            OrderedPair p = new OrderedPair(4.0, -5.0);
            System.out.println(p);
        }
    }
    
    However without the behavior functions when you print it out it'll look like this:
    OrderedPair@3679908
    
    The OrderedPair is the name, and following it is some binary number code.
    
CONSIDER: Now what happens if you print an OrderedPair object to the console? What changed?

    After writing out the the behaviour functions it will now print: (4.0, -5.0) like we wanted.
    
    
