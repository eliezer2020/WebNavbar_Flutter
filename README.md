# web_navbar

package project for a responsive web navbar. updated for flutter 2
for flutter 1.x used package version 2

## Getting Started

Must be used inside an Scaffold, this widget is placed in the Appbar section.
You need yo override the Appbar widget with this one as the 
example:

```dart
appBar: WebNavbar(
        navColor: Colors.black,
        hamburgerColor: Colors.blue,
        pathImage: "assets/DC.png",
        myButtons: [btn1, btn2, btn3],
        textNavbar: Text(
          "Gerson Morales",
          style: TextStyle(color: Colors.white, fontSize: 22),
        ),
      ),
```
important: for flutter 2 use TextButton intead.     
btn represent FlatButtons, so myButtons is a List<FlatButton>
  
![alt text](https://github.com/eliezer2020/WebNavbar_Flutter/blob/main/webnavmar.png "Logo ")
 
