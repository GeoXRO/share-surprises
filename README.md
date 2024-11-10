# share-surprises
This Java program is designed to manage and give surprises in different ways. It has several key components:

-Surprise Types: The program creates different types of surprises such as FortuneCookie, Candies, and MinionToy. Each type implements the ISurprise interface, and when "enjoyed," it prints out a specific message related to that surprise.

-Bag Types: The program supports different bag types for storing these surprises: BagFIFO (First In First Out), BagLIFO (Last In First Out), and BagRandom (picks a surprise randomly). You can put surprises in these bags, take them out, or check how many surprises are left.

-Giving Surprises with Passion: The GiveSurpriseAndApplause, GiveSurpriseAndHug, and GiveSurpriseAndSing classes are used to give surprises with passion. They each have a specific way of presenting a surprise — either with applause, a hug, or a song. These classes extend an abstract class and implement a method called giveWithPassion(), which displays a message based on the type of surprise.

-User Interaction: The program allows the user to interact with it through the command line. You can construct different surprises, add them to various bags, take them out, and give them to others in a passionate way.

What I learned from this program:

-Polymorphism: Different classes (e.g., FortuneCookie, Candies, MinionToy) implement the same interface (ISurprise), allowing me to treat them in a uniform way and execute the same method (enjoy()) without worrying about the specific type of surprise.

-Abstraction: The abstract class AbstractGiveSurprises allows me to create different ways of giving surprises with passion, while the method giveWithPassion() is implemented differently in each subclass (like applause, hug, or song).

-Bag Management: I learned how to manage different types of bags (FIFO, LIFO, Random), each with its own way of storing and retrieving surprises.

-Command-Driven Programming: I got a chance to work with user input processing, where I can define and execute specific commands like creating surprises, adding them to bags, checking bag sizes, and giving surprises.

-Extensibility: This structure is easily extensible. If I wanted to add new types of surprises, new ways of giving surprises, or new bag types, I could do so by adding new classes and ensuring they follow the same patterns.

The program illustrates how object-oriented principles like inheritance, polymorphism, and abstraction can be applied to manage and interact with collections of objects in a flexible and extensible way.
