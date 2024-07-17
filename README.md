# Android developer questions
This is just a list of a lot of questions. The main purpose is to go thru them, research ones that you forgot or don't know and be ready for interview. Sometimes there will be a list of words instead of full questions, think of them like "what is/are ..." or "when ... should be used". 

# Contents
- [Android](#Android)
- [Security](#Security)
- [XML views](#XML-views)
- [Jetpack Compose](#Jetpack-Compose)
- [Kotlin](#Kotlin)
- [Kotlin coroutines](#Kotlin-coroutines)
- [KMP](#KMP)
- [Java](#Java)
- [Java concurency](#Java-concurency)
- [Testing](#testing)
- [Architecture](#Architecture)
- [Soft-skills](#Soft-skills)
- [Other sources](#Other-sources)
### Android
- what are Android components?
- describe Activity lifecycle, config change and Fragment lifecycle
- Can we have fragment without view? what is it's purpose?
- Why activity is Android component and fragment is not?
- What is the pendingIntent?
- How long a service will be running? describe it's Service Lifecycle. how can we stop it?
- How to communicate between Activity and Service?
- what is the difference between the foreground and background service? on which thread they run by default?
- name 4 main android components
- Is it a good idea to directly use Strings in Activity?
- when it is safe to call Activity inside Fragment?
- what are Intents in android?
- Baseline Profiles
- Bundle limitations
- how Android keeps ViewModel instances?
- how much RAM can app use
- AOT vs JIT
- dalvik vs art
- savedinstancestate vs viewmodel vs persistent storage
### Security
- How would you secure sensitive information, for example PIN
- comunicate securely to server
- prevent MITM attack
- explain encyrption (symetric, asymetric, public/private keys)
- certificate pinning
### XML views
- How would you optimise RecyclerView?
- how XML layout gets parsed and drawn
- GPU Overdraws
- How can we draw on Canvas
### Jetpack Compose
- Modifiers, custom Modifiers
- states, derivedstateOf
- @Stable and @Imutable annotation
- CompositionLocals
- what are sideeffects, disposable effect
- regular composition vs subcomposition
- composable lifecycle
- rememberSaveable
- what is state hoisting in compose?
- How can we draw on Canvas
- phases of compose, and what happens in each phase
### Kotlin
- what is companion object? how can it be used from Java?
- How to call extension functions from Java?
- destructuring declaration in Kotlin?
- Delegation vs delegated properties
- what is reified keyword?
- How many constructors can data class have? can it be extendeed or inherited? How does it calculate hashcode and equals?
- Can child class of sealed class be an object?
- can a class inherit from enum class?
- Sealed class vs Enum
- Interface vs abstract class
- what are high order functions? scope functions(probably .apply, .let)? extension functions?
- how Kotlin and Java interop work?
- Kotlin vs Java
- Your favourite Kotlin feature
- Sequence vs Iterable
- primitives in Kotlin
### Kotlin coroutines
- structured concurency
- StateFlow vs SharedFlow
- what are Dispatachers and their differences?
- Scopes
- Channel vs Flow
- how corutines know about childrens and parent
- mutex
### KMP
- source sets
- expect/actual functions
- what is IR(intermediate representation)
- how kotlin compiler compiles code for different targets
- how would you share ViewModel for android and iOS
- you need to implement a functionality that requires context on Android but not on iOS. For example you need to rotate screen, so you have a function like setLandscapeMode(), what would be it's implementation?
### JVM
- can you manually trigger GC? Have you tried it?
- what the memory leak is and some often cases when when we see them?
- Any risk to in using Java reflection?
- Explain reflection
- what data structure have you heard of(not specific to JVM)?
### Java
- shallow vs deep copy
- what is the difference between HashMap and TreeMap?
- whats the contract between hashcode and equals?
- Is it enough to write one the equals method for my custom object to be used in a set?
- How to check if 2 objects are same?
- how Set can guarantee is that it really stored unique items?
- what is the difference between list and set?
- Which data structure to use for sorted data?
- What is Object, it's functions and purpose?
- how to fix memory leaks?
- what does finally block do?
- what are dagger scopes and how to use them?
- how garbage collector works? what are GC Roots?
- https://www.youtube.com/watch?v=VtQFcyym550&list=PLX8CzqL3ArzX0zXLKycnQslZaF6viV0oQ
- Java memory model
- happens before guarantee
- what is stack? what is kept in ti? and its limitations? what is benefits?

### Java concurency
- how we can use Set in multithreading environment? Things to do If I need to work with some collection in multithreading environment?
- what are AtomicBoolean, AtomicOtherThings?
- Volatile keyword in Java?
- deadlock vs race condition. How to prevent them?
- How JVM understands that another thread is doing work inside @Synchronised block?
- What is the synchronised keyword in Java?
- asyncronouse vs parallel vs concurency vs multithreading
- ThreadPool and Executors
- how costly it is to create a Thread
- synchronization primitives
### RxJava
- Flowable vs Observable
- subscribeOn vs observeOn. Can they be used multiple times?
- SwitchMap vs FlatMap in Rx
- Observable vs Flowable rxJava2
### Testing
- FIRST principle
- AAA pattern
- what are Stubs, mocks, Dummies, spies, Fakes
### Architecture
- how does MVP work?
- MVP vs MVVM vs MVI
- Let's assume you want to integrate some SharedPrefs component in this clean architecture and of course, being able to initialise the sharePrefs, you need an app context. Where would this sharedprefs component be in your clean architecture application? From what layer and to what layer would it provide data?
- The two most important principles of the clean architecture?
- what is SOLID?
- compare Dependency Inversion and Inversion of Control
- Where would you put logic to decide if we show local data or remote data?
- Anemic Domain Model
- tell, dont ask
- law of demeteer(LoD)
- how can you update data in a Fragment from another Fragment
- name different design patterns
- 4 OOP principles
- business logic, business rules
- your implementation of Paging3 with cache
- why not use mocks over fakes
- why clean code/arch sucks
### Soft skills
- Introduce yourself
- goal of sprint?
- how many story points to take in a sprint?
- why use story points and not time (days, weeks)?
- what are scrum ceremonies?
- why not estimate with days, weeks etc?
- what is TDD?
- what is BDD?
- any questions you have to us?
- non-functional requirements
- how can you know that the code in PR is okay and can be merged?
- differences between assignment and delegation and what cannot be delegated.
- [Soft skills in Problem Solving for a QA(I think in a way it is also relevant to devs)](https://www.youtube.com/watch?v=GGiTWyIBsKQ)
### System design
- TODO
### Things to ask interviewers
- what is the architecture of your project
- time zones you work on
### books to recommend
Thinking in Java, Refactoring, Clean code, Grokking Algorithms, Data Structures the Fun Way, Kotlin in Action, Clean Architecture
### Other sources
- [Android Broadcast's playlist](https://www.youtube.com/watch?v=B9zOXjtHY7Q&list=PL0SwNXKJbuNlEUhPKvf5qZIwDiZHfee-C)
- [Oday's videos](https://www.youtube.com/watch?v=EYjX6e5HXN0&list=PLtRrDEpV3zkv3eluXOdfAezjyvPda8CRE)
- [Anywhere club(related to Java)](https://www.youtube.com/watch?v=KM4J5XuXUzE&list=PLjQEUzuSWgX1w7tmP6gX3R1JiAJ1cT74l)
- [Interview with Senior JS Developer (not related to Android but still :D)](https://www.youtube.com/watch?v=aWfYxg-Ypm4&t=0s)
- [AndroidInterviewQ](https://www.reddit.com/r/AndroidInterviewQ/)
