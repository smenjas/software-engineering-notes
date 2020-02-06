# ["All Questions Answered" by Donald Knuth](https://youtu.be/xLBvCB2kr4Q)

[Google Tech Talks](https://www.youtube.com/channel/UCtXKDgv1AVoG88PLl8nGXmw)

Donald Knuth: I'm not sure I can match Lady Gaga. But anyway, when I was
teaching at Stanford, our last last day of class was reserved for all questions
answered. I told everybody they could cut class if they wanted to but if they
had something that they wanted to ask me (because they had paid their tuition
and everything) that was the time to do it. They could ask questions on any
subject whatsoever except religion, politics, or their final exam. Now, about 2
years ago at Google I gave a talk that had something to do with religion.
Politics is kind of depressing. If you want to ask questions about anything,
you know I'll still give it my best shot but I can probably give better answers
to things that I know something about. I understand that some people have been
submitting questions and then they're going to choose the best ones to vote or
anything. I'm hoping that the questions are not frequently asked questions.
Okay. Currently in the lead, okay, so, should I mention the guy who asked the
question? Does this show up on your table? Whatever. Okay, so, let's go.

"What is the theorem or contruction that in computer science that you feel is
most counterintuitive, and which one do you find most beautiful?

Well, this kind of ranking of things in a one dimensional criterion. Uh...
[crowd laughs] So first of all, we project onto the counterintuitive thing and
beauty aspect. Okay, I mean, somehow, you ask a parent which of their children
they like the best or something. Okay, counterintuitive, is anything intuitive
to me? I guess, going to more and more dimensions, our intuition seems to be
worse and worse. I understand George Dantzig once said that our intuition in
n-dimensions isn't worth a damn. I don't use that kind of language myself, but
anyway. So I think the things that we're doing in high dimensional spaces and
some of these methods now that are dealing with many degrees of freedom and
somehow, we can still map them down into something we can control. Those are
pretty [counterintuitive], probably.

The most beautiful theorem in computer science, my goodness. It's always the one
that I learned most recently, I guess, but there are a lot of contenders. And
then there's this boundary between computer science and mathematics which is
hard to draw. So let's see, right now I'm gonna go for construct that I find
very beautiful because during the last year, I've been playing around with a
data structure called [ZDD](https://crypto.stanford.edu/pbc/notes/zdd/zdd.html),
which isn't the greatest name, but it's the best way that I know to represent
families of sets. And families of sets cover many, many applications of all
kinds. I played with it. I started out with it thinking I would just spend one
page of volume four talking about ZDDs and a year later, I had almost a hundred
pages of introduction to it and I was still learning more stuff about ZDDs. I
think it's a very beautiful construction that needs to be studied much more,
and soon people will find more reason for it.

Now, let's see, should I alternate between this and people in the audience?
Okay, so let's take something from the floor.

Audience member: "Rumor has it there's an amazing pipe organ located somewhere
near where you live. Do you ever have anyone else, any other organist play that
pipe organ, and what's your favorite song played on it?"

DK: If you look in "Art of Computer Programming" volume three, in the index
under "royalties, use of" it'll take you to a page that shows a picture that
looks like organ pipe. After we had sold a few copies of volumes one, two, and
three, I was able to fulfill a dream and get a really nice instrument in one
wing of my house. I guess Alan Kay also has a great organ in his house down in
Southern California. My father was an organist and I took some lessons when I
was 12 years old on how to play an organ, and then I was called when I was down
in Pasadena as a grad student. All of a sudden the organist at the church I was
going to had a detached retina and the called me on Saturday and said, "Don, did
you really take a year of organ lessons when you were a teenager? Can you fill
in?" I learned at that time that all the wonderful literature that's been
written for pipe organs and I found some people down in Pasadena that had got an
organ in their house. So that became a dream of mine and I was able to realize
that in the middle '70s. I investigated, I was thinking maybe I could get
somebody in Denmark to build one for me because they had such beautiful
instruments. But that turned out to be impractical because they couldn't give me
a fixed price on it. So finally I found a really god builder near UCLA, and they
build four organs a year, and the one that's in my house is a joy. So we
occasionally have people from the American Guild of Organists come for recitals
and play on it. If you're an organist, just see me afterwards and you can come
and try. Stanford students used to practice on it, but there aren't so many
organ students now as there used to be.

AM: Thanks, I'll come see you afterward.

DK: Now the next one here. What kind of problems do you feel Google or the
industry at large should be working on but isn't. Hmmm. Another great question.
I'll just give you one. In Google Maps, a click back, a facility that I can get
the GPS coordinates, I can click on something on Google Map and then I have a
way to find out the GPS coordinates. That used to work last year until November
and it's gone now. If you [Google "GPS coordinates in Google
Maps"](https://www.google.com/search?q=GPS+coordinates+in+Google+Maps) you'll
find a lot of other irate users who miss this feature.

I'll take another one off the screen.

"Most of the low hanging fruits in computer science have already been reaped and
dissected in detail. Do you still see any of them surprisingly no one is trying
to reap?"

It's true that a lot of things have been dissected in detail, but it all feels,
including computer science it seems that people are always going down the same
roads. It's amazing to me the headway of how many times another low hanging
fruit appears in my consciousness. Both in computer science and even in
mathemtatics which have been around for, you know, hundreds of more years.
I was finishing the eighth volume of my collected papers, and I got to give a
plug for this book because actually I have to admit that I love it much more
than I can explain. It was decided more than 20 years ago that the papers that
have been written should be published in archival form with all the bugs removed
and adding extra information about the developments since the papers were
written and so on, and divided into eight topics. The first topic, literate
programming and the second topic was computer science in general for
non-specialists and the third book was about typography and so on. Well the
eighth of these eight was papers on fun and games. I saved that up for dessert.
I knew that if I kept that for last, it would keep me going through all the
other papers. So here I have this, finally, though I'm closing the door on
papers I've been writing. From now on I don't write any more papers. I add to
"Art of Computer Programming". There are 17 chapters in that book of papers that
were never before public. Two of those chapters I wrote last year on topics
which you might say are low hanging fruit. In one case it was about knight's
tours. I call it long and skinny knight's tours. I studied the problem of how
many ways are there to take a board that has three rows and n columns and find a
nice tour on this board. It turned out that it was a really interesting problem,
a really challenging problem. It taught me a lot of mathematics as I'm doing it.
I can tell you the exact number for any n. I can tell you the asymptotic numbers
and I classify them into different ways that surprise me. It seemed like low
hanging fruit because you don't need much, I mean, people have been thinking
about knight's tours for 200 years. Still, there was another open problem on
knight's tours called Celtic knight's tours which are knight's tours that are
especially beautiful because they don't have three lines that come almost
touching each other and so you can make beautiful Celtic knots from the patterns
anyway. Another example of something that was out there that hadn't been asked.
Two weeks ago, Ron Graham tells me about the following problem: take any
integer, write it in binary, so you've got basically any sequence of zeroes and
ones. You can always cut it, any string of zeroes and ones. You can always cut
it into substrings so that the sum of the, consider each substring has a binary
number. The sum of those binary numbers is a power of two. It's not easy but
there it is, in a sense, low hanging fruit I would say. You know, try it out but
don't start thinking about it just before trying to go to sleep because I was
just reading the information -- what is it called? "Learning in the Loo" or
something like this? -- It tells you how to get a good night's sleep. So anyway,
surprisingly, there's still a lot of low haning fruit, and just keep asking
questions. It's not really that likely that it's been totally explored yet.

Yeah?

Audience member: "Earlier, you were talking about GPS coordinates. There's a
Labs feature where you can get that on your cursor now. You can turn on a Labs
feature."

DK: A Labs feature?

AM: Yeah, if you go to the settings.

DK: Okay well tell me afterwards, because it used to be that through my maps I
could get something called position finder but they discontinued the ability to
use other people's Java code during my map.

AM: I'm not too familiar with what you're using, but if you just want GPS
coordinates that you can still get it.

DK: You know I can do it easily with Google Earth, but with Google Maps, I want
to be able to do it easy. I searched and nobody had published that solution.

AM: Well you can get it with the mouse cursor.

DK: A mouse cursor?

AM: Yeah there's a plugin for it.

DK: A plugin.

AM: A Labs plugin.

DK: A Lab plugin. Okay. All right. Well, thank you.

"With the increasing processing power and adoption of machine independent high
level languages, it's a common perception that being close to the metal doesn't
matter any more. What impact does this have on computer science as a field of
study?"

I don't agree that it doesn't matter any more. It doesn't matter as much to as
many people, but that's just relative. In absolute number it probably just
matters. We can still use more power. We can still use it. There's all knids of
problems where you want to push the envelope and do better and so, if you just, 
lots of problems, there's no point in my spending much time on something if it's
going to get the answer in a microsecond instead of ten seconds. So I write
really inefficient programs to solve certain problems, but boy when I was
studying these three binary knight's tours I had to find the inverse of a 700 by
700 matrix of polynomials and so I had to think about it and I had to know a bit
of what's going on. If people, imagine a whole generation growing up with this
philosophy that you don't need to know anything about the metal underneath, then
these programs they write are going to be really bad. So then of course there'll
be lots of low hanging fruit for people who want to make improvements.

Okay, next question. "Literate programming has never really taken off although
some scripting languages have improved code readability somewhat. What, if
anything, do you think has hindered its adoption.?"

That's a question that of course, I can try to answer, but literate programming
is so close to my heart that I'm totally biased about it, so you have to
discount what I say. Again, in absolute numbers we've got tens of thousands of
people who use literate programming. But still, that's less than 1% probably.
But I've got at least program that I wrote that was so complicated that I
totally believed that I would never ever have been able to get the program
finished at all if I didn't have literate programming to organize my thoughts
and make it done. This is the meta-simulator for my MX computer. I've got this
RISC machine that you can configure in basically infinitely many ways. You can
say for each instruction what functional unit belongs to how much of a pipeline
you want it to have, all kind of caches you can control in multiple issue of
instructions and did advanced prediction methods. You can imagine, you can
simulate what it  would be like if you had a processor with many more things
than we know how to build at the moment. But anyway I wrote this simulator and
it was the hardest challenge that I ever had as far as programming, I think.
With literate programming, I was able to finish it in a year, but without
literate programming I think I would've totally flopped. So for me, literate
programming isn't only nice, it's sort of essential. It's also noce because I
write average of maybe one program a day. Some of them are longer, some of them
are pretty short. But with this literate programming method, it really works for
me and makes me happy. Now, so on the other hand, you know, fewer than 100% of
the world loves it. I read a lot of code and a lot of the best code that I see
out there adheres to a certain set of conventions that are pretty good. They're
nowhere near as good as literate programming but still, they're good enough that
they're adequate. They're understood by a huge community, people know this style
and it's a lingua franca. For me to say drop that and go to literate programming
it's like saying, "Well, you know let's go to Esperanto instead of English," or
some other language that might be even better than Esperanto, you know, prove
that it's a much more logical language. Yet English is good enough and I'm not
going to change from English. Why should I tell somebody else to change the
style of programming that they all can use and it's good enough? Jon Bentley
might have hit the nail on the head because the people who like literate
programming the best are people who also seem to be people who also like to
write. You know, bloggers and teachers. Because when you're writing literate
programming, you're like in front of a class, you're writing for a human
audience rather than for the computer to understand. You're trying to explain
something to another programmer.
