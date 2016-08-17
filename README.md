# Curated iOS Resources

> This document features curated links to interesting talks and documentation for easy referencing.
> The links have been vetted by me for quality and usefulness. :gem:

# Architecture
### MVVM-C
* [MVVM-C in Practice](https://www.youtube.com/watch?v=9VojuJpUuE8) :vhs: by Steve "Scotty" Scott

> Introduces Coordinator Layer to abstract presentation logic out of
> ViewControllers into Coordinator objects.
> This improves separation of concerns.

* [Steve Scotts Demo Project for his Talk MVVM-C in Practice](https://github.com/macdevnet/mvvmc-demo) :file_folder:


# Frameworks
### Core Data
* [Modern Core Data](https://realm.io/news/tryswift-daniel-eggert-modern-core-data/) :vhs: by Daniel Eggert

> Lots of code examples how to improve the Core Data API by wrapping it into modern Swift.

* [Pragmatic Core Data](https://realm.io/news/cocoaheads-florian-kugler-pragmatic-core-data/) :vhs: by Florian Kugler

> He talks about how to decide which architectural approach to use as there are multiple ways to approach this topic with various pros and cons.

* [Futures and Promises, or how I learned to stop worrying and love the GCD](https://realm.io/news/altconf-michael-gray-futures-promises-gcd) :vhs: by Michael Gray

> Stop using callback closures and start using Futures. It does go well with Reactive Programming.


# Swift
### Protocol-Extensions
* [Protocol Extensions: A History](https://realm.io/news/tryswift-matthew-gillingham-protocol-extensions-history/) :vhs: by Matthew Gillingham
* [Practical Protocol-Oriented Programming](https://realm.io/news/appbuilders-natasha-muraschev-practical-protocol-oriented-programming/) :vhs: by Natasha Murashev

### Functional Programming
* [Swift Functors, Applicatives and Monads in Pictures](http://www.mokacoding.com/blog/functor-applicative-monads-in-pictures/) :book:

> Makes understanding those concepts so much easier.

### Generics in practice
* [Table View Controllers in Swift](https://realm.io/news/tryswift-chris-eidhof-table-view-controllers-swift/) :vhs: by Chris Eidhof

> Make Table View Controllers generic and pull out a configuration struct to simplify the controller's initializer 

### Misc
* [Weak, Strong, Unowned, Oh my!](http://krakendev.io/blog/weak-and-unowned-references-in-swift) :book: by Hector Matos 

> How to tackle retain cycles in Swift

* [Grokking Lazy Sequences & Collections](https://realm.io/news/slug-brandon-kase-grokking-lazy-sequences-collections/) :vhs: by Brandon Kase

> Building custom collections around huge sets of data that are fast to map, filter, reduce by deferring those operations until they are needed

* [Swift Scripting Redux: Localizations](https://realm.io/news/altconf-ayaka-nonaka-swift-scripting-redux-localization) :vhs: by Ayaka Nonaka

> Improving the internationalization process by declaring a custom `WFLocalizedString` method and scripting a string file generator in Swift

* [Prototyping Magic](https://realm.io/news/tryswift-adam-bell-prototyping-magic/) :vhs: by Adam Bell

> How animations can drastically improve the user experience and hands-on example how to prototype those in a playground with the [facebook/pop](https://github.com/facebook/pop) library

* [Discovering Native Swift Patterns](https://realm.io/news/slug-nick-oneill-native-swift-patterns/) :vhs: by Nick Oneill

> Shows a wide variety of good Swift patterns. The biggest take-away is don't get too clever with your code. There's a chance other developers might stumble over it.

# Testing
* [An Artsy Testing Tour](https://realm.io/news/tryswift-ash-furrow-artsy-testing-tour/) :vhs: by Ash Furrow

> Overview of different testing strategies. Be sure to check out the open-sourced Artsy apps and see their approaches.


# License
MIT (See `LICENSE` file)
I don't know if this is even necessary but it surely doesn't hurt, does it? :squirrel:
