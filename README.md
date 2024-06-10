# Android developer questions
This is just a list of a lot of questions. The main purpose is to go thru them, research ones that you forgot or don't know and be ready for interview. Sometimes there will be a list of words instead of full questions, think of them like "what is/are ..." or "when ... should be used". 

# Other sources
 - https://www.youtube.com/watch?v=VtQFcyym550&list=PLX8CzqL3ArzX0zXLKycnQslZaF6viV0oQ
# Contents
Android
XML views
Jetpack Compose
Kotlin
Kotlin coroutines
Java
Java concurency
Architecture
Soft skills

### Android
- what are Android components?
- describe Activity lifecycle, config change and Fragment lifecycle
- Can we have fragment without view? what is it's purpose?
- Why activity is Android component and fragment is not?
- What is the pendingIntent?
- How long a service will be running? how can we stop it?
- How to communicate between Activity and Service?
- what is the difference between the foreground and background service? on which thread they run by default?
- name 4 main android components
- Is it a good idea to directly use Strings in Activity?
- when it is safe to call Activity inside Fragment?
- what are Intents in android?
- Baseline Profiles
### XML views
- TODO
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
### Kotlin coroutines
### JVM
- can you manually trigger GC? Have you tried it?
- what the memory leak is and some often cases when when we see them?
- Any risk to in using Java reflection?
- Explain reflection
### Java
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
### Java concurency
- how we can use Set in multithreading environment? Things to do If I need to work with some collection in multithreading environment?
- what are AtomicBoolean, AtomicOtherThings?
- Volatile keyword in Java?
- deadlock vs race condition
- How JVM understands that another thread is doing work inside @Synchronised block?
- What is the synchronised keyword in Java?
### RxJava
- Flowable vs Observable
- subscribeOn vs observeOn. Can they be used multiple times?
- SwitchMap vs FlatMap in Rx
- Observable vs Flowable rxJava2
### Architecture
- how does MVP work?
- MVP vs MVVM vs MVI
- Let's assume you want to integrate some SharedPrefs component in this clean architecture and of course, being able to initialise the sharePrefs, you need an app context. Where would this sharedprefs component be in your clean architecture application? From what layer and to what layer would it provide data?
- The two most important principles of the clean architecture?
- what is SOLID?
- Dependency Inversion?
- Where would you put logic to decide if we show local data or remote data?
### Soft skills
- goal of sprint?
- how many story points to take in a sprint?
- why use story points and not time (days, weeks)?
- what are scrum ceremonies?
- why not estimate with days, weeks etc?
- what is TDD?
- what is BDD?
- any questions you have to us?
- how can you know that the code in PR is okay and can be merged?
