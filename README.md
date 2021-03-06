<!-- -*- mode: markdown -*- -->

corpus-iuris
============

Resources for the study of Roman and canon law...

Think of the files associated with this project as being under
continuous development: they are ever-changing,
[org-mode friendly](http://orgmode.org), versions of the main texts
pertaining to classical Roman and canon law along with various related
'tools'.  Many more texts await their conversion to plain text, but
this is what I know of for now.

I used `org-mode` because I primarily use
[GNU Emacs](https://www.gnu.org/software/emacs/) when I interact with
text files, and `org-mode` is reason enough to use Emacs.  For large,
but structured documents, `org-mode` is great because it lets you
toggle the visibility of sections and subsections of texts, so you
can, e.g., show only the main sections of a file (say, only the titles
of the file codex-01.txt).  If you don't know what I'm talking about,
trust me when I say that you're missing out; but you can compare the
three screenshots if you want to get a sense of what I mean.

Regardless, until you make the switch yourself, note that `org-mode`
files are usually still plain ASCII or UTF-8 (or, I suppose, your
encoding of choice), which means if your operating system and/or text
editor doesn't know how to handle an `.org` extension, just change it
to `.txt` and all will be well.  (But, really, just use Emacs: it
makes dealing with these kinds of large text files *much* more
convenient!)


## Canon Law

### Decretales (Liber extra)

Source: [Decretalium Gregorii papae IX compilationis libri V](http://www.hs-augsburg.de/~harsch/Chronologia/Lspost13/GregoriusIX/gre_0000.html)

The texts are based on the version of the *Liber extra* as it is found
on the Biblioteca Augustana website, which includes other texts of
[Gregory IX](http://www.hs-augsburg.de/~harsch/Chronologia/Lspost13/GregoriusIX/gre_intr.html).
I downloaded these texts several years ago, and I include in the
belief that the raw text of the *Decretales* surely belongs to the
pubic domain by now.


## Roman Law


### Latin

Source:  [The Latin Library](http://thelatinlibrary.com/ius.html)

I downloaded these texts from the source above an uncertain number of
years ago, and converted them into plain text at different times in a
variety of ways.  Depending upon what I am working on, these texts are
'improved' in greater and lesser ways at varying rates.  It is
believed that the original HTML versions are in the public domain, and
are therefore available for modification.

Note that I rarely have occasion to look at or use classical Roman law
sources that were unavailable in the middle ages, which means that
texts like Gaius' *Institutes* found here are virtually untouched and
I make no claims about their general usability.  Ideally that will one
day change, but caveat lector.

Another word of warning regarding these texts: when the original text
was published in Greek, these files either have incoherent
transliterations of the Greek text, which I assume derives initially
from the scanning process, or are simply omitted completely.  Some of
these passages have been fixed, but most have not.  However, now that
they are publicly available, I shall try to be more diligent about
fixing the files.

On occasion, I have made some effort to include the vulgate numbering
alongside the standard internal divisions of the text.  Earlier
efforts were haphazard, but now will be standardized.  Parentheses
(e.g., (27)) are used to indicate the vulgate numbering.  Thus,
something like 11.26(25).1 indicates that our modern edition calls the
26th title what pre-modern editions usually thought of as the 25th.
Scrupulous authors use this fuller format whenever possible so that it
is (much!) easier to search things out in both modern and pre-modern
editions.


### English

Source: [The Civil Law](http://www.constitution.org/sps/sps.htm)

S. P. Scott translated, in seventeen volumes, as it says on the
website give above, 'The Twelve Tables, The Institutes of Gaius, The
Rules of Ulpian, The Opinions of Paulus, The Enactments of Justinian,
and The Constitutions of Leo'.  Although the translation has not
received universal praise, it is still convenient.  (For the *Novels*,
see the
[Annotated Justinian Code](http://www.uwyo.edu/lawlib/justinian%2Dnovels/),
hosted by the [University of Wyoming](http://www.uwyo.edu/) --- an
excellent resource, which includes a superior translation of the
*Code*.)

There are problems with the text as scanned and converted into HTML,
and thus with my conversion into plain text.  The most significant is
that the footnotes of the translation are embedded directly into the
text and so one must be careful about untangling the two. (Many of
them are absurdly long and interweave with the text of the translation
for several paragraphs.)  I continue to fix these problems as I come
across them, but I do not use these texts as much as the Latin
versions, so progress is much slower.  I am trying to be more diligent
in this regard, however.

For medievalists, however, there is one advantage to this translation:
because Scott did not use the Krueger edition of the *Code*, his translation
also includes the *authenticae* and the *Constitutions of Frederick* as they
are found in vulgate editions of the *Code*.  This is a nice addition.

By the same token, this means there are downsides to this translation.
The most important one is that the numbering occasionally does not
match what we find in the standard editions, which can be very
annoying at times.  This is another area where I make incremental
improvements.  Numbers enclosed in angle brackets (e.g., `<52>`)
indicate an addition on my part, marking the text where it corresponds
to an internal division as one might see in Mommsen or Krueger (etc.).

## Contributions

If you download or clone or whatever these texts and end up making
improvements, please consider submitting your changes so others can
benefit in the future.  These texts can greatly facilitate the ways we
can access and search the texts of classical canon and Roman law, and
so it makes sense to make them as reliable and as easy of access as
possible.

Contributions of other texts, or other resources such as
reverse-lookup tools, would be great as well.
