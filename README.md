# happyHippo
How to mix MongoDB with Rails 2.1 for gandi.net hpp.io "the happy hippo"

We are creating a web app based on Penelope. Remember Penny v2.0 each archetype could hold a reference to another archetype. In Swift this was optionals. In MongoD this is a relational database. Through SSH portals we can run these systems on 24 core processor. Through native application we retrieve access to a parallel processing chip, albeit Nvidia GTX 560ti, essentially 1 gigaflop calculations per device codec. These A/V codecs can be programmed through use of OpenGL -> Opengles 3.0; 

Very powerful stuff, only what really is there to do with all this power? Imagine a chess app. It plays a game. The game is an object. Each move holds reference to many games played down the same route. Professional chess players of the highest caliber know this. It isn't about strategy, and optimizations, it IS ABOUT MEMORIZATION!!!

In SWIFT optionals(new Archetype, catch nil ref in try loops) presents a huge flaw. What to do if two objects hold nil reference of an object they need. This was solved through closure({return when(you).voyageToWalk(theDog(you))}()) As Rails solves a similar problem with Mongo. Are you ready for Ruby on Rails? Go over to Gandi.net now! Websites as low as $60. $30 domain registration plus half off domain hosting fees. S sized Simple Hosting solution. Select Create an Instance, choose closest server location. Instance Family set to Ruby / mongoDB (beta). 

Let's break down the closure steps into digestable bits:

Closure takes an argument, `closure(arg)`

the argument is unknow, We know whatever calls closure holds reference to itself, you. So we return what to do with you when. => `closure({return when(you)})` and we forgot the () to close it {}(call it) => `closure({return when(you)}())`

Now do something interesting, `closure({return when(you).voyageToChase()}())`

PROBLEM, ERROR ===>>> voyageToChase missing 1st arg!

Fix, `closure({return when(you).voyageToChase(arg)}())` when the only arg we hold is you(self).

ERROR ===>>> no known method voyageToChase(arg you) accepts 1st parameter of type you.

Solution, cast yourself as Dog, `func tailOfDog(arg: you) ->  val: Dog` function tailOfDog returns value of type Dog and takes 1st arg of type you. => `closure({return when(you).voyageToChase(TailOfDogma(you))}())`

~Note, in Swift an optional has to be unwrapped. Assuming you are an archetype(aka optional) i.e. `var you? = whoAreYou()` then you need to be unwrapped when called. `closure({return when(you?).voyageToChase(theTaleOfDogma(you?))}())`

No, no, no, the optionals have to be unwrapped when called, not when sent. That is to say the wrappers take args of type optional. ==> `closure({return when(you)?.voyageToChase(theTailOfDogma(you))}())`

Alas:=>  `try {closingIn({return when(you)?.voyageToChess(theTaleOfDogma())}())} catch {var you? = whoAreYou()}` self is implied.

Now the Tale of Dogma holds a reference to you, who ever you are.

##Now in Mongo wrapped in Rails for chess example

