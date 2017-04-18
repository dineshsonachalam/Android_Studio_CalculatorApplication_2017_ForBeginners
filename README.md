# Developing Calucator Application using Android Studio

This tutorial is all about creating a calucator application using android studio for beginners.

## Getting Started
These instructions will get you clear understanding  of how to create an calcuator application using android studio. Little glance of java programming is necessary if you dont have any idea about OOP programming languages.



### Prerequisites

What things you need to install

Android Studio

### activity_main.xml 
It an user interface. It acts as a front end in android developement.

Things to do:
* First of all we need to 2 textfield to hold input value that is the number.
* Then we should have one textview to display the result.
* We need 4 operators to perform addition,subtraction,multiplication,division.

Changes to be done in activity_main.xml
* Change the RelativeLayout to LinearLayout.
* Add android:orientation="vertical" for vertiall alignment of the widgets.
* Have two textfield having the dataformat as numbers.
* Have one textview to display results.
* Buttons for sub,add,mul,div.
* Set id for each of the above fields.

### MainActivity.java
It is backend of android development. Here we will perform all the computation here.


Things to be remembered
* First initialize set of TextView,EditText,Button,int,float.,etc. that you are going to be using in program.
* After intilization you need to perform code inside onCreate() function.
* findViewById -> denotes the set of id that you have given before in the xml widgets.
* getText() ->used to get the value from the inputTextField.
* setText() ->Used to display outcome of the result in the TextView.
* setOnClickListener -> These are the even listeners that is to perform events i.e, list of operations to performed if an event is triggered.




## Built With

* [Android Studio](https://developer.android.com/studio/index.html) - The android development framework



## Authors

* **Dinesh Sonachalam** - *Initial work* - [DineshSonachalam](https://github.com/dineshsonachalam)

## Screenshots

![Alt text](https://rawgit.com/dineshsonachalam/Android_Studio_CalculatorApplication_2017_ForBeginners/master/Screenshots/device-2017-04-19-004132.png "Optional Title")
![Alt text](https://rawgit.com/dineshsonachalam/Android_Studio_CalculatorApplication_2017_ForBeginners/master/Screenshots/device-2017-04-19-004240.png "Optional Title")
![Alt text](https://rawgit.com/dineshsonachalam/Android_Studio_CalculatorApplication_2017_ForBeginners/master/Screenshots/device-2017-04-19-004252.png "Optional Title")


