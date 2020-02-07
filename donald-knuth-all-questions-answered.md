# ["All Questions Answered" by Donald Knuth](https://youtu.be/xLBvCB2kr4Q)

Donald Knuth spoke on March 24th, 2011. The talk was posted on March 28th, 2011.

[Google Tech Talks](https://www.youtube.com/channel/UCtXKDgv1AVoG88PLl8nGXmw)

---

**[Donald Knuth](https://www-cs-faculty.stanford.edu/~knuth/):** I'm not sure I
can match [Lady Gaga](https://youtu.be/hNa_-1d_0tA). [crowd laughs] But anyway,
when I was teaching at Stanford, our last day of class was reserved for all
questions answered. I told everybody they could cut class if they wanted to but
if they had something that they wanted to ask me (because they had paid their
tuition and everything) that was the time to do it. They could ask questions on
any subject whatsoever except religion, politics, or their final exam. [crowd
laughs] Now, about 2 years ago at Google I gave [a talk that had something to
do with religion](https://youtu.be/JPpk-1btGZk). Politics is kind of
depressing. If you want to ask questions about anything, you know I'll still
give it my best shot but I can probably give better answers to things that I
know something about. I understand that some people have been submitting
questions and then they're going to choose the best ones to vote or anything.
I'm hoping that the questions are not [frequently asked
questions](https://www-cs-faculty.stanford.edu/~knuth/faq.html). Okay.
Currently in the lead, okay, so, should I mention the guy who asked the
question? Does this show up on your table? Whatever. Okay, so, let's go.

---

> What is the theorem or construction that in computer science that you feel is
> most counterintuitive, and which one do you find most beautiful?

Well, this kind of ranking of things in a [one
dimensional](https://en.wikipedia.org/wiki/One-dimensional_space) criterion.
Uh... [crowd laughs] So first of all, we project onto the counterintuitive
thing and beauty aspect. Okay, I mean, somehow, you ask a parent which of their
children they like the best or something. Okay, counterintuitive, is anything
intuitive to me? I guess, going to more and more dimensions, our intuition
seems to be worse and worse. I understand [George
Dantzig](https://en.wikipedia.org/wiki/George_Dantzig) once said that "Our
intuition in n-dimensions isn't worth a damn." I don't use that kind of
language myself, but anyway. So I think the things that we're doing in [high
dimensional spaces](https://en.wikipedia.org/wiki/Curse_of_dimensionality) and
some of these methods now that are dealing with many [degrees of
freedom](https://en.wikipedia.org/wiki/Degrees_of_freedom) and somehow, we can
still map them down into something we can control. Those are pretty
[counterintuitive], probably.

The most beautiful theorem in computer science, my goodness. It's always the one
that I learned most recently, I guess, but there are a lot of contenders. And
then there's this boundary between computer science and mathematics which is
hard to draw. So let's see, right now I'm gonna go for construct that I find
very beautiful because during the last year, I've been playing around with a
data structure called [ZDD](https://crypto.stanford.edu/pbc/notes/zdd/zdd.html),
which isn't the greatest name, but it's the best way that I know to represent
[families of sets](https://en.wikipedia.org/wiki/Family_of_sets). And families
of sets cover many, many applications of all kinds. I played with it. I started
out with it thinking I would just spend one page of volume four talking about
ZDDs and a year later, I had almost a hundred pages of introduction to it and I
was still learning more stuff about ZDDs. I think it's a very beautiful
construction that needs to be studied much more, and soon people will find more
reason for it.

Now, let's see, should I alternate between this and people in the audience?
Okay, so let's take something from the floor.

---

**Audience member:** Rumor has it there's an amazing [pipe
organ](https://www-cs-faculty.stanford.edu/~knuth/organ.html) located somewhere
near where you live. Do you ever have anyone else, any other organist play that
pipe organ, and what's your favorite song played on it?

**DK:** If you look in [*Art of Computer
Programming*](https://www-cs-faculty.stanford.edu/~knuth/taocp.html) volume
three, in the index under "royalties, use of" it'll take you to a page that
shows a picture that looks like organ pipe. After we had sold a few copies of
volumes one, two, and three, I was able to fulfill a dream and get a really nice
instrument in one wing of my house. I guess [Alan
Kay](https://en.wikipedia.org/wiki/Alan_Kay) also has a great organ in his house
down in Southern California. My father was an organist and I took some lessons
when I was 12 years old on how to play an organ, and then I was called when I
was down in Pasadena as a grad student. All of a sudden the organist at the
church I was going to had a detached retina and the called me on Saturday and
said, "Don, did you really take a year of organ lessons when you were a
teenager? Can you fill in?" I learned at that time that all the wonderful
literature that's been written for pipe organs and I found some people down in
Pasadena that had got an organ in their house. So that became a dream of mine
and I was able to realize that in the middle '70s. I investigated, I was
thinking maybe I could get somebody in Denmark to build one for me because they
had such beautiful instruments. But that turned out to be impractical because
they couldn't give me a fixed price on it. So finally I found a really good
builder near UCLA, and they build four organs a year, and the one that's in my
house is a joy. So we occasionally have people from the [American Guild of
Organists](https://www.agohq.org/) come for recitals and play on it. If you're
an organist, just see me afterwards and you can come and try. Stanford students
used to practice on it, but there aren't so many organ students now as there
used to be.

**AM:** Thanks, I'll come see you afterward.

---

**DK:** Now the next one here.

> What kind of problems do you feel Google or the industry at large should be
> working on but isn't.

Hmmm. Another great question. I'll just give you one. In Google Maps, a click
back, a facility that I can get the GPS coordinates, I can click on something
on Google Map and then I have a way to find out the GPS coordinates. That used
to work last year until November and it's gone now. If you [Google "GPS
coordinates in Google
Maps"](https://www.google.com/search?q=GPS+coordinates+in+Google+Maps) you'll
find a lot of other irate users who miss this feature.

I'll take another one off the screen.

---

> Most of the low hanging fruits in computer science have already been reaped
> and dissected in detail. Do you still see any of them surprisingly no one is
> trying to reap?

It's true that a lot of things have been dissected in detail, but it all feels,
including computer science, it seems that people are always going down the same
roads. It's amazing to me the headway of how many times another low hanging
fruit appears in my consciousness. Both in computer science and even in
mathematics which have been around for, you know, hundreds of more years.

I was finishing the eighth volume of [my collected
papers](https://www-cs-faculty.stanford.edu/~knuth/selected.html) out of eight,
and I got to give a plug for this book because actually I have to admit that I
love it much more than I can explain. It was decided more than 20 years ago
that the papers that have been written should be published in archival form
with all the bugs removed and adding extra information about the developments
since the papers were written and so on, and divided into eight topics. The
first topic, [literate
programming](https://www-cs-faculty.stanford.edu/~knuth/lp.html) and the second
topic was [computer science in general for
non-specialists](https://www-cs-faculty.stanford.edu/~knuth/cs.html) and the
third book was about
[typography](https://www-cs-faculty.stanford.edu/~knuth/dt.html) and so on.
Well the eighth of these eight was papers on [fun and
games](https://www-cs-faculty.stanford.edu/~knuth/fg.html). I saved that up for
dessert. I knew that if I kept that for last, it would keep me going through
all the other papers. So here I have this, finally, though I'm closing the door
on papers I've been writing. From now on I don't write any more papers. I add
to *Art of Computer Programming*.

There are 17 chapters in that book of papers that were never before public. Two
of those chapters I wrote last year on topics which you might say are low
hanging fruit. In one case it was about [knight's
tours](https://en.wikipedia.org/wiki/Knight%27s_tour). I call it long and
skinny knight's tours. I studied the problem of how many ways are there to take
a board that has three rows and n columns and find a nice tour on this board.
It turned out that it was a really interesting problem, a really challenging
problem. It taught me a lot of mathematics as I'm doing it. I can tell you the
exact number for any n. I can tell you the asymptotic numbers and I can
classify them into different ways that surprise me. It seemed like low hanging
fruit because you don't need much, I mean, people have been thinking about
knight's tours for 200 years. Still, there was another open problem on knight's
tours called Celtic knight's tours which are knight's tours that are especially
beautiful because they don't have three lines that come almost touching each
other and so you can make beautiful [Celtic
knots](https://en.wikipedia.org/wiki/Celtic_knot) from the patterns anyway.

Another example of something that was out there that hadn't been asked. Two
weeks ago, [Ron Graham](https://en.wikipedia.org/wiki/Ronald_Graham) tells me
about the following problem: take any integer, write it in binary, so you've got
basically any sequence of zeroes and ones. You can always cut it, any string of
zeroes and ones. You can always cut it into substrings so that the sum of the,
consider each substring has a binary number. The sum of those binary numbers is
a power of two. It's not easy but there it is, in a sense, low hanging fruit I
would say. You know, try it out but don't start thinking about it just before
trying to go to sleep because I was just reading the information -- what is it
called? [*Learning in the Loo*](https://padlet.com/kerszi/LearningInTheLoo) or
something like this? -- It tells you how to get a good night's sleep. So anyway,
surprisingly, there's still a lot of low hanging fruit, and just keep asking
questions. It's not really that likely that it's been totally explored yet.

Yeah?

---

**Audience member:** Earlier, you were talking about GPS coordinates. There's a
Labs feature where you can get that on your cursor now. You can turn on a Labs
feature.

**DK:** A Labs feature?

**AM:** Yeah, if you go to the settings.

**DK:** Okay well tell me afterwards, because it used to be that through my
maps I could get something called position finder but they discontinued the
ability to use other people's Java code during my map.

**AM:** I'm not too familiar with what you're using, but if you just want GPS
coordinates that you can still get it.

**DK:** You know I can do it easily with Google Earth, but with Google Maps, I
want to be able to do it easy. I searched and nobody had published that
solution.

**AM:** Well you can get it with the mouse cursor.

**DK:** A mouse cursor?

**AM:** Yeah there's a plugin for it.

**DK:** A plugin.

**AM:** A Labs plugin.

**DK:** A Lab plugin. Okay. All right. Well, thank you.

---

> With the increasing processing power and adoption of machine independent high
> level languages, it's a common perception that being [close to the
> metal](https://en.wikipedia.org/wiki/Low-level_programming_language) doesn't
> matter any more. What impact does this have on computer science as a field of
> study?

I don't agree that it doesn't matter any more. It doesn't matter as much to as
many people, but that's just relative. In absolute number it probably just
matters. We can still use more power. We can still use it. There's all kinds of
problems where you want to push the envelope and do better and so, if you just,
lots of problems, there's no point in my spending much time on something if it's
going to get the answer in a microsecond instead of ten seconds. So I write
really inefficient programs to solve certain problems, but boy when I was
studying these three binary knight's tours I had to find the inverse of a 700 by
700 matrix of polynomials and so I had to think about it and I had to know a bit
of what's going on. If people, imagine a whole generation growing up with this
philosophy that you don't need to know anything about the metal underneath, then
these programs they write are going to be really bad. So then of course there'll
be lots of low hanging fruit for people who want to make improvements. [crowd
laughs]

Okay, next question.

---

> Literate programming has never really taken off although some scripting
> languages have improved [code
> readability](https://en.wikipedia.org/wiki/Computer_programming#Readability_of_source_code)
> somewhat. What, if anything, do you think has hindered its adoption?

That's a question that of course, I can try to answer, but literate programming
is so close to my heart that I'm totally biased about it, so you have to
discount what I say. Again, in absolute numbers we've got tens of thousands of
people who use literate programming. But still, that's less than 1% probably.
But I've got at least one program that I wrote that was so complicated that I
totally believed that I would never ever have been able to get the program
finished at all if I didn't have literate programming to organize my thoughts
and make it done. This is the meta-simulator for my [MMIX
computer](https://www-cs-faculty.stanford.edu/~knuth/mmix.html). I've got this
[RISC machine](https://en.wikipedia.org/wiki/Reduced_instruction_set_computer)
that you can configure in basically infinitely many ways. You can say for each
[instruction](https://en.wikipedia.org/wiki/Instruction_set_architecture) what
[functional unit](https://en.wikipedia.org/wiki/Execution_unit) belongs to how
much of a [pipeline](https://en.wikipedia.org/wiki/Instruction_pipelining)
you want it to have, all kind of
[caches](https://en.wikipedia.org/wiki/Cache_%28computing%29) you can control in
[multiple issue of
instructions](https://en.wikipedia.org/wiki/Instruction-level_parallelism) and
did advanced [prediction](https://en.wikipedia.org/wiki/Branch_predictor)
methods. You can imagine, you can simulate what it would be like if you had a
processor with many more things than we know how to build at the moment. But
anyway I wrote this simulator and it was the hardest challenge that I ever had
as far as programming, I think. With literate programming, I was able to finish
it in a year, but without literate programming I think I would've totally
flopped. So for me, literate programming isn't only nice, it's sort of
essential. It's also nice because I write average of maybe one program a day.
Some of them are longer, some of them are pretty short. But with this literate
programming method, it really works for me and makes me happy.

Now, so on the other hand, you know, fewer than 100% of the world loves it. I
read a lot of code and a lot of the best code that I see out there adheres to a
certain set of conventions that are pretty good. They're nowhere near as good as
literate programming but still, they're good enough that they're adequate.
They're understood by a huge community, people know this style and it's a lingua
franca. For me to say drop that and go to literate programming it's like saying,
"Well, you know let's go to Esperanto instead of English," or some other
language that might be even better than Esperanto, you know, prove that it's a
much more logical language. Yet English is good enough and I'm not going to
change from English. Why should I tell somebody else to change the style of
programming that they all can use and it's good enough? Jon Bentley might have
hit the nail on the head because the people who like literate programming the
best are people who also seem to be people who also like to write. You know,
bloggers and teachers. Because when you're writing literate programming, you're
like in front of a class, you're writing for a human audience rather than for
the computer to understand. You're trying to explain something to another
programmer. There's a certain percentage of the world like to write and there's
a certain percentage of the world that's good at programming, and you have to be
in the intersection of those two in order to really love literate programming.
So that might be why it hadn't taken off. Still, I think that if Google
managers would sort of, you know, say "Let's have a test here and we're going
to do some system with literate programming," you find that it might in fact
make Google even better than it is now. But anyway, I'm not going to change and
I think a lot of people understand, I can point to some large programs that
probably more people understand these difficult programs than any other
programs on their side. So that's my take on that.

One more thing though, my book on fun and games, the last chapter... Okay, I
don't know how many people know this, but my first publication was in [Mad
Magazine](https://en.wikipedia.org/wiki/Mad_%28magazine%29). When I was a
freshman in college, this article came out and so that's chapter one of my
papers on fun and games. The last chapter is equally crazy and it's a smooth
talk that I gave last summer where I basically promised that, people were asking
about the future of tech and I said, "Well, I've decided that everything I did
on that project was a mistake and so I've secretly started this company and I've
got this new product that's coming out that's not only going to do
three-dimensional type setting, but it's also including manufacturing on demand,
and it also includes things like search engines and social networking, and it
sells differential equations, and it's all written in
[Scheme](https://en.wikipedia.org/wiki/Scheme_%28programming_language%29), and
we gave up on literate programming because everyone knows documentation is a
pain." Okay? So that was the hardest paragraph for me to write. But I thought I
would use some kind of book ends to have one. You know I started out in Mad
Magazine and I had to have something to match it as my final publication. Okay.
Jeff?

---

**Jeff:** So are you using
[call/cc](https://en.wikipedia.org/wiki/Call-with-current-continuation) on that
program?

**DK:** Am I using call?

**Jeff:** Are you using call/cc on that Scheme program? Here's my question,
it's a math search question. So this morning I used [social
search](https://en.wikipedia.org/wiki/Social_search) to find the name of a
silly technique called [propensity score
matching](https://en.wikipedia.org/wiki/Propensity_score_matching). Sometimes I
know that there's a mathematical concept that exists but I don't know what the
name of it is and I want to go find out about it. Integer sequences is a good
example of a search technique that allows me to go find...

**DK:** Yeah, the Handbook of, the [Online Encyclopedia of Integer
Sequences](https://oeis.org/), you can calculate your way into the literature.
If you can compute the first six terms of some sequence, you'll find if there's
anybody else that's ever been interested in that.

**Jeff:** Right. So that's a good solution, but that doesn't solve all
problems. So how do you, when you know that there's been a mathematical concept
that you've stumbled across but you don't know the name of it, how do you find
out what that name is so you don't have to go
[reinvent](https://en.wikipedia.org/wiki/Reinventing_the_wheel) everything?

**DK:** Okay. Well, the answer is of course I'm 73 years old now I developed a
bunch of friends and so I know...

**Audience member:** Social search then.

**DK:** Yeah, right. So I know who to ask, but if it's a completely new field
then I haven't got any good method myself. Often there are certain questions
that I ask [Ira Gessel](https://en.wikipedia.org/wiki/Ira_Gessel), others I ask
[Richard Stanley](https://en.wikipedia.org/wiki/Richard_P._Stanley), or Jeff
Almonds, et cetera. Fortunately I can go down the hall at Stanford and get the
answers to most of these questions and we get together for lunch every week. So
that's my solution, but it's not an algorithmic solution at all.

**Jeff:** Yeah, you don't scale very well.

**DK:** Well in fact, that would be terrible. Let's face it, if there were ten
people like me in the world, we wouldn't have time to read each other's books.

---

> How many P!=NP proofs have you seen? What is your opinion on this, [P=NP or
> P!=NP](https://en.wikipedia.org/wiki/P_versus_NP_problem)? When do you think
> it is going to be settled?

Oh boy. I got one last week, a guy sent me Java code that seems to prove that
P=NP and I'm pretty sure that he's finding [maximum
cliques](https://en.wikipedia.org/wiki/Clique_problem) and I'm pretty sure that
the way he's generating the data is from a set of problems that, in polynomial
time you'll be able to find the maximum cliques, with n cubed steps on the
average. It would look like P=NP in that because the maximum clique is one of
those NP complete problems. On the other hand, you know, you've got to be able
to solve all problems in a maximum polynomial number of steps in order to have
P=NP. Still, his algorithm might be really interesting on practical problems,
and so I've filed it away to read the code when I get to the point when, maybe a
year from now when I'm going to be writing up techniques for maximum cliques.

I've done my lifetime share of checking proofs that P=NP and P!=NP and some
years ago, I passed that threshold. So I'll never do it again. Still, there's a
pretty serious thing that a lot of people looked at about six months ago, wasn't
it? It turned out that it didn't pan out, but still the ideas couldn't be
dismissed out of hand.

Now, I've also read proofs about [squaring the
circle](https://en.wikipedia.org/wiki/Squaring_the_circle), too, in my youth.

To my surprise I've found that I had already given this opinion 15 years ago,
but I'm afraid what's going to happen in this question is that somebody maybe
50 years from now is going to prove that P=NP, and the proof is going to be
something like this: that it equals NP because there are only finitely many
reasons why it couldn't. [crowd laughs] In other words, a proof that could give
us no algorithm, it just proves that there exists some exponent, but an
algorithm that we'll never know is just out there. So then that was the wrong
question to ask. Now, we already have some cases like this. There're some deep
theorems in the [graph theory](https://en.wikipedia.org/wiki/Graph_theory) that
say certain kinds of graphs, in order to test for these graphs, you can do it
in polynomial time but nobody knows the algorithm. We just know that there's
only a finite number of cases to try for but we don't know what those cases
are. We just know that's not infinite. The paper by
[Lovas](http://www.cs.cmu.edu/~wlovas/) that describes some of the paradoxes
coming out of it. It's looking to me more and more like it's going to be that
the number of possible algorithms is huge huge, and to show that none of those
is polynomial time might just be wrong.

---

**Audience member:** Hi. I don't know if this touches more on philosophy, but
do you believe that programming is more of an [emergent
behavior](https://en.wikipedia.org/wiki/Emergence) of math, or it's its own
thing that just happens to be well described by math?

**DK:** Okay. Connection between programming and math, and emergent from math.
I find my own feeling is this: that mathematics and computer science are the
two unnatural sciences, the things that are man-made. We get to set up the
rules. It doesn't matter the way the Universe works. We create our own
universe, and decide we can design our computational models and we can make
axioms for mathematical problem. While physicists and chemists and biologists
and so on have a different thing. They want to know what's actually in the real
world. But are computer science and mathematics really two sides of the same
coin, or are they somehow different coins? I feel strongly that they're
different but I tried to convince [Bill
Thurston](https://en.wikipedia.org/wiki/William_Thurston) and he disagreed with
me.

My opinion though is I can feel rather strongly when I'm wearing my
mathematician's cloak versus when I'm wearing my computer scientist's cap. I'm
in one mode or the other, sometimes. To me, the biggest difference is
mathematicians are mostly working on unified theories where you have one or two
axioms that are sort of applying all the way through while, computer science
I'm more dealing with very heterogeneous things where there's case one, case
two, case three, and we have different things that happen in different status.
We have an assignment statement where we can just say X is placed by 2X. So all
value X is gone. Mathematicians, that's a weird concept to mathematicians. So I
think that these are different mentalities, different approaches where I can
sometimes say, "Well as a computer scientist, I got stuck here." Let me try to
translate into a mathematical one and then I think mathematically for a while
and that moves me to another thing. Then mathematically I'm stuck, and then I
go back and put on my programming hat again and try to do something
constructive or figure out a data structure that helps me understand the
mathematical of it. So, I think they're different but I can't convince Bill
Thurston.

The other thing that computer scientists... I can conclude this by saying we
got our pluses and minuses. So there are problems in the world that
mathematicians don't do very well at because they're sort of inherently
heterogeneous. Nothing uniform is going to explain them all. So mathematicians
aren't going to, couldn't be comfortable with that at all, and computer
scientists can cut through like butter. But on the other hand, there are
problems that do have a uniform thing and a computer scientist might not see it
because we can find a case one, case two, case three, a way to attack it which
is actually very inelegant and missing the underlying unity. So to me that's
the difference.

**Audience member:** Thanks.

---

**DK:**
> How has your involvement with music affected your computer science and vice
> versa?

I think there's a common thing about
[patterns](https://en.wikipedia.org/wiki/Pattern). It's a love of patterns that
seems to have a high correlation with the kind of thinking that goes on in both
mathematics and computer science. At Stanford, we had, one time our, the lady
who was sort of our department executive head, she had come from the law school,
and she said there was an incredible difference coming from the law school to
the computer science department. In music, the students were interested in
music, musicians. It was completely different than what she had experienced in
the other school. Anyway, I think there's probably something to that. Although
in the '70s we used to ask our incoming grad students the first question would
be "What's your instrument?" We had cases where, I don't know if you remember
Bill, Sam Vent, oral exam, he proceeded by a cello recital. We would have
student parties and we would do [chamber
music](https://en.wikipedia.org/wiki/Chamber_music). Much more in the '70s than
in the '80s, because one year I got to the incoming grad students and I said,
"What's your instrument?" It turned out that one guy played harmonica and
another one said that he did an Abba imitation, and nobody else did music at all
that year. I said, "Well what's you main hobby?" It turned out that more than
half of them were really into [bicycle
riding](https://en.wikipedia.org/wiki/Cycling). So there was a change somehow
in the population. I don't know why, and I don't know what it is now. Anyway I
do believe that these things go together, but it's maybe not a direct... If I
live long enough I'd like to compose some music with some of my algorithmic
ideas that I have. Maybe I could influence music that way. How does music
actually influence a program that I write? I don't know if I can point to
anything direct there.

---

Next question here was:
> You are famously known for your interest in (and contributions to) digital
> typography. Over 30 years after release of
> [TeX](https://en.wikipedia.org/wiki/TeX), what are your thoughts on the
> current state of typography as it exists on the web and other digital media?

Basically I'm upbeat about the way... I got a Nexus S and it has beautiful fonts
on it. I love the typography that I'm seeing. I think that people are starting
to understand fonts. I guess one of the only predictions that I, I'm famously
bad at predicting. In fact that's probably one of the, the fact that I can't
predict how hard something is, is the only reason that I started working on
typography in the first place. [crowd laughs] And *Art of Computer Programming*
and a bunch of other stuff. But I did predict that font designers would become
heroes and that turned out to be fairly close to the mark.

---

**Audience member:** So I have a question very similar to, like, one of the
previous questions. So, now kids are growing up with using computers like on the
cell phones, everywhere, like the small, small kids. But the computers became
really, really complicated. So what do you think will become the long term
impact. Will we have more people actually understanding how it all works, or
will we have magic, that only a few actually understand.

**DK:** This is a paradox and I wish I knew. I just gave you a couple of... So
I know that my grandkids are pretty fascinated by some applications that you
might say are fairly like programming and they put together objects and the
objects can move. I can't remember the names of the systems that they do. So
they're doing more than just passively playing games, although games are... I
must say I spent hundreds of hours rolling dice, and moving horses along a
track when I was in high school. Now the equivalent is doing things on them.

On the other hand, [Nick
Trefethen](https://en.wikipedia.org/wiki/Nick_Trefethen) told me three years
ago his son is going to the best high school in Oxford and Nick went there to
talk to the kids in his son's school and he found that not a one of them had
ever written a computer program or even thought about it. So, anyway it's a
very strange situation that we're in. And you'd think that more...

In the old days, people were learning
[Logo](https://en.wikipedia.org/wiki/Logo_%28programming_language%29) and
[Karel the
Robot](https://en.wikipedia.org/wiki/Karel_%28programming_language%29) and
stuff. Now there's many more systems like that which are quite fascinating.
You probably know the one called [ChucK](http://chuck.stanford.edu/) from
Stanford, and then [MIT has this one](https://scratch.mit.edu/about) that was
featured in the ACM last year, and there are more.

I don't know if it'll change. Throughout my career, the number of people, of
every hundred people, it's been pretty steady over my career that two out of
every hundred seems to be born to be a computer scientist. They're geeks like
me. We have a peculiar way of organizing stuff in our head and that happens
when you're young at some point. I view computer science as something that I do
because I just happen to be good at it, not because I had an urge to compute.

---

> Programming today is not fundamentally changed from programming decades ago.
> How has the industry failed in this regard and how could it change in the
> future?

I wish I could answer about industry, but my own expertise is in writing books
and I don't know.

---

> How many people have actually cashed the [$2.56
> checks](https://en.wikipedia.org/wiki/Knuth_reward_check)?

I think some of you know that I reward people for finding errors in my books. I
started that, it used to be one dollar back in 1960s and then in the second
edition it went up to two dollars. At some point it switched over to two dollar
fifty-six cents which seemed a more appropriate number. People used to cash
those checks a lot, and it fouled up our checking account. [crowd laughs] So I
got my own account because others were not cashing.

Well, now it turns out that the electronic funds transfer is incredibly
insecure. Banks have almost no security. I mean, the banks believe any
electronic message that they get. Crooks have learned how to do this, so that
if somebody looks at a check that you write, you write the personal check that
has numbers at the bottom, if a clerk knows those numbers, he can turn himself
up an [ATM](https://en.wikipedia.org/wiki/Automated_teller_machine) card and
withdraw money from your account. Anyway, I had to close three accounts because
these numbers... I have examples where the check says "Bank of America Atlanta,
Georgia", and at the bottom, it has [routing
number](https://en.wikipedia.org/wiki/ABA_routing_transit_number) of my
checking account in Palo Alto. It would look like a payroll check and so, four
hundred bucks, cash it at the supermarket. But others were actually, as I said,
making ATM cards and doing withdrawals and ordering all kind of fancy computers
and stuff, I think probably somewhere in Eastern Europe. This whole banking
system is all screwed up.

So about four years ago I started my own bank and you can find it on the web,
it's called [The Bank of Sans
Seriffe](https://www-cs-faculty.stanford.edu/~knuth/boss.html) [crowd laughs]
and I still write checks, but you don't cash them because it doesn't say "pay
to the [...]", it says "Deposit to the account of [...]" and it's a virtual
bank so you can look on there and you can find the names of everybody who's got
an account at the Bank of Sans Seriffe and how much they've done.

I wrote 21 of those checks last month and I'll write probably 10 this month so
far from what I know, things that came in. Last week, I got a letter from
China. A guy found an error in volume one from 1960, it hadn't been noticed
since 1968. Finally somebody read that page carefully. It's true. So, it's very
valuable to me, you know, trying to make these books more and more correct.

---

> What do I think is the most effective way to get children enthused about
> computer science?

I guess we got good tools for them to play with, but I was best at understanding
children when I had children who are that age. When my kids were in first grade
I could design [curriculum](https://en.wikipedia.org/wiki/Curriculum) for first
graders and then the next year I could design curriculum for second graders.
Right now, that's wiped out of my head.

I think part of it is they have to have a way to be creative and share their
creations with their friends. So that's probably going to be the most effective
way: have some kind of things where kids can make a construction that they're
proud of.

---

> Did Steve Jobs tell you he'd read all of your books and how did you respond?
> Bye.

Okay. Now, there's a funny story about that you can look up. The true story I
believe is on the [Russian version of the
Wikipedia](https://ru.wikipedia.org/wiki/%D0%9A%D0%BD%D1%83%D1%82,_%D0%94%D0%BE%D0%BD%D0%B0%D0%BB%D1%8C%D0%B4_%D0%AD%D1%80%D0%B2%D0%B8%D0%BD).
Because the guy in Russia wanted to check out the source. The fact is that I met
Steve several times and the most likely thing is that he said that I said, "Oh,
that's wonderful. You're the first person I ever met who has," or something
like, has read them all. Anyway, I defer the rest of the story.

You got a question?

---

**Audience member:** So, are you familiar with the field of [natural language
programming](https://en.wikipedia.org/wiki/Natural-language_programming), or,
sorry, [natural language
processing](https://en.wikipedia.org/wiki/Natural_language_processing)?

**DK:** Natural language processing. Well, I use [Google
Translate](https://translate.google.com) an awful lot. [crowd laughs] I know a
little bit about the way it works.

**AM:** So from what little you know, do you see it having any effect on the
field of literate programming, or programming in general?

**DK:** No. Well, it sounds to me like a different... It's certainly a huge
impact on artificial intelligence and a lot of algorithms and a lot of the
algorithms that are used in order to deal with things that are... I've always
looked for a way of getting automatic translate so that I wouldn't have to use
a dictionary. I only had to learn a dialect of English when I'm dealing with
things from other languages. This seems to be happening now. I haven't got
anything profound to say about it.

**AM:** Thank you.

**DK:** A friend of mine gave me a wonderful book. They started out with [*Alice
in
Wonderland*](https://en.wikipedia.org/wiki/Alice%27s_Adventures_in_Wonderland),
and translated it by machine into French, and then translated that into English
and back into French until they had a stable thing. [crowd laughs] After two
cycles you get the same thing back again. Then they printed the whole thing
into a stable form. The rabbit is saying, "Oh, precious," instead of, "Oh,
dear."

---

**Bill Coughran:** Could I? I'm going to interject here. I'm going to take the
liberty of asking the last question. So, you know, years and years ago when I
was studying computer science, there was a lot more expectation for
mathematical training, and I noticed over the ensuing 30 or 40 years that
there's less and less dependence on mathematics, and my impression is that
students are less trained in that. I remember it was very controversial at
Stanford for a number of years about whether to have an undergraduate degree in
computer science and so forth. I think there was a presumption that people
should have mathematics training before they went into computer science. How
has computer science changed as the role of mathematics has become less in the
field? I'd be interested in your view.

**DK:** Another great question. All of these questions have been really
terrific. There's a lot of good computer science that can be done without a lot
of mathematics now. But there's just as many examples of really cutting edge
mathematics going into computer science as well. I mean, I just go through our
building, [computer graphics](https://en.wikipedia.org/wiki/Computer_graphics),
all the [rendering
methods](https://en.wikipedia.org/wiki/Rendering_%28computer_graphics%29) that
are heavily based on mathematics, and the [new camera
techniques](https://en.wikipedia.org/wiki/Computational_photography) are
incredible. People are using high mathematics in artificial intelligence, all
of the [Bayesian network](https://en.wikipedia.org/wiki/Bayesian_network), the
calculations with [robotics](https://en.wikipedia.org/wiki/Robotics) are
requiring great mathematics.

I don't think however that I need a terrific amount of mathematics to come up
with Facebook. Still I understand the way Facebook is able to do its magic is
by actually putting everybody's Facebook page in one giant computer, a certain
mathematic knowledge in order to understand caching and so, yeah, but not
traditional mathematics. Mathematical
[paradigms](https://en.wikipedia.org/wiki/Paradigm) are still there. You have
to know the concepts of [rigorous
proof](https://en.wikipedia.org/wiki/Mathematical_proof) for at least half of
computer science now, I would say. But there's also lots of other things that
are... When we talk about the design of
[GUIs](https://en.wikipedia.org/wiki/Graphical_user_interface) or something
like that where you don't need so much to many theorems.

**BC:** That's true. I've heard a few people say that reading your
books, *The Art of Computer Programming* is challenging if you don't have the
right mathematics background, which I think is true.

**DK:** It's not easy to read my books, but it could be a lot harder. [crowd laughs]
I tried to make them as simple as possible but I haven't succeeded in making it
a breeze.
