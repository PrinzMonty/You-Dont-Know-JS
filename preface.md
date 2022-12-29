# Du kennst JS "noch" nicht - 2. Auflage

# Einleitung

Willkommen zur 2. Ausgabe der viel gelobten Buchreihe _Du kennst JS nicht._ Engl. You Don't Know JS (**YDKJS**)

Wenn du eines der Bücher der 1. Auflage gelesen hast, kannst du in dieser neuen Auflage eine Auffrischung erwarten, mit einigen aktualisierten Berichten darüber, was sich in den letzten fünf Jahren in JS geändert hat. Ich hoffe und glaube, dass du immer noch die gleiche Verpflichtung verspürst, JS zu respektieren und das Verlangen hast, herauszufinden, was es wirklich ausmacht.

Wenn du das erste Mal diese Bücher liest, freue ich mich, dass du hier bist. Bereite dich auf eine tiefe und umfassende Reise in alle Ecken von JavaScript vor.

Wenn du neu in der Programmierung oder in JS bist, solltest du wissen, dass diese Bücher nicht als leichte Einführung in JS gedacht sind. Das Material ist komplex und anspruchsvoll und geht viel tiefer, als es für einen Anfänger üblich ist. Du bist willkommen, egal welchen Hintergrund du hast, aber diese Bücher sind unter der Annahme geschrieben, dass du bereits mit JS vertraut bist und mindestens 6-9 Monate Erfahrung damit hast.

## Die Teile

Diese Bücher nähern sich JavaScript absichtlich entgegengesetzt dazu, wie _The Good Parts_ die Sprache behandelt. Nein, das bedeutet nicht, dass wir uns _the bad parts_ anschauen, sondern dass wir **alle Teile** erkunden werden.

Vielleicht hat man dir gesagt oder du hast es selbst gespürt, dass JS eine zutiefst fehlerhafte Sprache ist, die schlecht entworfen und inkonsequent implementiert wurde. Viele behaupten, dass es die schlechteste und beliebteste Sprache der Welt ist; dass niemand JS schreibt, weil er es will, sondern nur, weil er es muss, weil JS im Zentrum des Webs steht. Das ist eine lächerliche, ungesunde und gänzlich herablassende Behauptung.

Jeden Tag schreiben Millionen von Entwicklern JavaScript, und viele von ihnen schätzen und respektieren die Sprache.

Wie jede große Sprache hat sie brillante und schlechte Teile. Sogar der Schöpfer von JavaScript selbst, Brendan Eich, beklagt einige dieser Teile als Fehler. Aber er irrt sich: Es waren überhaupt keine Fehler. JS ist das, was es heute ist – die weltweit allgegenwärtigste und damit einflussreichste Programmiersprache – genau wegen all dieser Teile.

Glaube nicht der Lüge, dass du nur eine kleine Sammlung von "guten Teilen" lernen und verwenden solltest, während du alles Schlechte meidest. Kaufe nicht das "X ist das neue Y" Schlangenöl, das eine neue Funktion der Sprache sofort jede Verwendung einer früheren Funktion als veraltet verbannt. Höre nicht darauf, wenn jemand sagt, dein Code sei nicht "modern", weil er noch nicht ein Feature der Stufe 0 verwendet, das erst vor ein paar Wochen vorgeschlagen wurde!

Jeder Teil von JS ist nützlich. Einige Teile sind nützlicher als andere. Bei einigen Teilen musst du vorsichtiger und sorgfältiger sein.

Ich finde es absurd, zu versuchen, ein wirklich effektiver JavaScript-Entwickler zu sein, während man nur einen kleinen Teil der Möglichkeiten dieser Sprache nutzt. Kannst du dir einen Bauarbeiter mit einem Werkzeugkasten voller Werkzeuge vorstellen, der nur einen Hammer benutzt und den Schraubenzieher oder das Maßband als minderwertig verhöhnt? Das wäre einfach nur dumm.

Ich behaupte vorbehaltlos, dass du alle Teile von JavaScript erlernen solltest, und wo es angebracht ist, solltest du es auch benutzen! Ich bin so kühn und behaupte: Es ist Zeit, alle JS-Bücher wegzuwerfen, die dir etwas anderes erzählen möchten.

## The Title?

So what's the title of the series all about?

