---
title: Why I Choose Flutter to Build Small-Scale Apps Efficiently
date: 2024-10-11 10:32:00 -500
categories: [coding for beginners, my journey, project ideas]
tags: [flutter, for beginners]
image: "https://raw.githubusercontent.com/cristina22999/cristina22999.github.io/refs/heads/main/assets/img/flutter.jpg"
---


I’m sure you’ve seen Flutter appear very frequently in tech blogs, news and job requirements recently. It has been the “hot new thing” in mobile development for a while now. And as annoying as it can sometimes be, it is widely chosen for good reason.

I came across it through 2 companies I started working with to develop their apps, both of which were developing the front-end in Flutter. I had no experience at all prior but quickly got up to speed, bringing me to the first pro:

**1. Ease of Learning**  
Definitely one of the major selling points I look for when choosing a programming language for a project. Flutter is a satisfying experience of a streamlined learning process; the documentation is clear, and the community is supportive. There are thousands of packages out there, with pre-built solutions to common functionalities, and to help build pretty much anything you can think of, so it allows for efficient integration of your app’s functionalities. Its popularity has led to a growing community and ecosystem, with a wealth of open-source packages, libraries, and plugins. And as a Google-backed framework, Flutter benefits from consistent updates and high-quality documentation.

> Top Tip: If you are ever struggling to work something out when using a package, go to `https://pub.dev/packages/{package}`{: .filepath } and add the package name as it appears in `pubspec.yaml`{: .filepath }. Then copy the docu found here into ChatGPT, and your failing code. Best experience ever is seeing your issue solved within minutes because of how well documented most things are.
{: .prompt-tip }


I cannot stress this enough: even if you’re completely new to mobile app development, you can get a working prototype up and running in a reasonable amount of time. I know because I did it.


**2. Flexible UI Design**  
For those of you who have tried to build a web in HTML or similar before, it can be a pain to properly align items and make things be where they should be on all dimensions of screens. Flutter has a great way to deal with this; the UI components such as `Column`, `Row`, `Expanded`, and `Align`, make designing responsive interfaces straightforward. Features like `Flex` and MediaQuery, make controlling how elements adjust across different screen sizes easy, and most importantly, require minimal additional testing. I do not miss spending hours perfecting UI’s  across different devices and screen sizes or proportions, and I can now use that time to focus more on the app’s functionality and user experience. It does come with a small caveat; there is a very strict structure of which components you can or cannot place within each other. And if you dare get it wrong, the terminal will blast you with never ending “Misuse of ParentWidget” errors, which can be annoying. But it does also force you to fix the issue instead of letting it linger, and once you do the structure will be clean and error-free as you add new things.


**3. Well-Structured Codebase, Readability**  
This may sound like it shouldn’t make a big difference, but Flutter’s code is pretty. Especially if you hook it up with the Prettier extension on VSC. Thanks to its use of Dart, the code is maintainable, easy to navigate and VERY readable,which really helps spare many headaches. I remember going to a Hackathon night with developers that had many years of experience with languages like C++ and Pascal. So,understandably, when they saw my cascading brackets with automatically added labels to see which component is finishing and keeping the structure clean, they were drooling. Nothing like fangirling over a clean use of closing brackets with some 50 year old hardcore coders.


**4. Seamless Integration with Firebase**  
Again, a major advantage for beginner developers; Flutter’s compatibility with Firebase allows for a shockingly easy and code free alternative to complex backend services. Firebase doesn’t require a prior structure at all, a plus for apps that are still being conceptually developed and whose functionalities keep changing. At one of the startups I was working for, the data types and data we needed from users kept changing as we grew. So if you don’t want to be changing the infrastructure of your database every week, you can just add new paths for folders and files in Flutter for your request to Firebase and these are automatically created. This is great to allow you to only use the storage necessary, as data is only stored when needed and a request is made. It also allows easy management of the structure and data through its interactive UI,as you can edit and delete data with a few clicks.

It also comes with various services. Mainly, I use Firestore Database to store user data that has to be fetched many times, fast and efficiently. Then I use Firebase Storage to store media, keeping the paths to these media files in each user’s firestore file for cleaner logic. To painlessly handle security and sensitive user data, I use Firebase Authentication. And for automatic updates to several data points when users make changes to their accounts, I use cloud functions. This **significantly** reduces the time spent on backend setup, which makes it ideal for startups looking to develop smaller apps where speed and efficiency are key, and for talented but inexperienced coders.

It is also well-integrated with other Google services like Google Cloud, for other backend needs and great long-term reliability. 


**5. Cross-Platform Support**  
I guess I had to mention this at some point, but as I’m sure you’re aware Flutter offers exceptional cross-platform support to build apps for both iOS and Android from a single codebase. Goodbye to having to maintain separate codebases. In addition, Flutter does also support web applications. It is worth noting though that adding web functionality often requires writing some additional HTML code, but this still improves flexibility and scalability.

**6. Fast Development Cycles** 
I LOVE hot reload, especially when I can just have my emulator on the same screen as my code and see changes immediately with one tap of a key. This helps save time and drastically shortens development cycles, as future errors can be avoided since you see everything rendering on screen as you go along. Without having to restart the app! It’s especially useful when building MVPs or perfecting UI designs, and makes coding interactive AND efficient! 



**7. Final Reason**

I don’t really have a final reason, I just prefer prime numbers. But I guess that since I love maths and Flutter makes me think of the Butterfly Effect in Chaos Theory, the cool name gives it a bonus point.
