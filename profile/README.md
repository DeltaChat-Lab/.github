# DeltaChat Lab
DeltaChat's testing ground, where you can use AI to turn your ideas into reality and merge them into the official repository. The official repo can refer to the code and suggestions inside to manually merge the implementations with the official code.

DeltaChat Lab is an organization that helps everyday users and beginners contribute to the official DeltaChat project. Since these users—who are typically not professional coders and have limited time—are the ones actually using the app, DeltaChat Lab values ​​their input; even if the code they write is imperfect, the creative ideas and improvements they offer are undeniably valuable to the official project. Once users have refined a feature within the Lab, they can share the problem they solved and post their implementation code on the DeltaChat forum. DeltaChat Lab serves as a hub for development-stage builds, ensuring a steady stream of new features and innovative ideas that can be showcased and eventually merged into the official DeltaChat application.

DeltaChat Lab是一个帮助普通人和小白为DeltaChat官方做贡献的组织，因为小白通常时间较少并且不擅长写代码，他们是DeltaChat的使用者，DeltaChat Lab相信使用者写出来的代码哪怕再烂，但我们也收获了使用者的创意和改进，而这些对官方的DeltaChat来说无疑是宝贵的，在使用者在Lab上完善好功能后完全可以向DeltaChat的论坛讲述自己的解决的问题，并且可以给出已实现的代码在论坛下面。而DeltaChat Lab承担起DeltaChat的开发版本，让新功能和好创意源源不断的展示并合并进官方的DeltaChat就是DeltaChat Lab的使命

# Points to Note for PR
1. The content to be merged must at least pass the full suite of GitHub CI checks.

2. Features must be practical; a feature cannot simply be a functional interface that ultimately serves no real purpose. For instance, consider a plugin system implemented via code injection: if the app undergoes code obfuscation after compilation, plugins developed based on the original source code might become unusable or restricted to minimal functionality (such as only sending messages)—scenarios that lack practical utility. To be eligible for merging, the submitter must provide at least one working example demonstrating the feature's utility, and the implementation must be verified as effective by a member of DeltaChat Lab.

3. Maintain consistency: the UI must align with the official design, and title placement must match the official layout; otherwise, the software will ultimately devolve into an indescribable mess.