I'm not trying to insult you with criticism about your current lack of knowledge or understanding of JavaScript. I'm not suggesting you can't or won't be able to learn JavaScript. I'm not boasting about secret advanced insider wisdom that I and only a select few possess.

Seriously, all those were real reactions to the original series title before folks even read the books. And they're baseless.

The primary point of the title "You Don't Know JS Yet" is to point out that most JS developers don't take the time to really understand how the code that they write works. They know _that_ it works—that it produces a desired outcome. But they either don't understand exactly _how_, or worse, they have an inaccurate mental model for the _how_ that falters on closer scrutiny.

I'm presenting a gentle but earnest challenge to you the reader, to set aside the assumptions you have about JS, and approach it with fresh eyes and an invigorated curiosity that leads you to ask _why_ for every line of code you write. Why does it do what it does? Why is one way better or more appropriate than the other half-dozen ways you could have accomplished it? Why do all the "popular kids" say to do X with your code, but it turns out that Y might be a better choice?

I added "Yet" to the title, not only because it's the second edition, but because ultimately I want these books to challenge you in a hopeful rather than discouraging way.

But let me be clear: I don't think it's possible to ever fully _know_ JS. That's not an achievement to be obtained, but a goal to strive after. You don't finish knowing everything about JS, you just keep learning more and more as you spend more time with the language. And the deeper you go, the more you revisit what you _knew_ before, and you re-learn it from that more experienced perspective.

I encourage you to adopt a mindset around JavaScript, and indeed all of software development, that you will never fully have mastered it, but that you can and should keep working to get closer to that end, a journey that will stretch for the entirety of your software development career, and beyond.

You can always know JS better than you currently do. That's what I hope these YDKJSY books represent.

## The Mission

The case doesn't really need to be made for why developers should take JS seriously—I think it's already more than proven worthy of first-class status among the world's programming languages.

But a different, more important case still needs to be made, and these books rise to that challenge.

I've taught more than 5,000 developers from teams and companies all over the world, in more than 25 countries on six continents. And what I've seen is that far too often, what _counts_ is generally just the result of the program, not how the program is written or how/why it works.

My experience not only as a developer but in teaching many other developers tells me: you will always be more effective in your development work if you more completely understand how your code works than you are solely _just_ getting it to produce a desired outcome.

In other words, _good enough to work_ is not, and should not be, _good enough_.

All developers regularly struggle with some piece of code not working correctly, and they can't figure out why. But far too often, JS developers will blame this on the language rather than admitting it's their own understanding that is falling short. These books serve as both the question and answer: why did it do _this_, and here's how to get it to do _that_ instead.

My mission with YDKJSY is to empower every single JS developer to fully own the code they write, to understand it and to write with intention and clarity.

## The Path

Some of you have started reading this book with the goal of completing all six books, back to back.

I would like to caution you to consider changing that plan.

It is not my intention that YDKJSY be read straight through. The material in these books is dense, because JavaScript is powerful, sophisticated, and in parts rather complex. Nobody can really hope to _download_ all this information to their brains in a single pass and retain any significant amount of it. That's unreasonable, and it's foolish to try.

My suggestion is you take your time going through YDKJSY. Take one chapter, read it completely through start to finish, and then go back and re-read it section by section. Stop in between each section, and practice the code or ideas from that section. For larger concepts, it probably is a good idea to expect to spend several days digesting, re-reading, practicing, then digesting some more.

You could spend a week or two on each chapter, and a month or two on each book, and a year or more on the whole series, and you would still not be squeezing every ounce of YDKJSY out.

Don't binge these books; be patient and spread out your reading. Interleave reading with lots of practice on real code in your job or on projects you participate in. Wrestle with the opinions I've presented along the way, debate with others, and most of all, disagree with me! Run a study group or book club. Teach mini-workshops at your office. Write blog posts on what you've learned. Speak about these topics at local JS meetups.

It's never my goal to convince you to agree with my opinion, but to encourage you to own and be able to defend your opinions. You can't get _there_ with an expedient read-through of these books. That's something that takes a long while to emerge, little by little, as you study and ponder and re-visit.

These books are meant to be a field-guide on your wanderings through JavaScript, from wherever you currently are with the language, to a place of deeper understanding. And the deeper you understand JS, the more questions you will ask and the more you will have to explore! That's what I find so exciting!

I'm so glad you're embarking on this journey, and I am so honored you would consider and consult these books along the way. It's time to start _getting to know JS_.
