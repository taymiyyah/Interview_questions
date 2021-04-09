# Interview_questions-oop-java-kotlin-

**Good to start with (open questions)**

What is your Favorite Language, why?

What is your IDES Language, why?

What is your idea of a good work day?

Describe a difficult task you had at work and how you finished it.

What makes code a clean code?

**Basics**

**General**

Explain public static void main(String args[]) in Java ?

What is the difference between abstract classes and interfaces?

 Can you create an instance of an abstract class /Interface?

What is a constructor?

What is the difference between a local variable (in method) and an instance variable (in class)?

Local : no defaults + recreate each call

Class : create for each instance (objects), gets defaults (null , or 0,&quot;&quot;..)

Differentiate between this() and super() in Java.

Name all of the data types?

What is different between ArrayList &amp; Array? Array is fixed size

**OOP**

What is inheritance

What is a superclass?

What is a subclass?

What is final/readOnly/val keyword ?

How to protect your class from inheritance?

How to protect your method form override?

How to protect your variable form changes?

What is the default value of the local variables? Must be initialized (ides will tell you)

What is a package/namespace, why they used?

What is the different between static method and normal method?

What is the different between static variable and normal variable?

How can we call the base method without creating an instance? By static

How to use static method/variable

What is method overloading?

What is method overriding?

What is method overloading?

What is method overriding?

**Exception**

What is the difference between an error and an exception?

What is exception?

How to handle exception?

When catch is called?

When finally is called?

If an EXCPTION fire in try block, does the execution continue?

What is NullPointerException?

When ArithmeticException is thrown?

What is throw does?

**More**

What is the base class of all classes &quot;base class&quot; c# /java /kotlin

Kolitn : they called it Any

What is the Difference between == and Equals()

== Memory reference , Equals() object content

What is Garbage Collection (GC)?

What is JSON?

What is an enumeration?

What the methods of an object class ? toString , hashcode,equals

What are visibility modifiers?

What are the different types of arguments(ref/value)?

What is the singleton , why , and how?

What is java/c# file extension?

**Intermedium**

What is OOP principles?

Inheritance :

Encapsulation: variable control should be done by the class, setter and getter will prevent the user from change the value as he want

Polymorphism: Same Type Difference behavior

Data Abstraction :

Data abstraction is a very important feature of OOPs that allows displaying only the important information and hiding the implementation details.

What is the Difference between String, String Builder?

IF class has three static variable, when these variable is pushed to memory and when cleanup?

## Can you declare an overridden method to be static if the original method is not static?

Static methods cannot be overridden

What is different between HashMap (dictionary)&amp; HashSet ?

What are the functions of hashCode() method?

Why do I need to override the equals and hashCode methods?

What is the Linked List VS array list?

Linked List use pointers and reference to make a sequence , it makes new node to create new object

array list make new array to increase the size

What is mutable/immutable variables?

Asynchronous VS synchronous code?

What is Design pattern?

Explain the difference between the inner class and the nested static class **?**

Inner class: hold a reference to outer class so it can access outer variables

Nested static class : does not hold a reference to outer class so it cannot access outer variables

What is boxing type? Wrapper class in java (Integers , Long …)

Doesn&#39;t support (c#/java) multiple inheritance. Why?

Does Java allow Default Arguments? No , but you get the same behavior by overloading methods

What is Memory leaks?

Explains Factory ,Builder design patterns

What is utc date?

Why they recommend to close db connections?

Why store procedure faster than connections?

**APIS**

What is the REST VS soap?

What is the REST action ?

What is the REST codes?

What is a token?

What are the advantages of JSON over XML?

What is Serialization?

**GIT**

Explain push/commit/pull/PR

What is git conflict?

**Advance**

What is Solid principle?

 What is operator overloading?

What is Generics , how it different from object type ?

What is Type erasure?

What is java Upper/lower bound?

When to use abstract class? Define Skelton of subclass

Explain GIT branching strategy?

How to fix production code?

When to use comments? to describe why you do tis not how

How jvm works?

What is new for java8?

Interfaces can define methods body

Lamdas

**GIT**

What is the difference between fetch/pull?

What is the difference between soft/hard/mixed?

What is the different between, merge, rebase, squash, fast-forward?

**Kotlin**

**Basic**

What is new for kotlin does not java do? ,  Why you should switch to Kotlin from Java?

. What is the difference between the variable declaration with var and val?

What is a data class in Kotlin?

Can we use primitive types such as int, double, float in Kotlin?

What are visibility modifiers in Kotlin? What&#39;s the default visibility modifier?

What are companion objects in Kotlin?

does Kotlin have the static keyword? How to create static methods in Kotlin?

What is an property?

