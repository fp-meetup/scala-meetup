+++
author = "Eason"
date = 2025-12-11
title = "7 years of Scala religion, part I"
image = "/images/hardangervidda.jpg"
+++

I'm Eason du, a Scala enthusiast for many years. This is the first part of my story of using Scala for 7 years. I'm writing this story just before the upcoming Scala meetup in Shenzhen on December 13, 2025, named "Scala reload 2025: AI, chip and DSL". My story will be continued in part II for more details about my career. This post is not well organized by timeline or topics, but rather a mixture of my Scala career and my thoughts.

## From Haskell to Scala
I started using Scala in 2018, when I graduated from college. At that time, I have already been using Haskell almost whole of my campus life for Bachelors. I also use Java some times for Android development. Since Haskell won't lead me anywhere closer for a job, After some research, I decided to learn Scala. 

I still remember it's not easy to grasp Scala, maybe taking me almost half a year to be confident in it. Retrospectively, I think I have the almost ideal background for Scala, Since I write both Haskell and Java(and Scala = Java + Haskell). Since then, I have been using Scala for almost all my work, including work projects, open source projects, and personal projects. 

## From backend and big data to chip design
It's extremely lucky that I'm able to use Scala all over my career(one reason is that Scala is at the most popular time during these years for internet companies). Another reason is that I'm obsessed with applying functional programming in my work. To keep using Scala, some times I have to jump to totoally different domains, from backend services, to big data, to chip design(compiler), and to AI. I can't imagine to work in so many fields if I'm not using Scala. The reason is:
- functional programming is very general, and Scala is the most practical functional programming language
- Due to the first point, Scala is applicable to many domains
- Skills in Scala in one domain is transferable to another domain
- Using Scala let me unify different knowledge in different domains, so I can learn faster

## Returning to China in 2025
After working in Norway for 2 years where I mainly used Scala for big data and Spark, I returned to China and started as a research assistant about chip design with Chisel, a Scala based DSL for chip design. More specifically, our group is working on formal verification of chip design. And again, formal verification is a field that is very close to functional programming, so I'm able to continue my Scala journey, and deepen my understanding of functional programming and mathematics to a new level after my math-intensive study in DTU, Denmark.

The local community of Scala in China has shrinked a lot from 2023 when the biggest sponsor Tubi freezed hiring and stopped organizing meetups, due to the recent layoffs in tech industry, so it's difficult to gather more Scala enthusiasts together. There are also multiple reasons:
- People usually use whatever language is mandated by their job, and that's usually not Scala
- People that previously used Scala are forced to switch to other languages due to job change or project change
- Many internet companies have finished their development, and not much new development is needed, so the demand for backend and big data engineers in general has decreased

However, I still believe in Scala, seeing its rising and falling as a natural cycle. The rise due to backend and big data might be over, but the new applications in AI and DSLs are just starting.  A recent talk with the author of ScaIR, a Scala library for MILR, shows the potential of Scala in compiler, which is the natural area for functional programming, but currently dominated by C++ due to historical reasons. The rise of the Chisel DSL for chip design implies the potential of Scala in compilers as well, where the expressiveness matters a lot.

Another thought is that, I have often heard the opinion that the new version of xx language is coming and copying the features of Scala(or other functional programming languages), such as Kotlin, Swift, C++, etc, so that those functional programming languages like Scala will be replaced. That didn't happen, and I don't think it will happen in the future. I think one of the reasons is that Scala and other fp languages like Haskell have a relatively graceful theoretical foundation, and it's impossible to copy that beautiful core, but only some superficial features. Thus, those new languages will never fully replace Scala or Haskell, but rather coexist with them.

In the calculation of career path, The choice of programming language is almost never be the decisive factor for most people, but for me, Scala has been the key to open many doors due to my religious belief in it. I'm honored to say that I'm working almost exclusively in Scala for so many years, and I didn't foresee any change to that. This is one reason why the title contains "religion".

Another reason for the word "religion" in the title is that, the prevalence of one programming language probably depends on a lot on the taste of the people that controls the resources(capital, money, personal influence and connections, etc). Thus, the popularity of one language is not decided purely by scientific factors. Based on this reasoning, Another way is to enter business world with Scala, or on the contrary, break down the commercial world with Scala based open source projects, This is also one of my future plans.

## Ending
In the end, I also want to thank all the people that contributed to Scala community. I read lihaoyi's blog posts where he shared his experience from the very beginning of Scala back in 2004([12 years..](https://www.lihaoyi.com/post/12yearsofthecomlihaoyiScalaPlatform.html)), when the Scala ecosystem was much less "batteries included" than now. Nowadays, it's much easier to use Scala for almost everything(except things that prohibit garbage collection). In addition to technical blogs, I also enjoyed a lot from the stories about people's career in Scala. This kind of stories are mind opening, and also tells Scala enthusiasts how to better plan their careers.

Thanks for reading my story. See you in the next part!
