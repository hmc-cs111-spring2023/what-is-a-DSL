[assignment howto]: https://sakai.claremont.edu/x/v8BuEq
[fowler]: https://sakai.claremont.edu/access/content/group/CX_mtg_160537/Fowler_Chapter2.pdf
[markdown]: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
[pulls]: https://github.com/hmc-cs111-spring2023/what-is-a-DSL/pulls

# What _is_ a DSL?

In this assignment, you will read an introductory chapter about DSLs, which will
give us some shared terminology for talking about DSLs and their
implementations. Then you will find a DSL "in the wild" and describe its design
and implementation using terminology from the reading. Finally, you will write a
program in an interesting DSL: ContextFree.

After this assignment, you should be able to:

- Recognize properties of a DSL, and evaluate those properties using common
  terms.
- Use at least two DSLs (ContextFree and Markdown).
- Use GitHub as a submission system.

## Teamwork

For the technical part of the assignment, you will work by yourself (though you're
free to talk about the assignment with anyone). For the critique part of the
assignment, you and a partner will review each other's work.

## Read up on the assignment workflow

[This article][assignment howto] describes how we will do our assignments on
GitHub. Be sure to read it before you start working on your assignment.

## Read Fowler's introduction to DSLs

Read [Fowler, Chapter 2][fowler].<sup>1</sup> For the most part, this reading is
self-contained. In a few places, Fowler references other parts of the book.
Ignore these references; you can understand the reading without them. It may be
helpful to know that, in Chapter 1, Fowler described a domain called Miss
Grant's Controller. You can safely substitute the domain you choose for your DSL
(see below) in place of Miss Grant's Controller.

_<sup>1</sup> This copy of the reading is for class use only. You should not distribute
it to anyone outside the class. You should destroy your digital copy when the
class is over._

## Find a DSL

Find a DSL—one that you think most other people in the class _won’t_ know.
When picking a DSL, it's good to pick one for which you can find a few
example programs, so you can get a good sense of it. Sometimes it's hard to be
sure whether or not a language is actually a DSL. That's okay! If you find a
language that you think _might_ be a DSL, but you're not sure, then go with
it—just assume that it _is_ a DSL.

_Tip:_ One way to find DSLs is to search the web for "`domain` DSL", where `domain` is a
topic you are interested in (for example, animation, abstract algebra, juggling, etc.).

## Describe your DSL

Open the file `my-dsl.md`, read the questions there, and edit the file to
include your answers to those questions. Back up your answers with any evidence
that you can find about your DSL. Your answers must be formatted in [markdown].

## Learn, use, and critique ContextFree

1. Download [ContextFree](https://www.contextfreeart.org/), a domain-specific language for making art.

2. Write an interesting ContextFree program. Save your program in a file called
   `firstname_lastname.cfdg` (where you fill in your first and last names, of
   course). I recommend keeping it simple! No need to use advanced features of the
   language such as functions or control structures.

3. Export a nice image from your program. (Choose the `Render` menu, then `Save
Output...`) Use a `.png` extension, so your filename should be `
firstname_lastname_variation.png` (where `variation` is the three-letter variation the
   uniquely identifies this version of your program).

4. Answer the questions in `context-free.md`.

## Identify your peer-review partner(s)

Your name is on the left side of this table; the person whose work you should
review is on the right side of this table:

| Your name | Your critique partner's name (GitHub ID) |
| --------- | ---------------------------------------- |
| Adam      | Ryder (rmitchellPitzer)                  |
| Ash       | Chris (cgcouto)                          |
| Brandon   | Kate (muffinkate)                        |
| Carson    | Lilly (lillee205)                        |
| Cas       | Phoebe (pc027)                           |
| Charlie   | Georgia (georgia-reb)                    |
| Chris     | Ash (aayush141)                          |
| Christian | Selim (selimbayar)                       |
| Everett   | Occam (occamkg)                          |
| Georgia   | Charlie (cweismann)                      |
| Kate      | Brandon (BBecker8)                       |
| Lilly     | Carson (carsonfrench)                    |
| Occam     | Everett (everettbu)                      |
| Phoebe    | Cas (cruedy)                             |
| Ryder     | Adam (adamrbeckwith)                     |
| Selim     | Christian (cvaldovinos)                  |

## Peer-review your partner's work

After the due date (or if your partner tells you they have finished), you can comment on
their work. To locate their assignment and comment on their code, follow the instructions
in [this article][assignment howto].

Provide feedback on all aspects of your partner's work, including the information in
`my-dsl.md`, `context-free.md`, their code, and their image. Here are some questions you
might consider / answer when providing feedback:

- Would you answer a question from the assignment differently than your partner
  did? For example, do you agree with how your partner described the DSL-ness of
  their language?
- Did your partner describe anything that you also experienced? For example, did
  you try to do something in ContextFree that was difficult?
- If your partner has raised a question in `my-dsl.md` or `context-free.md`,
  try to answer it!
- Did you learn any cool language features (from ContextFree or Markdown) that
  might add to your partner's work?

## Grading

Good responses will:

- fully respond to every prompt in the starter file, _and_
- be well-written and easy to read, i.e., clear yet concise using good
  organization, and proper formatting, to convey a
  well-formed idea, _and_
- where appropriate, support your thoughts with references to material from
  the reading or from language documentation.

Great responses will additionally:

- be particularly insightful, by using concepts from the reading to classify
  aspects of each DSL in the assignment and / or by disagreeing with the
  classification that Fowler might make and by presenting a strong argument for
  a different classification.

## Tasks

- [ ] Read the [Assignment HOWTO]
- [ ] Read Fowler's [introduction to DSLs][fowler]
- [ ] Find a DSL
- [ ] Describe your DSL's implementation and semantics in `my-dsl.md`
- [ ] Write a ContextFree program in `firstname_lastname.cfdg`
- [ ] Make and save a nice picture in `firstname_lastname_variant.png`
- [ ] Answer the questions in `context-free.md`
- [ ] Submit your work
- [ ] Comment on your critique partner's work
