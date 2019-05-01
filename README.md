# Just Get It Done

This is (well, will be, one day, hopefully) a board game situated in a corporate
world. Get as much money as you can during the play by competing for
better-payed positions, bonuses, interests in projects, etc.

*This is currently a very early brainstorming stage. In particular, there's
nothing to actually play yet. Everything, including core game principles, might
change*

Whatever is written here is just the first idea. If you have better ideas,
propose them. In general, contributions are welcome. But keep in mind the basics
need to be solved first before diving into specific details.

## The Vision

* The game should not need special equipment (computer/CD player/mobile
  application).
* The game should not get used up by playing (no special forms or sheets to
  write into).
* It should not take 4 hours just to explain the rules 😇.
* Being able to play in just 2 players is a definite advantage, but not a hard
  requirement.
* While the eventual goal might be to have it professionally printed,
  manufactured and boxed, while testing it should be possible to easily print
  all the cards, add some generic gaming material (dice, colored tokens for
  resources, …) and be able to play it. That includes being able to generate the
  cards to be printed as a PDF or something like that automatically and not
  requiring any *special* gaming material.

## Technicalities & tasks

There are some important things to answer early on, before most of the work gets
done.

* Licencing:
  - It should be possible for anyone to collaborate on this and everyone should
    be allowed to print his own copy.
  - On the other hand, if the goal is to eventually have it printed
    profesionally and sold as a proper boxed game, the investor might want to
    have some guarantees noone else will just print their copy and sell them
    too.
  - If there's a profit (royalties) from the commercial print & sale, how are
    they shared between contributors? It would be nice if core authors get a
    part in these. On the other hand, making up some metric (KPI 😜, like number
    of commits) and split the sares based on these is not practical ‒ the
    administration needed to send the money to every one who submits a single
    commit to fix a typo, especially abroad, would be quite high.
* How to collaborate. Should a mailing list or something be made, or just have
  discussions in github issues and eventually merge everything into markdown
  files here?
* Formats. The assumption is, there'll be few kinds of cards (in addition to the
  basic rules, a central board or something like that). If we want to
  automatically format PDF file with all the cards to print & cut, the format
  needs to be machine readable and structured enough for the automation to make
  sense of them. To get a decent output, it should allow certain amount of
  formatting abilities. On the other hand, it needs to be easily editable
  (something like markdown file per card comes to mind, but how to include
  structured data like caption of the card, tag-pictograms, etc?).

## Guiding principles

* The game is supposed to be cynically making fun of the corporate world. The
  right amount of cynicism is somewhere around the [ha ha only serious] sweet
  spot ‒ in particular, it shouldn't *insult*, but it should hint at something
  not being completely OK in the corporate world.
* Gameplay and fun can take precedence before realistic principles, if there's
  an inherent trade of between these two. For example, in the corporate world,
  you might get fired and need to apply for a job in *another* company. But in
  this game, there probably *won't* be another company, so you might apply for a
  different (lower-payed) job in the *same* company and start over from the
  bottom. The alternative would be to kick the player out of the game early,
  which is not nice (unless the game can be really fast).
* On the other hand, some realistic principles should be preserved. For example,
  a smaller company (startup) should be easier to influence by the player's
  choices, while a huge international behemoth lives its own life and can't
  really be guided too much by even the CEO.
* There should be some fairness. Even if none of the authors turns out to be
  from a marketing department (for example), the marketing department should not
  be painted as evil (or, more evil than our own departments). Everyone should
  get their share of evilness and eventual downfall of the company.
