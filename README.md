# dungeon
An gramatically opinionated role-playing game from 1980.
--

This seems to be a mix of rough draft and revisions of a program I wrote in
the spring of 1980, in a variant of BASIC that shipped with the
[HP 3000](https://www.hpmuseum.net/display_item.php?hw=798) minicomputer
that my high school had recently bought or leased - replacing the already vintage
[IBM 1130](https://www.ibm.com/ibm/history/exhibits/1130/1130_intro.html)
on which I cut my coder teeth.

The computer's main purpose was to emit
report cards and class schedules, but its
[Multiprogramming Executive](https://www.hpmuseum.net/upload_htmlFile/PrintAds/Ad1978_Jun_3000_Series!_ModernData-36.jpg) allowed you to "develop new programms
on the HP 3000 while it's running your old ones," so motivated amateurs
were allowed onto the sanctified premises to hack away
(as it wasn't then called).

From an auto-archeological point of view, what's interesting to me is that
the program is partially data-driven, using computed `GOTO`s along with `DATA`
statements to link rooms.  I recall that, eventually, the data model had
cartesian constraints (allowing a primitive map-generation), but, at this
point, you could link anything to anything.

I was particularly insistent that users write complete sentences, and, in
these days before cut/paste and readline, noncompliant commands would have to
be typed from scratch, if, for example, a terminal period was missing.  That said,
there wasn't a lexer as such, so part of the game was guessing what would be
considered grammatical.  Note the special handling of obscenities; eventually
these were represented in data blocks with primitive obfuscation, growing
to classify various teachers and fellow students of whom I disapproved as having
explitives for names.

I'm embarrassed to say that I still find some of the jokes funny.


![delicate](https://raw.githubusercontent.com/pnf/dungeon/master/images/delicate.png)

![teaser](https://raw.githubusercontent.com/pnf/dungeon/master/images/a-bit-silly.png)
