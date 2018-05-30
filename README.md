# EMOTIONAL ICONS FOR ALL

The "emoticons" of old, :), :D, :|, and their nose-inclusive variants,
and the rest of their head-tilted school (for we are not here
discussing the upright "o_O", etc.), these have died, Facebook and
others have killed them, finally, for the many, these evocative
agglomerations of symbols and letters, appropriated from their
conventional uses and taught the unfamiliar science of standing for a
face which, monospaced in their early youth, golden in the heyday of
USENET, engaged the ingenuity of their authors and the creativity of
their beholders alike, the paucity of detail found in their poor
materials enabling a richness of interpretation paradoxical only to
the foolish who, in obedience to the unintelligible demands of an
incomprehensible system, have sought, with increasing success, to
replace the vague (yet, oddly, literal), rough, and popular with the
concrete, graphical, and centralized, the unruly ferment of unbounded
textual combination and novel recombination with selection from a
pre-chosen set of cartoonish faces, the open, in a small-scale
reproduction of the fate of the Internet generally, with the closed.

Anymore, that is, when you type a good old-fashioned smiley :) :) :)
:), you're apt to see it replaced by some grody circular abomination.
They're abominable because they replace the schematic and suggestive
text icons with relatively more concrete graphics which allow less
interpretive freedom and less playfulness, and less creativity. (It's
also inconsistent across platforms, with (e.g.) both Facebook and
Hipchat replacing :| with a face with its mouth a straight line, but
only the former replacing :/ with anything.) You might not think that
a yellow circle with horizontally disposed eyes and a horizontal line
for a mouth would be less evocative and more concrete in what it
does evoke than the vertically disposed eyes and vertical line for a
mouth of ":|", but such, I report, is my experience; the different
graphical realizations of the nonplussed face suggest in each case
something different, but they each suggest something particular, in
contrast to the flexibility of the spare original.

The plain-text emoticons have the further advantage over the graphical
that anyone typing text can type them, and add to or change them; I'm
not sure precisely what :B might convey, but I can still use it (and
have); if I want to indicate that I'm so surprised I'm vomiting 
exclamation points, I can employ ":O !!!". It's an open field.

These pleasures can be enjoyed once again, with the `emote` script
herein to be found, which takes a single commandline argument and
copies into a clipboard, except with a zero-width space between each
character [1]. If `pbcopy` can be found, it will use that; otherwise,
it will use `xclip` (regardless of whether it can be found! ha!),
using the `clipboard` selection (which allows the contents to be
pasted using ctrl-V, rather than the middle mouse button). I use this
with `dmenu` on linux and (so far) just from the terminal on osx, but
I'm sure there's a convenient way to use it there too.

Regrettably, since many of the most emotional characters on the
keyboard are also special to the shell, usability takes a bit of a
hit; one must type:

    emote ':|'
    
rather than:

    emote :|                                                                               
                                                                                 
But such is our sublunary world.


[1] Or rather, between each whatever-it-is that one iterates through
when iterating through unicode in Python. 
