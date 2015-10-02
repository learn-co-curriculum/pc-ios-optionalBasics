# pc-ios-optionalBasics
## So What the Heck is With the '?' and '!'?
Don't worry, you didn't accidentally sign up for English class. Those little punctuations are actually super important and are there solely to help you write awesome apps.

##OK Maybe a littttttle bit of English
But to help understand what an optional is for one sec, let's take two sentences:
> There is cinnamon in the cupboard!

> There is cinnamon in the cupboard?

Read these out loud. What's the difference? In the first example, the '!' indicates with certainty that there is in fact cinnamon in the cupboard. You're screaming it with confidence. It would be very weird and highly unlikely that there actually wouldn't be cinnamon in the cupboard.

But what about in the second example? If there ended up actually being no cinnamon in the cupboard, would you be that shocked? No, of course not. You used a '?' because you weren't certain that there would actually be cinnamon.

##I don't even like cinnamon can we talk about Swift now?
OK, OK, fine, fine. Now let's actually talk about Swift. Just like with our two sentences above, you use '?' and '!' depending on how confident you are whether there is going to be actual Cinn...err I mean, a value for a particular variable. Let's do one more example, using something I know you know a lot about, a Person.

All people have a couple of basic things. They have an age, they have a height. They have a weight. Sure, these things vary from person to person, but by being a person, you are ***SURE*** that they have them. So let me ask you, which sentence makes more sense here?
> He has a height!

> He has a height?

You would never be uncertain if someone would have a height, you know they do. So if you had a Person, and you wanted to put that in code, it would probably look something like this:

`var height:Int! = 0`

That is completely legit code as you know for a fact that a person has AT MINIMUM a height of 0.

But what about stuff that some people have and others don't? For example, a lot of people have favorite countries, but do you need to have a favorite country in order to be considered human? No of course not! Maybe you haven't traveled to enough to pick a favorite. Maybe you don't like any of them. So back to English...
> He has a favorite country?

This is not at all a weird sentence. Maybe he does, maybe he doesn't have a favorite country. So, in code, we would make this `Optional` by putting a question mark.

`var favoriteCountry:String?`

This tells the computer that the person may or may not have a favorite country. And if they do not, it's totally cool, we just need to handle that (more on this later in the course).

Long story short, there is a lot to this concept of "Optional" values and how to actually use them in code. But if you get the difference between assuring something has a value (!) and not being positive (?) you're well on your way.
