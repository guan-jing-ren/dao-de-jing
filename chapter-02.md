Don't turn it into A Thing
===
```
When the world knows beauty as beauty, ugliness arises
```
- When the world knows testing as TDD, tests become meaningless.
  - We all know testing should be done, and that software should be made easily testable. However, knowing what and how to test is more important than the number of tests. TDD makes a virtue of quantity of tests, leading to tests that add nothing to quality, and hide problems by pretending most of those meaningless tests pass.

  - Automating tests too early solidifies the design when it is too early to know the correct design. Automated tests makes it harder to discard those tests. Just like product code, test code must also be written to be easily thrown away.

  - The goal is not to produce a complete automated test suite up front, but to know what is actually the thing to be tested and what is worth testing. Premature automation is a form of premature optimization.
```
When it knows good as good, evil arises
```
- When it knows agile as Agile, consultants sell silver bullets.
  - A synonym for agility is flexibility. When a team loses flexibility to adapt to a new situation simply for the sake of following Agile, they are no longer agile. Then cultists come in and say you're doing Waterfall, you should be more Agile than you are now, and the cycle starts again.

  - You can't spell consultant without cult.

  - Identify what it is about Agile that works for your team and project and do those things and not every Thing. Understand the spirit of agile, not the (capital) letter.
```
Thus being and non-being produce each other
Difficult and easy bring about each other
Long and short reveal each other
High and low support each other
Music and voice harmonize each other
Front and back follow each other
```
- Thus Waterfall and Agile produce each other  
Robustness and features bring about each other    
Long release and short sprints reveal each other  
High coherency and low coupling support each other  
Application and library harmonize each other
Development and testing follow each other  
  - Blindly adhering to Agile practices leads to rigidity. People try to elimnate rigidity with Agile, but end up with a different form of rigidity.

  - The more robust code is, the easier it is to add features. The ease of adding new features is an indicator of robustness. Agile code is not fragile code. This includes tests.

  - Short sprints exposes an inefficient release process. The harder it is to shorten a sprint, it usually means testing is fragile, which usually means your product is fragile.

  - Highly coherent, lowly coupled code go hand in hand with each other. Irreducible complexity is the outcome of blind evolution. All code evolves, so make sure selection pressure is about coherency and coupling.

  - Developing and testing are really the same thing, but not in that TDD way. Code is already being tested when it is used to write other code. If your code induces boilerplate code, it means it is failing the test of code usability. No unit test can fix a broken design. A broken design renders all tests meaningless.
```
Therefore the sages:
Manage the work of detached actions
Conduct the teaching of no words
```
- Therefore effective developers:  
Are agile not for the sake of being Agile  
Conduct development with no buzzwords
  - Practices that are agile are so because of their inherent and emergent qualities. They are not agile merely because some consultant deemed them to be.

  - Developers must make decisions on a case-by-case basis, whether it is algorithm implementation, architectural design or development methodology.
```
They work with myriad things but do not control
They create but do not possess
They act but do not presume
```
- They work within many methodologies without imposing  
They write code that can be thrown away  
They prototype before knowing  
  -  If there's any recurring theme to any development methodology, it is prototype, prototype, prototype. Continuous Integration? Prototype. Agile? Prototype. Iterative Waterfall? Prototype.

  - This is why effective developers remain effective regardless of the fad that management is trying to push. They always try different things out (a form of testing) to make sure they understand the problem.
```
They succeed but do not dwell on success
It is because they do not dwell on success
That it never goes away
```
- They engage in best practices, but do not develop cargo cult practices  
It is because they do not turn a good thing into a Good Thing  
That it never becomes a hindrance
  - Cargo cult practices arise when those same best practices are performed regardless of effect.

  - What worked once, or a few times, for other people, doesn't make it an absolute best practice. The easiest way to make something legitimate-sounding is to give a name with a capital letter, and it is mistaken to mean something that will always work. Any fool can give anything a name to make it more important than it is.

  - Perfect is the enemy of the good. Trying to reproduce the sucess of a best practice in one area often results in the disintegration of the next.