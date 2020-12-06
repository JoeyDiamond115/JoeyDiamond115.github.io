# Joey Diamond's Intro to Programming Portfolio

## Adventure Game

**Description:** A text-based adventure game where the player explores the World's Fair of 1893. It shows off object oriented programmings' fundamental principles of inheritence, encapsulation, and polymorphism. 

![AdventureGame](https://user-images.githubusercontent.com/74879325/100317950-d45c3a00-2f82-11eb-95ef-dff669adb3b9.png)

**Additional Information (Technical Details):** The "choose your own adventure" nature of the game allows the player to experience different events with each play through. They can come across new foods first introduced at the fair (Juicy Fruit gum, Cracker Jack Popcorn, Aunt Jemimas Syrup), different exhibits that were presented (Cold Storage Building, Electrical Building, the Ferris Wheel), and recognizable people who attended the magnificent event (Nikola Tesla, Milton Hershey, HH Holmes). 

## Study Application

**Description:** An application that helps users study programming based vocabulary words. This program is unique in that it uses the "using System.IO" derective to read in the terms and their definitions from an external file. 

![Study App](https://user-images.githubusercontent.com/74879325/100318790-38333280-2f84-11eb-95be-c6662301f2dd.png)

**Additional Information (Problem Solving):** Using an external file to read in information was overwhelming at first. I started out only having one external file with both the definitions and term names, but I didn't know how to get a single definition or name into my program. I ended up using this for the review screen and created two more external fles (one with names and one with corresponding definitions) in order to properly call them into my program. This fixed my issue. 

## Explorable Areas

**Description:** A command line application where the player can explore different areas and find/collect items specific to those areas.

![Explorable Areas](https://user-images.githubusercontent.com/74879325/100320745-446cbf00-2f87-11eb-912c-d272aaf6eb98.png)

**Additional Information (Technical Details):** Once a player chooses an area, they will be gitfted with two items. Once that is specific to that area, and another that is randomized from a different list of items. The player can then choose whether or not they wish to take said item. Some items even give the player a chance to explore new areas, as some places require the player to have a specific item to enter.

## Underwater Creatures

**Description:** An application that displays different underwater creatures to a user and allows them to learn more about the creatures. This application is heavily focused on using the object oriented programming principle of inheritence.

![Underwater Creatures](https://user-images.githubusercontent.com/74879325/100321859-f789e800-2f88-11eb-858c-0e7b4cc0828c.png)

**Additional Information (Problem Solving):** When trying to learn how to use inheritence in C#, it was crucial that my group called on the base class of the sub class and overloaded its constructor with the same elements used in the base class. This is something we soon realized, which gave us success in creating numerous sub "creature" classes of the base "Being" class. 

## Adopt-An-Insect

**Description:** This is an application where the user gets to customize its own insect. They get to choose which insect, give it a name, and then select what color it'll be.

![AdoptAnInsect](https://user-images.githubusercontent.com/74879325/100323047-c4e0ef00-2f8a-11eb-9242-d3ad5f4d04f3.png)

**Additional Information (Technical Details):** Having been my first ever coded project for the class, this application is pretty bare. But with only having simple console commands like "Console.ReadLine," "Console.WriteLine," and "Console.ReadKey," the purpose of the application is clear and easy to understand.

## Shift Cipher

**Description:** An application where a secret agent is given the option to use a substitution cipher or Caesar cipher to encrypt or decrypt a message of their choosing.

![CipherApp1](https://user-images.githubusercontent.com/74879325/100323991-30778c00-2f8c-11eb-90fa-da422de2feee.png)
![CipherApp2](https://user-images.githubusercontent.com/74879325/100324045-44bb8900-2f8c-11eb-834c-691d7e88b557.png)

**Additional Information (Problem Solving):** It was difficult trying to fugre out how to realign the aplhabet in a Caesar cipher if the encrypted/decyrpted message went past the 1st or 26th value of "A" or "Z," but then I realized that I could use an if statement to change the value of the alphabet index if this was to occur. This fixed the problem and made the cipher work properly.

## Trivia Game

**Description:** An application where a user can test their knowledge of Greeak Heros/Gods in trivia fashion.

![Trivia Game](https://user-images.githubusercontent.com/74879325/100325338-1474ea00-2f8e-11eb-8cf7-966832f5dc82.png)

**Additional Information (Technical Details):** This was the first application I created that took advantage of changing the backgorund color for thw window screen, alongside utilizing a random element within an array. Each hero/god that is presented is randomly chosen as the player continues. 

## Shift Cipher App (GUI Version)

**Description:** Similar to the normal Shift Cipher app, this application lets the player, a "secret agent" choose to use a substitution cipher or Caesar cipher to encrypt or decrypt a message of their choosing.

![AgentGUI1](https://user-images.githubusercontent.com/74879325/101279867-080d4000-378b-11eb-9812-e60da6e9bb4a.png)
Image of the application before anything has been pressed.
![AgentGUI2](https://user-images.githubusercontent.com/74879325/101279883-2b37ef80-378b-11eb-8c6a-ff801aa216d5.png)
Image of the application after using the encrypted substitution cipher.
![AgentGUI3(Caesar)](https://user-images.githubusercontent.com/74879325/101279937-971a5800-378b-11eb-98a4-4ca39f1f5473.png)
Image of the application after using the encrypted Caesar cipher.
![AgentGUI4](https://user-images.githubusercontent.com/74879325/101279951-ad281880-378b-11eb-8137-73af631b86d3.png)
Image of some application code.

**Additional Information (Problem Solving):** While I was working on this program, I was very confused on how to access a XAML property in my C# code. After a while of tinkering, I found it helpful to scrap my additional classes entirely and focus on the two premade classes the program had started with. This helped me reference the player's input textbox, which allowed me to decode their message. 


Click [Here](https://github.com/JoeyDiamond115/JoeyDiamond115.github.io/edit/main/README.md) to see this page in GitHub.
