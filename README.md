# Falsehoods Educators Believe

This is inspired by the "Falsehoods Programmers Believe" series of articles that cover many unexpected edge cases for common problems. An extensive list of such articles can be found in the [awesome-falsehoods-programmers-believe](https://github.com/spickermann/awesome-falsehoods-programmers-believe) git repo.

The goal of this repo is not to denigrate teachers, administrators, or students. Rather, it is phrased provocatively to catch attention and get people to examine their assumptions. Also, since I started this repo, I find the adversarial phrasing helpful in getting thoughts out of my head faster.

Once this repository in a more complete state, I intend to compile the knowledge here into "how to" or other guidance documents that will look more familiar to educators and be a more comfortable read.

## Status

This is still in **draft** form. I've written down various falsehoods that I've come across talking with educators at conferences, during consulting work, and things I've read about in the press and trade papers.

I'm sharing this repo more broadly in the interest of motivating myself and others to add detail and sources to the sections below, and also any topics or sections that I may have omitted.

## Canonical Sources

* [Keybase](keybase://team/comp_sci_edu/falsehoods-educators-believe)
* [GitLab](https://gitlab.com/egx/falsehoods-educators-believe)
* [GitHub](https://github.com/egx-org/falsehoods-educators-believe)

## Falsehoods About Computers in Education

### Kids are Digital Natives, they know how computers work.

Using an information appliance (iPhone or other touch device) does not increase one's ability to program a generalized computer. In fact, today's kids are generally **less knowledgable** about programming than previous generations.

Old computers dropped users straight into the command line. There was little separation between using and programming the computer. Apple and other companies have moved to the App Store model which is far more locked down and makes programming the computer rather inaccessible. For a student wishing to program a computer today they must first perform the following steps (on macOS):

1. Install Xcode Command Line Tools
2. Install Hombrew
3. Install updated, standard versions of Git and other tools
4. install the package manager for the chosen language(s)
5. Install the language version(s)
6. Install a decent text editor
7. Install package manager for text editor
8. Install language extensions and plugins for text editor
9. Get an Apple developer account if you wish to share your software with others
10. Generate cryptographic keys for code signing
11. Learn how to sign software
12. Upload signed software to the App Store or other distribution channels

### All programming languages are interchangeable. It's just syntactic differences.

While there are many core concepts that appear again and again throughout the field of computing, there are some significant differences between classes of languages.

One important distinction is between imperative and declarative languages. Imperative languages (Python, JavaScript, Go) specify the exact sequence of steps that are to be taken in the exact order. Declarative languages (SQL, Haskell, Prolog) specify an end result and allow the system or runtime to determine the most effective way to obtain the result.

Another distinction is the language style:

* procedural - C
* object oriented - Java
* functional - Haskell
* data-flow - Luna
* logical - Prolog

### Choosing the right language is critically important.

Computing concepts such as flow control, boolean logic, and algorithm design are common to a wide variety of languages. These concepts can be explored successfully in languages from [Scratch](https://scratch.mit.edu/) to [OCaml](https://ocaml.org/).

While the types and styles of various programming languages vary widely, the core concepts can, for the most part, be explored in any language and set a foundation for learning other languages.

### It doesn't matter which programming language you choose.

The counterpoint to the above, is that different types of languages can make implementing different algorithms or completing different tasks much harder or easier than other types.

* [What is Good About Haskell? - Donnacha Oisín Kidney](https://doisinkidney.com/posts/2019-10-02-what-is-good-about-haskell.html)

Additionally, some languages are more "feature rich" than others. Starting in something like Haskell will expose students to concepts such as algebraic data types, lazy evaluation, pure functions and immutability. While these concepts can in theory be explored in a language such as Java that is unlikely, especially in any context other than a highly advanced course.

* [Dijkstra on Haskell and Java](https://chrisdone.com/posts/dijkstra-haskell-java/)

### Visual programming isn't "real programming".

### Having certifications is universally important.

### Having a degree is important.

### We should what industry does, they are cutting edge.

### You need to have the "correct" devices to learn tech.

### You have to have devices to learn tech.

### You have to learn specific topics in a specific order.

### The teacher must fully understand the topic before they can teach it.

### People in industry are fully knowledgeable about their field.

### Popular languages are popular because they are the best.

The vast majority of popular languages today are **imperative, procedural/object oriented** languages with **C like syntax**. None of these properties are necessarily that great, in fact there are serious drawbacks to all of them from a language theoretic standpoint.

* [Let’s stop copying C / fuzzy notepad](https://eev.ee/blog/2016/12/01/lets-stop-copying-c/)
* [A Reply to _Let's stop copying C_ - gingerBill](https://www.gingerbill.org/article/2020/01/25/a-reply-to-lets-stop-copying-c/)

### Partnering with a tech company will make classes better.

### Tech people won't teach because the pay is too low.

### Students need to have a path through the curriculum laid out ahead of time.

### Students need topics broken down into small atomic units that can be taught separately.

### Students will just "mess around" if they are not given detailed directions.

### Updating the curriculum is adequate.

### Test results are accurate indicators of students abilities.

## Falsehoods About Mathematics

### You won't have a calculator with you 24x7

### The way math is currently taught is carefully considered to be the most effective method

### Mathematics == Calculation

### Mathematics can be memorized

### Mathematics is mostly understood

### The math you learn in school will be useful to you outside of school

### The math you learn in school is the most applicable subset of mathematics for most jobs