* Players should not be motivated to *directly* hurt each other. While they
  necessarily need to compete for limited resources (eg. for a bigger slice of a
  budget for their own salary), there should not be a motivation to eg. sabotage
  a project if it would lead to lowering salaries of all the players (while
  lowering own salary less than others'). For that, we may need to introduce a
  possibility of multiple winners (everyone wants to live above the poverty or
  luxury line, but not whoever makes *most* money). That would make the game
  cooperative and competitive *at the same time*.

## Basic game principles

The players' goals is to earn good salaries. Specifically, the health of the
company is not a *direct* goal of a player (through the company being in trouble
is usually not good for the player either ‒ pay cuts, layoffs, …).

During the game preparation a specific company is chosen (not sure how yet ‒
generated randomly, selected from some existing set). This influences how big
the whole company is, which departments have how many people working in them, or
which department are not even in the company at all or are outsourced.

The company has its own resources (tentatively, money, reputation, know-how,
morale and employees in departments). Each of these resources are used for
certain tasks, allow certain tasks to happen (money are allocated for salaries
of employees or assigned to projects and used up, while know-how isn't used up
by projects but allow some of them to succeed or makes them impossible if it is
too low).

Each player is an employee of the company, assigned into a department (eg.
marketing, engineering, legal…) and a rank (junior, senior, …) ‒ which later on
splits into expert and management tracks (are there possibly more tracks?). Each
player has their own resources (time, influence, promotion points, in-company
budget for their projects ‒ but note that the budget is *not* part of their
salary). The department and rank influence how many resources the player gains
or has (eg. a CEO has more influence than a junior lawyer) or what actions can
be taken (a lawyer can't increase the company know-how if the company is not a
law company itself).

There are certain actions that can be taken by players:
* Working on projects. This uses up some of the player's resources to push a
  project forward. If a project is successfully completed, it generates
  resources for the company and a certain bonus for each player who somehow
  participated in the project.
* Moving inside the company ‒ this uses up the promotion points and can be used
  to move both up or sideways. Note that sideways move may have some specific
  limitations (do we want the players to have skills and losing them by this
  move?).
* Playing action cards. The action cards can influence the whole company, other
  players, currently running projects, etc. The cards being played are likely to
  be restricted by both the resources available and the players position in the
  company. Q: What to do with cards that are not at all useful for such player
  (eg. a lawyer having some engineering card that can't be played) ‒ use cards
  as resources too, to pay for some other actions? Use them instead of the
  „time“ resource?

Furthermore, the rest of the company should somehow play too. They are going to
be other employees in the departments. They are likely to be assigned to
projects (partially by the players, but partially by the game itself). There
could also be some „disaster“ cards, drawn periodically and having *some*
effect. The effect of the game needs to be bigger in a larger company. Also, not
all disaster or company decision actions are applicable to each company ‒ so, if
the card can't be used when drawn, discard and draw a new one?

Every now and then (each round?) company gains money and pays salaries to
players.

We also need to have principles how to deal with things like company not having
enough money to pay the salaries or pay for projects ‒ bonus cuts, layoffs,
bankrupts, projects being canceled. If there's not enough morale, unions might
go on strike. Etc. If a player is in „adequate“ position, they should have some
say in what happens here, but we also need automatic resolution in case no
player (only non-player employee) is in the position.

What do we do if player gets himself fired or is unhappy about the work and
decides to leave? Start him over in a new position at the bottom of company?

Do we want players on high-enough rank to have a say about eg. salary policies
of the company, or is it fully prescribed by the specific company?

### The goal of the cards

The general setting should be in a way that the decisions are often in conflict
with something. Working on this particular project will drain valuable resources
the company should long-term invest in something else, or action of one player
will often be good for that player but not as good for some other players (or
the company in general).

The players should struggle between gaining for themselves, but not sinking the
company and risking losing the job as a result.

## Inspiration

I've played the [alchemists] game. This game is about making fun of the academic
world. In the game the way to win is to keep publishing theories. In particular,
there are some advantages if the theories are *correct*, but it is not a
requirement.

I've been introduced to the game by two friends who are Ph.D. students. My
reaction to that was, if academicians can have a game making fun of their world,
we, corporate employees can have our own too! While the game principles
described above are different (I guess there's a mix of inspiration from many
games in it), the *theme* is similar in nature.

[ha ha only serious]: http://catb.org/jargon/html/H/ha-ha-only-serious.html
[alchemists]: https://czechgames.com/en/alchemists/
