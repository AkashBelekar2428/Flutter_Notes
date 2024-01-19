# Flutter_Notes

Flutter

Its is codebase to create UI and logics.

Types of  widget :-
1. Stateless Widget :-  No need to change UI of the runtime. only navigation one vc to another vc.
2. Stateful Widget :-  Runtime changes of UI.

Scapffold :-
1. AppBar
2. Body


Native vs Cross Platform vs Hybrid :-
Native :- Android Studio, Xcode
Hybrid :- Visual Studio, Ionic
Cross Platform :- Flutter, React Native


Widget TREE :-
Use UI or Create

Conditional programming is use to change UI to specific platform or Actions

tutorial number : - 10  [WsCube Tech]

Material App :- For use of android UI
Cupertino App:- For use of iPhone UI

JIT:- 
Just In Time Compiler.

Container:-
1. it is a widget that combines common painting, positioning , and sizing of the child widgets.
2. It is also a class to store one or more widgets and position them on the screen according to our needs.
3. Generally, It is similar to as box for storing contents.
4. It allows many attributes to the user for decorating its child widget such as using margin, which separates the container with other contents.


Center Widget:-
1. It aligns its child widget to the center of the available space on the screen.

Text Widget:-
1. The Text widget displays a string of the text with single style.
2. The string might break across multiple lines or might all be displayed on the same line depending on the layout constraints.
3. properties- Text, fontSize, fontWeight, backgroundColors, color.

TextFiled Widget:-
use Controller to assign value.

Button Widget:-
1. Buttons are the graphical control element that provides
2. A user to trigger an event such as taking actions, making choices, searching things, and many more. They can be placed anywhere in our UI like dialogs, forms, cards, toolbars, etc.

Type of Button:-
1. TextButton(Flat Button)
2. Elevated Button(Raised Button)
3. Outlined Button

How to add image in app:-

Columns And Rows:-
columns:- children attributes

In Rows:-
1. mainAxisAlignment - Its used to horizontal line
2. crossAxisAlignment - Its used to vertical line

In Columns:-
1. mainAxisAlignment - Its used to vertical line
2. crossAxisAlignment - Its used to horizontal line


Inkwell Widget:-
1. Inkwell is the material widget in flutter.
2. It responds to the touch action as performed by the user.
3. Inkwell will respond when the user clicks it/Tap on it.
4. There are so many gestures like double-tap, long press, tap down, etc.
5. inkwell widget properties:- onTapPress(), onLongPress(), onDoubleTap().

ScrollView and Its types:-
1. Horizantal Scrollview
2. Vertical Scrollview

ListView And Its Components:-
1. Listview in flutter is a widget used to display items in a linear manner.
2. For example, list view is used in app like zomato and swiggy to display a list of restaurants.
3. Since it is a scrollable widget we can display multiple items on the same screen.
4. If the scroll direction is vertical the children will be arranged one after another from top to bottom.
5. When scroll direction is horizontal the children will be arranged from left to right and the scroll direction is vertical the children will be arranged from top to bottom.

ListView Types:-
1. ListView
2. ListView.builder - set dynamic data automatically (through API)
3. ListView.seperated -  seperate two items.

Expanded Widget:- 
expand the width and height.

Margin And Padding:- 
Margin:- Outside  the Container.
Padding:- Inside the Container.

List Tile in ListView:- 
Include properties is in leading, title, subtile, trailing.

Circle Avatar:- 
1. It is simply a circle in which we can add background color, background image, or just some text.
2. It usually represents a user with his image or with his initials.
3. Although we can make a similar widget from the ground up,
4. this widget comes in handy in the fast development of an application.

Thems And Style:-

Card Widget:- 
properties - elevation:, shadowColor:, shape:, color: ..

Text Input Widget:-
1. A TextField is an input element which holds the alphanumeric data, such as name, password, address, etc.
2. Enables the user to enter text information using a programmable code.

placeholder :- means hintText in flutter
image icon, icon button :- suffixIcon (left side of textfield)
image icon, icon button :- prefixIcon (right side of textfield)

Current Date And Time:- 

DateFormatter:-

Date Picker:- 

GridView:- 
1. GridView.count :- must taking a count (number)
2. GridView.extend
3. GridView.builder:- return dynamic data. (API)

CallBack Function:- 
Data Flow manage.

Splitting The App Into Widget:- 

Stack Widget:- 
1. A widget that positions its children relative to the edges of its box.
2. This class is useful if you want to overlap several children in a simple way,
3. for example having some text and an image, overlaid with a gradient and a button attached to the bottom.

Custom Widget:- 

SizeBox:- 
1. SizeBox.expand() :- Automatic set width and height. (parent widget maxWidth, maxHeight adapt automatically)
2. SizeBox.shrink() :-   no need to width and height . (parent widget minWidth, minHeight adapt automatically)
3. SizeBox.square() :- set dimension

IconWidget:-
Set Icons.
font_awesome_flutter Library to set third party Icons.

Switching VC to VC:- 
1. Navigator.push - Navigator.push(context, MaterialPageRoute(builder: (context) =>  (YourPageName),) );

SplashScreen:- 
Navigator.pushReplacement(context, MaterialPageRoute(builder: (context) => splashScreenPage(),));

Passing Data From One Screen To Another:-   Foo Animation {Animated Container} :- 

Share and Retrieve Data :- 
1. Shared Preference :- use async.await
2. Database Management
