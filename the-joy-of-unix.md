# The Joy of Unix

[Sun Microsystems](https://en.wikipedia.org/wiki/Sun_Microsystems) co-founder
[Bill Joy](https://en.wikipedia.org/wiki/Bill_Joy) charts where Linux and free
software fit into his company's solar system.

by Eugene Eric Kim

[Linux Magazine, November 1999](https://web.archive.org/web/20050207084053/http://www.linux-mag.com/1999-11/joy_01.html)

---

## Contents
- [Introduction](#introduction)
- [Licensing](#licensing)
- [Community](#community)
- [vi](#vi)
- [Desktop Unix](#desktop-unix)

---

## Introduction

As one of the creators of Berkeley [Unix](https://en.wikipedia.org/wiki/Unix),
Bill Joy knows a thing or two about developing and marketing a free operating
system. Sun Microsystems' chief scientist has survived the [Unix
wars](https://en.wikipedia.org/wiki/Unix_wars) and has watched both his company
and its chief competitor, Microsoft, grow from tiny start-ups to industry
giants. Though he has had a major hand in the development of such important
Unix technologies as NFS (Sun's Network File System), the Berkeley Unix TCP/IP
stack, and the vi text editor, Joy's current obsession is trying to build a
thriving development community around Sun's Jini distributed computing
technology and its not-quite-Open Source software licensing model. Joy recently
accepted Linux Magazine's invitation to dinner, where he gave Publisher Adam
Goodman, Executive Editor Robert McMillan, and Associate Editor Eugene Kim the
lowdown on what Sun thinks of Linux and Open Source.

---

## Licensing

**Linux Magazine:** One of the reasons we wanted to talk to you was that you
have a long history with and a broad perspective on Unix and free software.
What do you think of [Linux](https://en.wikipedia.org/wiki/Linux)? A lot of
people talk about it as more than just an operating system.

**Bill Joy:** It's actually less. It's just a kernel if you want to be
technical about it. It's politically incorrect to conflate Linux with the
applications. At least one person will get upset. So to be quite precise, it's
just the kernel of the OS. When we did Berkeley Unix, we were doing the
operating system and all of the applications.

In a lot of ways, the [Berkeley Systems Distribution
(BSD)](https://en.wikipedia.org/wiki/Berkeley_Software_Distribution) was on the
road to being free with source available and many of the things that Linux is.
But it got hung up in this legal fight between the University of California and
Unix Systems Labs.

Those are the accidents of history. Now with Linux, we have this new version of
Unix written with similar kinds of values that BSD had. One of the great
strengths of Unix is that it's been rewritten and reimplemented several times.
Applications with similar names and similar functions are widely understood,
which allows this healthy kind of invention and reinvention to occur.

**LM:** So if it weren't for the lawyers, we'd be called
[FreeBSD](https://en.wikipedia.org/wiki/FreeBSD) Magazine?

**BJ:** If BSD had been free, there would have been no reason to rewrite it.
The new thing that happened with Linux was cultural. The Internet is now
coupling people together in ways that probably couldn't have happened before.
How else would the developers have found each other?

I did my work in the era of the magnetic tape. We sent Unix in source form to
thousands of people; they sent us a few hundred dollars, because I had to pay
for the postage and for the printing of the manuals, and that was our network.
It was a postal-age speed thing. It was not very convenient.

**LM:** Were licensing issues as important back then as they seem to be now?

**BJ:** No. I knew I needed a license for BSD because at some point Berkeley
was going to discover it. So I just took a license from the University of
Toronto and modified it a little bit and started using that. I figured if I
sent people a tape, and there was nothing for them to sign, they wouldn't take
it seriously.

When you give things away for free, often people think that's what it's worth:
Nothing. So charging them a small amount and giving them a license to sign
actually created a perception of value. I'm not saying the tape didn't have
value, but an awful lot of stuff comes across your desk that you just throw
away.

**LM:** So, what did your license actually say?

**BJ:** I don't remember. It was a one-page thing. I didn't have any lawyers
look at it and I'm not a lawyer. I just made it up as I went along.

What happened was that at some point we were getting to be big enough that we
were sending out hundreds of these [Unix tapes] a year and charging hundreds of
dollars for them. A quarter of a million dollars in revenue is a great deal of
money for a graduate student. Scott McNealy likes to say: "To ask permission is
to seek denial." And we were operating with that philosophy.

But there were huge amounts of money involved and we were becoming pretty
visible. So eventually we decided to send
[AT&T](https://en.wikipedia.org/wiki/AT&T) a letter asking them: "Is this okay
what we're doing?" And 18 months later they sent a letter back: "We take no
position." We won't answer your question. So that's what it was like to deal
with a regulated monopoly of lawyers. That same sort of legal structure is what
caused [AT&T] to license the transistor for nothing.

So we couldn't actually get an answer from them and it was only years later
that this whole fracas erupted around who owns the code. It turned out their
code was as tainted with Berkeley stuff as ours was with theirs, so they
eventually came to a truce. That's what I've heard second hand or just drinking
wine with people. So there's a very tortured and funny history to all this
code.

**LM:** Have you ever contemplated what it would have been like if you'd
released your code under the [GNU Public License
(GPL)](https://en.wikipedia.org/wiki/GNU_General_Public_License) or something
similar?

**BJ:** I don't see what the advantage to it is. The important thing is that
people have the source code. I actually think it's fine that people can take
BSD and make improvements to it and reap software profit.

I don't think, given where we were and what we were trying to do, that the
license made that much of a difference. At Berkeley, we had the model that
software is the result of your research. The university tradition is that when
you do research, you publish. So not giving people the source code for software
meant that you weren't publishing your research. A fundamental model of BSD
was: Software is a result of our research. We'll publish it and other people
will use it if they choose. If someone commercializes it, I don't particularly
care, because if you publish research in a university, people can commercialize
it. That's just the way it is.

The important thing in my mind is that people share stuff. We've done something
at Sun -- [Community Source
Licensing](https://en.wikipedia.org/wiki/Sun_Community_Source_License) -- which
is another spin on this. But the fundamental principle in my mind is that
people get to see the results of other people's work in a way that they can
stand on shoulders rather than on toes. The details can vary; there can be many
approaches and they work in different contexts.

I think the GPL is fine. I just don't necessarily agree that it will achieve
everything that [Richard
Stallman](https://en.wikipedia.org/wiki/Richard_Stallman) thinks it will. I'm
not as religious about this as other people are.

**LM:** Just what was your involvement with Sun's Community Source License?

**BJ:** I was the instigator of it.

**LM:** Did you at any point evaluate the GPL for Sun's projects?

**BJ:** I can't license all of Sun's intellectual property under the GPL,
because it just won't work. I don't see any reason why I should give somebody
who's doing commercial reuse unfettered access to stuff that cost me millions
of dollars to do. We're spending over a billion dollars a year in research. I
can't just throw it all on the street. Not only because it's worth something,
but because I'm not convinced people will respect its values -- the values I
would want to see expressed in the way people used it.

If I make code available under the GPL, I'll lose control of it. The Europeans
have this notion of artistic rights, and it seems to me an artist -- the person
who creates something -- has some right over the ultimate use of what they do.
Artists' rights also allow an artist to get paid on resale of their stuff
later. My view is that programmers are like artists. I think there's got to be
some economic reward back to the people who do the creative work that turns out
to matter.

The GPL just doesn't solve my business problem at Sun. I would like all of our
intellectual property to be available in source form, but I can't economically
do that under the GPL.

In the
[object-oriented](https://en.wikipedia.org/wiki/Object-oriented_programming)
world [of programming], binaries are almost as usable as source because they
have clean interfaces and boundaries. This whole thing about open source makes
much less sense once you start talking about [object-oriented programming
languages like]
[Java](https://en.wikipedia.org/wiki/Java_%28programming_language%29), except
to the extent that people don't get the boundaries right.

**LM:** What about your original implementation of
[TCP/IP](https://en.wikipedia.org/wiki/Internet_protocol_suite) for BSD, which
was freely available and which became the basis for a lot of the other
implementations that are out there? It seems that from a compatibility
standpoint, Java, for example, would have benefited from freely available
source code in the same way TCP/IP did.

**BJ:** The top predator now is
[Microsoft](https://en.wikipedia.org/wiki/Microsoft). We didn't have a top
predator back when I did TCP/IP. When you have a person with unlimited funds
who is clearly focused on destroying the value proposition of what you're
doing, you'd be a fool not to account for them in the strategy that you
adopted.

**LM:** Do you feel that Microsoft might actually try to create Microsoft Linux
in an attempt to fragment the Linux community?

**BJ:** The enemy in terms of fragmentation is usually yourself -- the people
who know the most about making the software better. It's likely to be two
separate groups that both decide that they're right and they're both going to
make it better and just diverge. You've seen the history of the family tree of
Unix. It's all over the map. It's certain to happen to the Linux tree at some
point.

**LM:** Then why hasn't it happened already?

**BJ:** It has. Depending on what we'd say Linux is -- the kernel hasn't
fragmented, but the distributions have. People's systems aren't the same.

**LM:** Do you think that the GPL discourages incompatibility by requiring
people to make their source code freely available?

**BJ:** I don't see that it really prevents incompatibility. The only thing I
know that prevents incompatibility is requiring people to be compatible. The
GPL permits compatibility. It does not encourage it.

**LM:** Can you explain Sun's position toward Linux on
[Sparc](https://en.wikipedia.org/wiki/SPARC)? Sun seems to be supporting the
development effort somewhat.

**BJ:** Right. Well, the customer's always right. If the customer wants Linux,
that's great -- then we should give it to them. Sparc is the hardware that we
make, and we're supportive of and very glad that people in the Linux community
have done the hard work that they need to do.

We treat each of our divisions as entirely separate businesses, and I don't
necessarily know what's going to be important in the long run. People have now
figured out that companies that are a little more chaotic in this way actually
are better adapters to environmental changes, and I think it's one of the
reasons Sun has done so well. We don't try to get everybody signed up to one
credo. We do not have one ironclad set of rules. We allow this kind of
diversity internally.

**LM:** Sun is providing machines for Linux developers. What else is it doing
to support Linux?

**BJ:** I don't actually know. I'm more involved in Java and
[Jini](https://en.wikipedia.org/wiki/Jini). The company's very large -- we have
like 30,000 people -- and I probably get involved with about half of the R&D.
The [Solaris](https://en.wikipedia.org/wiki/Solaris_%28operating_system%29)
stuff I have the least to do with.

Sun wins if somebody has a Linux machine with Java because that improves the
Java community. Sun wins if it's a Sparc. That's even better. To be honest, if
it was Solaris, Sparc, and Java, that would be even better. But we're not
infinitely greedy here.

The old [Macy's](https://en.wikipedia.org/wiki/Macy's) model was if they didn't
have what you wanted, they'd send you to the store that did, even if it was a
competitor. If you come to us, we don't expect that we're going to solve all of
your problems. You may want
[Apache](https://en.wikipedia.org/wiki/Apache_HTTP_Server) on Linux on
[x86](https://en.wikipedia.org/wiki/X86), and we'll do the best to operate in
that environment because there may be some reason that's beyond our ability to
affect that that's the right answer for you.

So to be customer-driven is to accept that and to contribute what you can. We
just did this big deal with Apache to put more Java stuff in Apache. So we're
coming at it from all directions.

**LM:** You're referring to the [Jakarta
project](https://en.wikipedia.org/wiki/Jakarta_Project), where Sun agreed to
donate its [JavaServer Pages
(JSP)](https://en.wikipedia.org/wiki/JavaServer_Pages) and other Java Web
server-related source code to the [Apache
project](https://en.wikipedia.org/wiki/The_Apache_Software_Foundation) and have
it released under the [Apache
license](https://en.wikipedia.org/wiki/Apache_License).

**BJ:** That was a local business decision; I'm glad that they did that.

**LM:** But you still have the same concerns about standardization,
compatibility, and so forth?

**BJ:** Which I think the Apache community should have also. To the extent that
Apache is a platform, and you want to have it be a healthy platform, you want
the platform to be stable. But, I'm not opposed to limited cases depending on
other licensing mechanisms.

I would always rather have a legal thing to fall back on to enforce
compatibility. Think of contractual enforcement as sort of the right-wing
approach, and community licensing as more left-wing. We've taken a step to the
center. We expect in most cases the community to enforce compatibility, but in
the limited case of a rogue, I want the ability to enforce a legal contract,
because I don't see any reason why I shouldn't have that ability. In the left
wing, amongst ourselves, we can argue about these things, but in reality, most
of the commercial guys are so far to the right that we already seem radical by
being in the middle.

It's innovation and sharing versus centralized control. It's basically the
Romans versus the Greeks. That's what it comes down to. Microsoft is the Roman
model, and the other people are basically the Greek model. That's the real root
of it.

**LM:** Isn't that the same situation with Java? With Jini?

**BJ:** No. Because the Java source code has always been widely available.
That's never been the issue. You can download it yourself. Even under the old
license, we basically had a clickable license to download all this stuff.

Basically, we think that it's much better to work together than to not work
together. That's not a very complicated value. Microsoft thinks: "anything you
do, you compete with us." I think that if you don't necessarily like what we
do, we'll find some other way to work together. There are not enough of us IT
professionals anyway.

**LM:** Speaking of Microsoft, have you ever meet [Bill
Gates](https://en.wikipedia.org/wiki/Bill_Gates)?

**BJ:** Oh yeah. Mostly in the eighties. I met him in the early 1980s.

**LM:** So would you consider him someone you know fairly well personally?

**BJ:** No. That would be a stale evaluation of him.

**LM:** So you believe he's changed?

**BJ:** I believe it's possible that he has so I can't speak to his current
state. I haven't seen him since -- the last time I talked to him was probably
five years ago.

**LM:** Is Linux the major force pushing against Microsoft?

**BJ:** I think Java is probably the major force pushing against Microsoft
right now. I think Linux is a threat but Java's a bigger threat.

**LM:** Do you see Linux as a threat to Sun at all?

**BJ:** No. More Unix is better. Anything that isn't Microsoft is better.
Anybody who buys a Linux machine has a lot better chance of buying a Solaris
machine as their next machine or buying a Sparc machine running Linux or buying
Java. The probabilities are greater for all those cases.

If I look at the graph of what percentage of customer dollars I'm likely to get
next, it's much higher if they start with Linux than if they start with
[Windows](https://en.wikipedia.org/wiki/Microsoft_Windows). So in all cases,
I'd rather win and get Sparc/Solaris/Java as the solution. But Linux/Sparc/Java
would be my second choice.

**LM:** Do you know of a company named [VA Linux
Systems](https://en.wikipedia.org/wiki/Geeknet)?

**BJ:** I met somebody who said they were working for them. I don't track the
Linux community, though.

**LM:** What do you think about the business models being built around Linux?

**BJ:** I understand that people think they're going to build a business on the
service model, but the truth is customers don't want to pay for that, so I
don't get it. I don't know how it's going to work. People don't like to pay for
service.

The whole proposition with Linux is that nobody can control the operating
system. Some invisible hand controls it a community controls it. Any
individual company can't affect where it goes. How is everybody going to use
this in a sense? The Linux companies are hobbled by it because if you say they
can add value, then I say it's going to fragment Linux.

If you accept the proposition that they can't fragment it, then you also are
saying that they can't really differentiate themselves. Because other than
tuning it up a little bit, to differentiate would cause fragmentation.

I would argue that for most people the performance is going to be more than
they're going to need anyway. I'm not sure performance differentiation is going
to be that significant. So I'm not exactly sure how these companies will
differentiate themselves technically.

**LM:** Have you ever considered making the Solaris source code more freely
accessible?

**BJ:** Yeah. The difficulty is that it's got a lot of third-party stuff that's
licensed under funny terms. So I think it will be really healthy for both the
Solaris and Linux communities to work more closely together.

**LM:** Think that will ever happen?

**BJ:** It already is. We run a lot of Linux binaries, and we're trying to find
ways to work together. Merging isn't a goal. I think Linux and Solaris have
different goals. Linux is not worried about providing
[MVS](https://en.wikipedia.org/wiki/MVS) class or
[VM370](https://en.wikipedia.org/wiki/VM_%28operating_system%29) or whatever
[IBM](https://en.wikipedia.org/wiki/IBM)-class services for corporate data
centers. That's not the center of the Linux community.

**LM:** But there are certainly areas of overlap.

**BJ:** That's okay. It gives people a choice, and that's not a bad thing,
right? I still prefer to win. I'm not saying we're not competitive, but I'd
still rather have it be Linux than
[NT](https://en.wikipedia.org/wiki/Windows_NT). If there's two Unix choices and
one Microsoft, that improves our chances.

**LM:** Do you think it's likely that parts of the Solaris operating system
will be individually released as open source software?

**BJ:** I think that would be a good thing. There are logistic issues. You have
to spend money to do that and it's hard work. In return, you get the value that
the source code's available so the customer can become more self-reliant. I
think self-reliance is a good thing.

**LM:** Were you in favor of Sun's decision to move to AT&T Unix with Solaris?

**BJ:** It was hard to do a deal with AT&T and it was hard to work with them.
It was a very close call and I went into Scott's office and I said to him: This
is a really close call and I can make the deal happen if you want. There are
pluses and minuses. Personally I think it's a plus because I think a unified
Unix community is better than one that's not, and I'm concerned about this. But
I also think it would be okay if we decide to go our own way. It's your call.
It's a CEO call.

## Community

**LM:** Do you see similarities between the development community and the
cultural community that's surrounding Linux right now and the community that
surrounded BSD when you were developing it?

**BJ:** No. Our community was so small. It was [Robert
Elz](https://en.wikipedia.org/wiki/Kevin_Robert_Elz) and the people at
[Berkeley](https://en.wikipedia.org/wiki/Computer_Systems_Research_Group) and
the people at [Bell Labs](https://en.wikipedia.org/wiki/Bell_Labs). There was
one guy in Austria and one in Australia. No one else contributed much of
substance that I recall.

**LM:** Do you believe that the BSD guys in general have a different philosophy
toward software development than the Linux guys do?

**BJ:** No. I think that if you exclude device drivers, you'd find that there's
a bit of a myth operating here; that a whole lot of people wrote the system. It
was actually a small number of people.

**LM:** In BSD or in Linux?

**BJ:** Both cases. We have this myth that distributed development works, but
it's a slight bit of a lie in that a small number of bright people can create
an operating system. It does take a lot of people to write all of the device
drivers. That's true. But that doesn't necessarily mean we can coordinate the
programming of hundreds of people writing [C
code](https://en.wikipedia.org/wiki/C_%28programming_language%29). I don't know
if that's true or not, and I personally don't think Linux proves it. I don't
think Apache proves that. That's the myth that people have propagated. Maybe
it's true, but if you called me as an expert witness, I would testify that it
has not been true in my experience.

**LM:** Is there something to the notion that the people working on BSD are
more exclusive than the Linux community?

**BJ:** That's an us-versus-them thing. These things just get amplified. I
don't think these people vary from each other by much. They just identify with
some group, and that's a human-nature thing.

BSD is older. It doesn't need as much hacking. So if you're a new person
learning how to hack, BSD was not as good a place to go. It didn't need as much
work. Linux grew up with the Internet. By the time the Net came along, BSD
didn't need the same level of work and wasn't as amenable to getting people
interested in it.

When you already have several million lines of code, it's not as much fun to
work on. Linux was a great thing because it allowed a lot of people to get
involved in learning about operating systems by helping to finish this system.
That process of creating something is the process of creating a community.

So Linux came along at the great, perfect time in a perfect, incomplete state
for lots of people to participate in. It was still small enough that people
could read the code. On the other hand, BSD was already mature, and the things
that needed to be done to it were hard enough that it made it difficult for any
person to come and participate.

So BSD wasn't as amenable to parallel innovation because the bar to
participating was pretty high and the code base was too large. When I started
on Unix, the source code could be listed in ten or twenty thousand lines as a
50-page or 100-page book.

If I came in today and wanted to do something with Solaris, I'd be overwhelmed.
I can't have the kind of impact I had on Unix with Solaris. The
second-generation people coming into the Linux community are going to have the
same problem.

## vi

**LM:**: What inspired you to write [vi](https://en.wikipedia.org/wiki/Vi)?

**BJ:** What happened is that [Ken
Thompson](https://en.wikipedia.org/wiki/Ken_Thompson) came to Berkeley and
brought this broken
[Pascal](https://en.wikipedia.org/wiki/Pascal_%28programming_language%29)
system, and we got this summer job to fix it. While we were fixing it, we got
frustrated with the editor we were using which was named
[ed](https://en.wikipedia.org/wiki/Ed_%28text_editor%29). ed is certainly
frustrating.

We got this code from a guy named [George
Coulouris](https://en.wikipedia.org/wiki/George_Coulouris_%28computer_scientist%29)
at University College in London called em -- Editor for Mortals -- since only
immortals could use ed to do anything. By the way, before that summer, we could
only type in uppercase. That summer we got lowercase ROMs for our terminals. It
was really exciting to finally use lowercase.

**LM:** What year was that?

**BJ:** '76 or **'77**. It was the summer
[Carter](https://en.wikipedia.org/wiki/Jimmy_Carter) was president. So we
modified em and created en. I don't know if there was an eo or an ep but
finally there was [ex](https://en.wikipedia.org/wiki/Ex_%28text_editor%29).
[laughter] I remember en but I don't know how it got to ex. So I had a terminal
at home and a 300 [baud](https://en.wikipedia.org/wiki/Baud) modem so the
cursor could move around and I just stayed up all night for a few months and
wrote vi.

**LM:** So you didn't really write vi in one weekend like everybody says?

**BJ:** No. It took a long time. It was really hard to do because you've got to
remember that I was trying to make it usable over a 300 baud modem. That's also
the reason you have all these funny commands. It just barely worked to use a
screen editor over a modem. It was just barely fast enough. A 1200 baud modem
was an upgrade. 1200 baud now is pretty slow.

9600 baud is faster than you can read. 1200 baud is way slower. So the editor
was optimized so that you could edit and feel productive when it was painting
slower than you could think. Now that computers are so much faster than you can
think, nobody understands this anymore.

The people doing [Emacs](https://en.wikipedia.org/wiki/Emacs) were sitting in
labs at MIT with what were essentially fibre-channel links to the host, in
contemporary terms. They were working on a
[PDP-10](https://en.wikipedia.org/wiki/PDP-10), which was a huge machine by
comparison, with infinitely fast screens.

So they could have funny commands with the screen shimmering and all that, and
meanwhile, I'm sitting at home in sort of World War II surplus housing at
Berkeley with a modem and a terminal that can just barely get the cursor off
the bottom line.

It was a world that is now extinct. People don't know that vi was written for a
world that doesn't exist anymore -- unless you decide to get a satellite phone
and use it to connect to the Net at 2400 baud, in which case you'll realize
that the Net is not usable at 2400 baud. It used to be perfectly usable at 1200
baud. But these days you can't use the Web at 2400 baud because the ads are 24
kilobytes.

**LM:** Do you still use vi?

**BJ:** No, because I mostly use
[Netscape](https://en.wikipedia.org/wiki/Netscape_%28web_browser%29).

**LM:** To write code?

**BJ:** I mostly do e-mail. The last code I wrote of any substance, I wrote in
vi.

**LM:** Did you have a sense back in those days -- even in the furthest region
of your mind -- that you were working on something that would eventually build
an industry or change the world?

**BJ:** No.

**LM:** At what point did it occur to you? At what point did you look around and
say: Whoa?

**BJ:** I probably constantly under-estimated it.

**LM:** You must have realized that it was happening at some point in your
career.

**BJ:** I think the Web was a "wow" for me because my dad was using it.
[laughter]

## Desktop Unix

**LM:** You said earlier that Sun would like to work more with the Linux
community. Do you have any thoughts on how something like that might happen?

**BJ:** We have Linux mode on Solaris and there's Solaris mode on Linux. We've
done analysis on both sets of APIs and what commonality they have. If the Linux
community believes it's okay for there to be other choices, then that's kind of
a prerequisite to working with somebody who's different. It's okay that there's
another version of Unix out there and total world domination is not our goal.

**LM:** Are there opportunities to do things with Linux that Sun was never able
to do as a company? For example, Unix never got the desktop. Or at least, Sun
was never really able to bring Unix to the desktop.

**BJ:** That was our whole business for years.

**LM:** Right, but Microsoft owns the desktop right now. It's not meant as a
cut against Sun. It's just a fact that Unix is basically a server operating
system.

**BJ:** We haven't given up. We're doing Java clients now.

**LM:** Why do you think that Unix was never successful on the desktop?

**BJ:** Because Microsoft had a person who was very greedy and who was very
brutal in his business dealings and was handed a monopoly by IBM due to
ineptness. They had several opportunities to rein this guy in and the
management blew it. So the IBM monopoly got transferred basically due to
blunders. Microsoft is a direct successor to the IBM mainframe monopoly. The
corporate guys coalesced around the PC standard because it came from IBM. Not
because it was any good.

**LM:** But does something like Linux offer Sun an opportunity to rectify past
mistakes? For example, there are windowing systems being developed for Linux
that need ...

**BJ:** We've had windowing systems, several of them, for many years. The
presence or absence of a windowing system didn't win or lose the war. We have
had [CDE](https://en.wikipedia.org/wiki/Common_Desktop_Environment) and [Open
Windows](https://en.wikipedia.org/wiki/OpenWindows) and
[X-Windows](https://en.wikipedia.org/wiki/X_Window_System) and
[NeWS](https://en.wikipedia.org/wiki/NeWS).

We've had applications too. We've had all of these things. I suggest that the
desktop war was not won based on technical merit, but on business decisions.
Microsoft came along and took over the apps base with
[Office](https://en.wikipedia.org/wiki/Microsoft_Office). Office locked people
in to the point where corporation don't feel they can change their desktops,
not because they're locked to Windows but to Microsoft Office.

Now what's happening is the wind is blowing hard for the companies to put
everything on the Net. Make the browser the access point for the desktops. So
the desktop is really becoming a browser. But the people -- the companies --
still have these Microsoft Office hairballs that nobody likes. Have you seen a
good review of Office 2000? Everybody hates it. But Office is what locks up the
desktop.

**LM:** There is a lot of talk about Linux possibly conquering the desktop.

**BJ:** It's easier to talk about than to do. The
[Macintosh](https://en.wikipedia.org/wiki/Macintosh) is easy to use, and it
even has Office. What's the difference between Linux and a Macintosh? If Linux
with future apps is going to be good enough, why aren't more people buying
Macs?

**LM:** You think this is a fight that's already been fought, basically?

**BJ:** No, I'm not saying you can't find a way to win. It's just that I
haven't heard what it is. Given a sufficient number of people who care and an
ability to be flexible about the way you achieve your objective, Linux might
get there. You have to find a way around some of these things that are
preventing people from switching.

These guys at Microsoft are very aggressive business people, and they have been
very successful as aggressive business people. I don't think they've been very
successful at building good products. I think history will judge their products
to be the lowest-quality consumer products ever built and manufactured in any
scale.

It's similar to how Detroit got itself to where they manufactured incredibly
low-quality cars, which coincided in history with
[GM](https://en.wikipedia.org/wiki/General_Motors)'s maximum market share. What
happens is monopolists don't tend to value product quality. Very high market
share is what they value.

As GM's market share was declining, it always talked about getting back market
share. Why didn't they talk about making products that people wanted to buy
that were high quality? That was the problem. I heard [Steve
Ballmer](https://en.wikipedia.org/wiki/Steve_Ballmer) [President of Microsoft]
say this in a speech: "Our number one goal is maximizing our market share."
Excuse me. Market share should be a consequence of your goal. That can't be the
goal.

The goal is to build great products. I have an infinite respect for Steve Jobs
because whatever else you say about him, his passion is to build a great
product. Good things come from that. Bad things come from a focus on market
share. So the Linux community should have as its goal to build the greatest
operating system. Its goal should not be, "Beat Microsoft." Because that's a
market-share goal. That's a very, very destructive, counterproductive goal.

**LM:** Do you think there are any other goals the Linux community should
pursue?

**BJ:** Make it the best product it can be. Figure out who you want it to be
for and build it to serve that community -- if it's for yourself, that's okay.
Make it the best hobbyist -- in the best sense of the word -- operating system.
Linux to me is like [amateur
radio](https://en.wikipedia.org/wiki/Amateur_radio) was to radio. Amateur radio
developed all the radio technology. Linux is developing some good technology,
and these people are hobbyists. Probably some Latin root of the word "hobbyist"
means people who love something and care about it. So it's a sense of love and
caring for reasons that are noneconomic.

It's like [amateur
astronomers](https://en.wikipedia.org/wiki/Amateur_astronomy). In essence, it's
amateur in the highest sense of the word, having the highest affinity to caring
that it's always the best. And tinkering and all this kind of stuff, that's a
very positive value.
