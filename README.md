
# The Clean Coder
This will contain personal list of interesting things, opinions and key takeaways from book The Clean Coder by Rober C. Martin.
Content will not be structured similar how the book is strucured.


## Overview
Book itself is trying to define term professional programmer. What it means, how should this person behave, communicate, make decisions, commit to things as well as learning some useful habits. Author also want from reader to learn from his many mistakes that he did during his career.

## Professionalism
Professional is defined a person that should meets these criteria:

### Learn and educate continuously
Programmer should always keep learning new things that are outside of his comfort zone. IT industry is changing very fast so it can easily happen that after few years your knowledge becomes obsolete and you will not going to keep up with your other pears. Professional programmer should educate beyond stuff in work, he should not take free books, conferences from employer as standard, but rather the favor. You should find a way to take extra time beyond work and continuously educate/learn new stuff. This should be something that you consider fun to try/learn, otherwise it can be  recipe for burnout.
### Be committed
Professional should be committed to statements that he say. he should be aware that phrases like "I should" "I need" , "I hope" are clear sign of lack of commitment. Therefore you should not use these, but rather use "I will" ... "by".. "date". Professional is not required to always say "yes". He should find a "creative" way to make it work or otherwise say "no"
### Say no
Professional have courage to say no to manager, Both manager and programmer should defend their ideas and key points and find mutual agreement/alternative. When defending your ETAs do not try to explain why some "feature" take longer to implement while it is not necessary, because it can lead to micro managing of things and arguing about petty things.
More in stake it is, more important is to say no, you should stand our for your reasoning. Do not get tricked by saying "I will try" when management is pushing on you or definitely do not try to be a "hero" that saved the deadline. You will mostly do not make it. And when management will look for someone to blame, be sure that it will be you. Even if you make it will cost you nerves, overtimes and person life costs.
### Know the domain
When working on new project/feature you should understand the domain that you will be working on. Read a book about it, meet with people they understand it, to make sure that you implement solution that users really need.

### Take responsibility /  being team player
I think that these two qualities are self explanatory and do not need to take deeper explanation.
 
 ## Coding
 Coding is intellectually challenging and exhausting activity. It requires level of concentration and focus that few other disciplines require.  Before you start coding you need to be sure that:
 - you understand the problem
 - your code should fit into system without increasing complexity
 - your code must be readable

Being concentrated  for longer period of time is challenging.  When you cannot focus (e.g. due to team/organization distractions or everyday life problems)  your code will be bad and you may end end redoing what you did later. 

### Bad code
It is very probable that worst code you end up writing is code that you wrote when you were tired. Many times this code can work but chosen solution will bite you back later on.

TLDR: Make sure you have enough sleep and healthy lifestyle.

### Worry code
Whatever personal issues/problems you may have, even if you think you are not affected by it, you will be thinking about them in background and as a result it will affect your productivity and ability to code. Try to allocate some time to fix/improve this issue so it will not hunt you during the day.

### Flow zone
it was very surprising to me that author is trying to prevent coding when he feels like he entering "the zone". He is defending this decision by fact that you may end writing a lot more code when you are in the "zone" but you will end up going back to this code many times and questioning the decisions you made because you made lose sight of bigger picture.
Whenever you realize that you are entering the zone you should step back, answer emails or better find coding partner.

 ## Testing
There is no question that tests are crucial part of software development. Main advantage of having high code coverage of your system is that:

 - It actually make sure that code works !!!
 - It helps greatly reduce defection found.
 - It enabled you to freely add/modify functionality of current system without worrying whether it affects other parts of the system
 - Test are making sure that code structure is flexible and easy to make changes

### TDD
 Test driven development is more than highly recommended in this book and to be fair there are pretty strong arguments for it. TDD is not new, it has been here in first form in 1998 and since then it has proven that it just works !
 
Personally I think TDD is very simple concept that is making sure that :

 1. You are actually writing meaningful tests.
 2. it is making sure that your code is well designed, and decoupled.
 3. It won't let you fall into thinking that you don't need tests or that you will add tests later ("yea sure ....")
 4. It implicitly keeps your code coverage at high levels which in results automatically grants you all benefits mentioned that you gain when you have high test coverage !
 