What is the default return type in koltin , and what is the equivalent in java?

What is the equivalent java when statement in kotlin?

**Intermedium**

What is the default arguments in kotlin?

How to call top\_level (fun,variable) form java?

How to create Singleton classes?

What are the named arguments used for?

What are Varargs in Kotlin?

How many varargs might be placed in a parameter list?

What is a spread operator? It is used to pass an array as the vararg parameter.

What does &#39;Null Safety&#39; mean in Kotlin?

What is the difference between safe calls(?.) and null check(!!)?

Do we have a ternary operator in Kotlin just like java?

What is Elvis operator in Kotlin(?:) ?

Is there any difference between == operator and === operator?

What is the difference between lateinit and lazy in Kotlin?

What is the equivalent of Java static methods in Kotlin?

. What are init blocks in Kotlin?

What are the types of constructors in Kotlin?

Is there any relationship between primary and secondary constructors? : Yes, when using a secondary constructor, you need to call the primary constructor explicitly.

What are Coroutines in Kotlin?

What is suspend function in Kotlin Coroutines?

What is the difference between Launch and Async in Kotlin Coroutines?

What is the open keyword in Kotlin used for?

What are extension functions in Kotlin?

What is as throws?

What is common operation on collection ? filer, maps , any,…

**Advance**

Is koltic static/dyamic types?

When backing field for property is not generated?

What is the difference between the variable declaration with val and const?

 How does Kotlin work on Android?

What is the use of @JvmStatic, @JvmOverloads,JvmName and @JvmFiled in Kotlin?

What are Higher-Order functions in Kotlin?

What is an infix function in Kotlin?

What are the benefits of using a Sealed Class over Enum?

What is out , in keyword?

What is lambda labels is used?

What is inline fun,class?

Does kotlin has checked exception ?

What is safe cast (as?) ?

What is lambda sytax in kotlin?

What is lambda it?

What is kotlin sequnces ?

How to define custome getter , setter?

When you decelre class inside other will be (static,inner), why ?

What is the different between variable ein consttour or body for data class?

What is the different between Let, run ,wirth, apply , also

What is platform type?

What is Nothing type?

What is default val/var for function parameter ?

What is the different between constructor parameter with/without val)

Android

**Basics**

What is Application class?

What is AndroidManifest.xml?

What is the project structure of an Android Application?

How the xml file is linked with java code?

how to ask permission ?

how data is send between activities?

Difference between View.GONE and View.INVISIBLE?

What is Activity and its?

What is the difference between onCreate() and onStart()

What is Activity / Fragment LifeCycle ?

How to Translate in Android?

**Intermedium**

**Why**  **AsyncTask is bad , what the other option?**

How to do heavy operation?

Why android app will crash if you do task in main thread?

What is thread?

What is coroutine ?

Tell about Constraint Layout over other layouts ?

What is the difference between ListView and RecyclerView?

How does RecyclerView work internally?

What is Fragment and its.

When should you use a Fragment rather than an Activity?

When you have some UI components to be used across various activities

When multiple view can be displayed side by side just like viewPager

What is Activity and Fragment ?

Intents and Broadcasting

How to persist data in an Android app?

What is commit() and apply() in SharedPreferences?

What is roomdb

What is Android Jetpack and why to use this?

What is LiveData in Android?

What is view model?

When should you use a Fragment rather than an Activity?

What is View in Android?

What is Android Data Binding?

**Advance**

What is the difference between adding/replacing fragment in backstack

How would you communicate between two Fragments?

What is the difference between Serializable and Parcelable? Which is the best approach in Android?

Differentiate Activities from Services?

What is a JobScheduler?

What DI frameworks do you use?

What is the function of an IntentFilter?

What is Intent?

What is an Implicit Intent?

What is an Explicit Intent?

What is onSavedInstanceState() and onRestoreInstanceState() in activity?

How you can keep data after configuration change

Tell all the Android application components.

What are &quot;launch modes&quot;?

What is Context? How is it used?

What is Memory leaks ?

Where firebase messages is received?

Can you a create custom view? How

What is the ViewHolder pattern? Why should we use it?

Service vs IntentService

What is ANR? How can the ANR be prevente

Why should you avoid to run non-ui code on the main thread?

What is the difference between setValue and postValue in LiveData?

What are Android Architecture Components?

Explain OkHttp Interceptor

What gradle does?

What progarud does?

Android Unit Testing

What is Espresso?

What is Robolectric?

What are the disadvantages of using Robolectric?

What is UI-Automator?

Explain unit test.

Explain instrumented test.

Have you done unit testing or automatic testing?

Why Mockito is used?

Describe JUnit test.

Describe code coverage.
