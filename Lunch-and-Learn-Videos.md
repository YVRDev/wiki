# Lunch and Learn Videos

Collection of videos that are recommended for team lunch and learns

## Candidates Videos (yet to be watched)

* André Staltz - The introduction to Reactive Programming you've been missing
  * https://gist.github.com/staltz/868e7e9bc2a7b8c1f754

* Brad Urani - Immutability (RubyConf 2015) 35 mins
  * http://confreaks.tv/videos/rubyconf2015-changing-the-unchangeable-the-hows-and-whys-of-immutable-data-structures

* Noel Rappin - Estimating rubyconf 2015 (40mins)
  * http://confreaks.tv/videos/rubyconf2015-i-estimate-this-talk-will-be-20-minutes-long-give-or-take-10-minutes

* Grey Young - 8 lines of code (45 mins)
  * http://www.infoq.com/presentations/8-lines-code-refactoring

* Katrina Owen - Here Be Dragons (bathruby 2015) 24mins
  * https://www.youtube.com/watch?v=QAUHYzC9kFM

* Kathy Sierra - Making Badass Developers (25min)
  * https://www.youtube.com/watch?v=FKTxC9pl-WM

* Katrina Owen - Overkill - 33mins
  * https://www.youtube.com/watch?v=qLpvc5r6Bb0

* Coda Hale - Code as Craft
  * http://original.livestream.com/etsy/video?clipId=pla_780bfe22-12e8-4c7f-8c7b-06cc6cac9c49
  * Obviously, you care about the craft of programming. You spend time honing your skills, refactoring your code, learning new techniques, and experimenting with different libraries. But did you know where you sit, who you talk to, and how you report to your manager all affect the way your software is structured? In 2012, I was invited to Etsy’s Code As Craft series and spoke about how organizational structures influence software and the implications for designing scalable, resilient software systems and companies.

* Coda Hale - Metrics Metrics Everywhere
  * http://www.youtube.com/watch?v=czes-oa0yik
  * If you don’t measure it, you can’t optimize it. At GitHub’s CodeConf in 2011, I spoke about Yammer’s service-level performance metrics, how we used them to guide our development strategy, and how you can improve the transparency of your own software.

* David Chelimsky - Maintaining Balance While Reducing Duplication
  * http://confreaks.tv/videos/rubyconf2010-maintaining-balance-while-reducing-duplication

* Dan Quan - Pairing (rockymountain ruby conf sept 2015)
  * http://confreaks.tv/videos/rmr2015-policing-and-pairing-an-unlikely-preparation

* Git storytelling / good messages (rubyconf 2015) 38 mins
  * http://confreaks.tv/videos/rubyconf2015-communicating-intent-through-git

* Justin Searls - Ruby Test Styleguide (Rubyconf 2015)
  * http://confreaks.tv/videos/rubyconf2015-how-to-stop-hating-your-test-suite

## Watched (with occasional notes on takeaways)

Katrina Owen - Therapeutic Refactoring https://www.youtube.com/watch?v=J4dlF0kcThQ
Had cool part on how to build up a test suite for hairy code before beginning refactoring

Jan 25
Colin Fulton - Magic of Text editors (rubyconf 2015)
http://confreaks.tv/videos/rubyconf2015-string-theory-and-time-travel-the-humble-text-editor

Jan 18
Sandi Metz - Magic Tricks of Testing
http://confreaks.tv/videos/railsconf2013-the-magic-tricks-of-testing
Rules for Unit Testing (*not* integration tests) :
  - Test interface for incoming query messages
  - Test for incoming command messages with direct public side effects
  - Do not test Private Methods
  - Do not test outgoing query messages
  - On outgoing command messages, test expect to send method
  - Avoid redundancy


Jan 11, 2016
Sandi Metz - Gilded Rose Kata (all the little things)- Railsconf 2014 (40 mins) http://confreaks.tv/videos/railsconf2014-all-the-little-things
make small things
duplication is better than the wrong abstraction
sOlid - open/closed. New functionality should not require editing of existing code
inheritance is not evil, but hierarchies should be short and narrow (subclasses should use all parent methods)

Jan 4, 2016
Sandi Metz - Rules
http://confreaks.tv/videos/baruco2013-rules
Classes can be no longer than one hundred lines of code.
Methods can be no longer than five lines of code.
Pass no more than four parameters into a method. Hash options are parameters.
Controllers can instantiate only one object. Therefore, views can only know about one instance variable and views should only send messages to that object (@object.collaborator.value is not allowed).


Dec 14, 2015
Sandi Metz - Nothing is Something (Railsconf 2015) http://confreaks.tv/videos/railsconf2015-nothing-is-something)