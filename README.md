# Android-Developer-Guide

Java:

Could you please list object methods? 
What is the contract between equals and hashCode? 
What is the load factor and what is the default hashMap size? 
What is hash collision? How does HashMap calculate the index of the Bucket?
How HashMap solves collisions (In Java7 and in Java 8 and later) 
Does HashMap use equals and why? 
What data type HashMap stores in buckets? 
Why does the "space" operation of HashMap take O(n)? 
What is the time complexity of HashMap operations(see https://en.wikipedia.org/wiki/Hash_table). And why?(For every case) + Java 8 Complexity difference
TreeMap and difference between HashMap and TreeMap
What is the internal structure of ArrayList? 
How does ArrayList know the address of the element if it has only an index? (This is near the original question https://stackoverflow.com/questions/52047029/how-does-an-arraylist-retrieve-data-in-constant-time)
Which system call ArrayList uses to copy all elements during increasing? 
What is the complexity of get and add operations(to the beginning, middle and end of collection)? 
What are the benefits of ArrayList over LinkedList? 
What is the internal structure of LinkedList? 
How does LinkedList look in memory? 
What are the benefits of LinkedList? 
What is the internal structure of HashSet? 
I want to store elements in a set in the order of addition, what collection to choose? In which case you would need a set. Give an example. 
HashMap - Already covered TreeMap - internal structure, complexity, benefits Does HashMap thread safe? 
What is Hashtable? 
How to make HashMap thread safe? 
What is Collections util class? 
What is the difference between Collections.synchronizedMap(HashMap()) and ConcurrentHashMap? 
Common questions: If you would need to implement stack, which collection would you choose ArrayList or LinkedList? 
What is the inheritance hierarchy of ArrayList/LinkedList? 
What about maps? 
What is ConcurrentModificationException? How to avoid it? 
Why do collections in java have generics?
How to use wait/notify for synchronization 
How to start/stop java thread?
What is Runnable and how to use it? 
What is the difference between Runnable and Callable?
How to use Callable?
What is the difference between process and thread? 
Which types of references do you know in Java? (Hard/Soft/Weak/Phantom/AtomicReference) 
What is a synchronized keyword? What is a block of synchronization? 
What is the monitor of synchronization? 
What is the difference between synchronization of static and virtual functions?
Why do we need volatile keywords? And how does it work? 
Why are all of the primitives not volatile by default?
What is atomic operation?
What is CAS operation?
What is java.util.concurrent?
How CopyOnWriteArrayList works? Can it throw ConcurrentModificationException?
What are synchronizers? Which synchronizers do you know? (Lock, ReentrantLock, Semaphore, CountdownLatch, CyclicBarier, Exchanger) describe each of them
What are Executors, what are the benefits of executors?
What is Atomic types? What is the difference between volatile boolean and AtomicBoolean?
How does ConcurrentHashMap work?
Why are @Synchronized and @Volatile are annotations in Kotlin?
What happens-before? How volatile and synchronized connected with it?
What is the Java memory model?
I've created the thread and didn't have a hard reference on it, will it be collected by the GC? What are GC roots?
How does GC work? What GC algorithms do you know? What is Permanent/Old generation? Eden space? Survival and so on... Two objects have just cross-references, will they be collected by the GC?
Inner and Nested classes
Exceptions and try/catch/finally block
Iterator and Enumerator
OOP(Abstraction, Inheritance, Polymorphism, Encapsulation), Aggregation and Composition + UML diagrams it's a must! (You can find all of this topics in the first articles of book I sent to you)
Static and dynamic binding! (Runtime polymorphism)
Overloading and overriding!
Enums in Java
JDK, JVM and JRE!
String pool! and String.intern()! Also please read this urgent article: https://javaranch.com/campfire/StoryPassBy.jsp

Kotlin:

Initialization order in Kotlin (class fields, constructors, init blocks, what about inheritance)?
What are limitations of data classes?
What is Kotlin Sequence?
What do we have in Kotlin and don't have in Java? vice versa?
What is Structural Expressions in Koltin?
How to create volatile variables in Kotlin?
How do lambda functions work under the hood?
Reified in Kotlin?
How can we work with Kotlin collections? (Operators, operator functions like +) wait()/notify() in Kotlin
What is data class? Can it be extended?
What is the difference between object and class in Kotlin? Companion?
What is the benefit of extension functions?
What is the difference between sealed classes and enums? (How it works under the hood)
Why do we need @JvmOverloads (for Java/Kotlin stack)
Why are @Synchronized and @Volatile are annotations in Kotlin?
What is the difference between Unit and Nothing (+ Any type)?
What is infix / single line function / local functions / extension / inline (+ inline classes) What is the difference between IntArray and Array<Int>?
What is an inline keyword? Where can it be used? (inline functions) ( crossinline / noinline / reified)
What is spread operator (*)?
What are destructive declarations? Like (a, b) = ... 
Tell me about operator functions. How to use them?
What is delegate? What can be delegated?
Why do we need in and out modifiers? What is the difference between it and generic masks in Java?
What is typealias?
What is a tailrec modifier?
What is @Contract annotation? (+ contract blocks)
Can enum classes have abstract functions?
Difference between Sequences and Iterable?
How does Coroutine work under the hood? https://proandroiddev.com/how-do-coroutines-work-under-the-hood-803e6e9da8bb 

Android: 

What base components do you know and why they are base (pretty easy)
Activity/Fragment lifecycle.
How to start Activity. How to pass data to Activity/Fragment (Question about Bundle).
Can we put some data to the Fragment's constructor?
What is the TransactionTooLarge exception?
What is the main thread? Which restrictions do we have working with it?
Is it possible to change TextView's text from the working thread? How?
Handler/Looper/Message/MessageQueue. How does it work? HandlerThread. How to create a Handler?
I have two fragments attached to the same Activity. How to pass events from one fragment to another?(Remember as many ways as you know) What is the recommended way?
What is a retain fragment?
Can we create fragments without UI?
What is Activity stack, Fragment stack. How to move to the previous Activity/Fragment on back presses.
I want to download some big files and continue downloading even after system restart. What is the best option?
I want to ping the server from time to time. What can I use?
I want to send an SMS at 6 PM. How to implement it?
How to start Service? What is the difference between background/foreground/started and bound service?
I want to implement a music player app with notification in the app bar. Which type of service would you prefer?
What restrictions does Android have?(Services/Broadcasts/Geolocation/Networking...)
What are Notification channels?
What is the difference between Intent and PendingIntent?
What is JobScheduler? What is the difference between JobScheduler and WorkManager?
What is Doze mode? What is the maintenance window?
What is the difference between local and global broadcast receivers?
Types of permissions...
Can we run service in a separate process? How and why could we need it?
What is the difference between Dalvik and ART?
Which libraries do you use in your projects(image loading, networking, parsing)
What is the Lifecycle architecture component?
How LiveData works?
Which architectures do you know/have practical experience with?
Layouts?
onDraw and paint?
Dp vs Sp
RxJava:
You have to read about hot and cold streams and the differences between them.
Next understand the Observable and Flowable: http://reactivex.io/documentation/observable.html (Learn what is backpressure)
Next review operators: http://reactivex.io/documentation/operators.html (The most important are:
Create / Defer / Just / Interval
Map / FlatMap / Buffer
Debounce / Filter / First / Last / Take
CombineLatest / Merge / Zip
SubscribeOn / ObserveOn)
And finally review subjects: At least Publish, Behaviour and Replay
Also in future we have to cover:
Clean Architecture
Dependency Injection(Dagger, Hilt and Koin)
https://dagger.dev/dev-guide/ 
MVVM/MVP/MVC/VIPER/MVI
RxJava with popular tasks
Kotlin Coroutines: https://medium.com/@mmlilla90/kotlin-interview-questions-part-3-269bbc8525dd 
Android Architecture Components
SOLID
Popular Design Patterns + Design Patterns used in Android


Courses and Code Labs:
Course & Reference Links:
https://developer.android.com/courses/android-basics-kotlin/unit-1
Algorithmic tasks with Kotlin https://exercism.io/tracks/kotlin
If you still does not feel comfortable with Kotlin, try this course before codelabs: https://www.udacity.com/course/kotlin-bootcamp-for-programmers--ud9011
https://developer.android.com/jetpack/guide
https://github.com/android/architecture-samples/blob/dev-todo-mvvm-live/todoapp/app/src/main/java/com/example/android/architecture/blueprints/todoapp/SingleLiveEvent.java
Git Commands Basics: https://www.youtube.com/watch?v=HVsySz-h9r4 
Referencing complex data using room: https://mobikul.com/saving-complex-objects-using-android-room-library/ 
Git Branching model: https://nvie.com/posts/a-successful-git-branching-model/
https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/-shared-flow/ 
 Kotlin DSL : https://docs.gradle.org/current/userguide/kotlin_dsl.html 
https://goobar.io/adding-ktlint-to-your-kotlin-project/ 
https://medium.com/livefront/android-static-code-checks-keep-your-codebase-tidy-with-detekt-408435665fc3 
https://proandroiddev.com/mvi-architecture-with-kotlin-flows-and-channels-d36820b2028d
https://elizarov.medium.com/shared-flows-broadcast-channels-899b675e805c 
https://proandroiddev.com/dagger-2-part-three-new-possibilities-3daff12f7ebf 

Code Labs:
https://codelabs.developers.google.com/codelabs/basic-android-kotlin-training-welcome/index.html?index=..%2F..index#1
https://codelabs.developers.google.com/codelabs/android-lifecycles/index.html?index=..%2F..index#0
https://codelabs.developers.google.com/codelabs/kotlin-coroutines/#0
https://codelabs.developers.google.com/codelabs/android-room-with-a-view/index.html?index=..%2F..index#0
https://codelabs.developers.google.com/codelabs/android-navigation/#0
https://codelabs.developers.google.com/codelabs/android-workmanager/#0
https://developer.android.com/codelabs/android-adv-workmanager#0 
https://codelabs.developers.google.com/codelabs/android-databinding/index.html#0
https://codelabs.developers.google.com/codelabs/android-paging/#0
https://codelabs.developers.google.com/codelabs/android-dagger/#0 
https://codelabs.developers.google.com/codelabs/android-hilt/#2 
Creating http api(s) with Ktor https://play.kotlinlang.org/hands-on/Creating%20HTTP%20APIs%20with%20Ktor/02_application-init 
