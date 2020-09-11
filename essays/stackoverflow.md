---
layout: essay
type: essay
title: StackOverflow Helps
# All dates must be YYYY-MM-DD format!
date: 2020-09-10
labels:
  - Software Engineering
  - Learning
  - Fourms
---

In my first introductory programming class the first lecture included the ominous warning from my professor, I can't stop you from using stackoverflow.com, but I will be able to tell if you copy code from it, so don't.  I had never heard of stackoverflow.com, I assumed it was a website, so of course, I had to look.  I was too new to know what I was looking at, I didn't understand any of it, and I wasn't inclined to find shortcuts on homework, as I already know how that affected one's test scores.   

A few weeks into the class, one of my classmates mentioned that stackoverflow.com helped him with an assignment after I mentioned that I spent the whole weekend trying to draw triangles with *'s.  When in the following week I got stuck, I typed in many variations of what I thought I needed help with, but nothing yielded results that I could even understand.   I finally stumbled across a post that seemed similar and the response was something like "DO YOUR OWN HOMEWORK! Most teachers would consider this cheating!"  There was another comment about wasting your time in school if you're going to cheat.  But noticeably there was no answer.  

This user posted a link to their homework assignment; ["Can anyone check these to see if I did them correctly. Thanks * Also I'm not sure on how to do number 8 if anyone can help me out that should be awesome. "](https://stackoverflow.com/q/32875985) followed by a link.  This is the replies; "This is not your free homework-checking service." "Please copy the content into the question body. Nobody wants to go to your link."  

As my classes progressed, I was one day in office hours with a professor he answered my question "I don't know? Did you look at stackoverflow.com?" I was shocked and slightly proud that I stumped my teacher.  I reluctantly told him I had but did not find an answer, as he turned and started looking himself.  Eventually using search terms that I had not known to try; we found a solution to my question.  I asked him how often he looks for answers online, and he laughed and said, "All the time!"  That's part of being in computer science, we post and answer each other's questions.  But he warned me to look hard before I post a question that someone had already answered. 

I have since learned better techniques for searching and understand substantially more than when I first looked at stackoverflow.com.  I have not had to post since I have never failed to find a solution.  

The first thing I learned is to not ask homework questions.  

The second common thing I see is replies of nothing other than a short "Already answered" followed by a link. 

Third and also embarrassing to read is when someone posts and the reply is "what are you wanting help with?", or "what is the problem?" the poster did not explain clearly or show what was wrong. Sometimes [a post](https://stackoverflow.com/q/3670229) can get several critiques "Free tips for getting good answers: 1) Don't use "urgent" or any other spelling of that word. Is your question really more important than others'? 2) Use the code formatter." "What is your issue? Show us some of your errors and we can help more." "More tips. Messages starting with "Kindly etc etc" normally translates to "Listen up suckers! Do as I say: ". 

Finally, it should also be mentioned to go to the correct forum for your problem or you could get [this](https://stackoverflow.com/q/60792725); I think this might be more appropriate for superuser.com than Stack Overflow. Related: mac-forums.com/forums/macos-operating-system/…, apple.stackexchange.com/questions/147715/….  

Mostly on stackoverflow.com, I see genuine questions and genuine answers.  I use it myself to learn things or find answers to a problem that usually I discover I created.  Occasionally though I see praise in a [reply](https://stackoverflow.com/a/5062670) "You did a great job of summarizing what's awesome about Node.js."  The community of stckoverflow.com has given this discussion over 3000 upvotes. Even though the question was open ended, it was specific and the user posted alot of information and links.

I was recently watching a YouTube recording of my Software development teacher.  He was explaining the solution for a coding practice.  As he was explaining he stopped himself early in his lecture, when he mentioned that there was a way to answer the practice in one or two lines of code.  Being in our first week of using JavaScript he explained the answer using eight lines, counting the function declaration.  Every single character he typed was familiar to me, so no trick answer. 

``` JavaScript 

function isUnique(str) {
	let chars = {};
  for(let i = 0; i < str.length; i++) {
  	if (chars[str[i]]) {
    	return false
    }
    	chars[str[i]] = true;
    }
    return true;
  }

``` 

A few hours later, I was curious about how it could be done in two lines.  I started with a google search of the assignment name, often previous semester's students openly post homework and assignments online.  No matches, and the results were not even close to what I was searching for.  I changed my search terms to "compare string characters Javascript", and I was greeted with my old friend, stackoverflow.com.  In less than three minutes I found the [two lines](https://stackoverflow.com/a/55487751) of code that would replace the original eight lines, I tested it, it worked.  Score a win for stackoverflow.com. 

``` JavaScript 

function isUnique(str) {
  return new Set(str).size == str.length;}

```
