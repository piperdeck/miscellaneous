# Introduction to Open Source

Open Source is one of the most exciting phenomena of our modern world. For many of us, it inspires us to dream of a utopia where software is free, secure, and well made. But when you start to dive into the culture of Open Source, it can take a while to get used to the jargon, the controversies, and the technical details. You've probably heard concepts and names being thrown around that you don't understand, and straight answers to questions can be surprisingly hard to find.

If you're new to this world, or if you're not new and a bit embarrassed about some of your gaps in knowledge, this article is for you.

But before we start talking about licenses, we need to start with some more basic concepts; namely, Intellectual Property, 

## What is Intellectual property?

Intellectual property, or IP, is the concept of ownership over something intangible, like an idea, a song, a story, or some computer code. It is distinct from concepts of private property (ownership of land and/or capital by a person or organization) and personal property (ownership of physical objects by a person) because unlike those traditional property concepts, theft of intellectual property doesn't deprive the owner of the thing itself. 

If I have a laptop and you take it, I no longer have the laptop anymore. But what if I write a book on my laptop and you hack into it and publish the book before me? In some sense, you didn't really take the book away from me, I still have it. I can still open it up and read it and enjoy it. But most people have a sense that you've done something wrong to me. You may not have deprived me of this intangible thing that is my book, but you've taken away my ability to receive the credit or compensation for work I put into making it. That's what intellectual property (in this case, copyright) is all about.

Intellectual property usually comes in 3 forms: Trademarks, patents, and copyrights. Although the differences between these types of IP

### ~~What are trademarks?~~

~~Trademarks are the symbols that people and brands use to indicate that something comes from them, and not someone else. For example, Apple computers owns the trademark for the apple symbol found on the backs of their laptops and phones, as well as the names "MacBook" and "iPhone".~~

~~As a rule of thumb, trademarks are any of the signifiers that a consumer might look at to reliably verify that the thing they're buying comes from the producer they want to buy from.~~ 

~~In many places like the US and Canada, trademarks require no action from the rights holder in order to come into effect. However, it's usually still a good idea to register a trademark, so that your case is as strong as possible if it needs to be litigated.~~

### ~~What are patents?~~

~~Patents protect people's rights to monetize inventions. Unlike the other two main forms of IP, patents only exist once they are created by a patent registry. If you invent a new kind of rechargeable battery, but you accidentally leave the engineering drawings for it lying in a cafe, it would be totally legal for someone to take photos of the drawings and beat you to market with their own battery that used your innovations, unless you obtained a patent first.~~

~~Patents usually don't apply to computer code, so we won't go into more detail about them here.~~

## What are copyrights?

Copyrights give the author of a creative work the exclusive right to copy and distribute that work. Unlike the other forms of IP discussed above, a copyright comes into effect the moment the creative work comes into existence, with no action needed from its creator.

For the purposes of copyright laws in most places, anything made by a human that requires some degree of creativity is protected by copyright. This includes (among other things) recorded music, written words, visual art and design, and computer code.

## What are licenses?

Now that we know what copyrights are, we can talk about licenses. A license is a message from the owner of a copyrighted work describing how it can be used. If you write an essay and publish it on your website, you might also publish a license telling people that they can feel free to record a reading of the essay for a podcast or a youtube video, as long as they indicate that you're the original author. If you publish a work of art, you might tell people that they can scan and print the art if they want to, but they're not allowed to sell those prints. 

In the case of software, if you publish some source code that you wrote, you can choose to make it Open Source by publishing it with an Open Source License.

## What is Open Source?

> Wait. If the source code is public, isn't it open source by definition?

Well, that depends on what you mean by Open Source. This term is often used to generally refer to an attitude of freely disclosing the source code of a piece of software, documenting it well, and encouraging people to use it for free.

But "Open Source" also has a strict definition in the world of software, and it's important to know what that is.

According to the Open Source Initiative (widely held as an authority on the subject), Open Source is a legally specific way of distributing software. The OSI lists 10 preconditions for open source and maintains a catalogue of approved licenses.

In broad strokes, in order for software to be Open Source, the source code needs to be shared with end-users of the software, and those users must be able to modify the source code, re-compile the software, and redistribute the code and software.

## What _isn't_ Open Source?

### Proprietary software

Proprietary software is precisely the opposite of Open Source software. Proprietary software is usually distributed without the source code available, and the copyright holder retains most of their privileges when it comes to modifying and redistributing that software. Most software is like this. You can install the Adobe suite on your computer, but you need to pay a subscription fee, you need to use Adobe's cloud platform, and you can't modify the software to work better for you, beyond the customizations that Adobe specifically designed.

### Freeware

Freeware is software that you don't need to pay for. It might be open source, or it might be proprietary. The monetary price of software is orthogonal to its free-ness. 

For example, you can download the macOS operating system for free, but you can't look at the source code, and the software license that comes with macOS prohibits its installation on third-party hardware.

#### Bonus round: Shareware

Shareware is basically like freeware, but which is distributed with the intention that people will share it around. This was particularly common in the days before high-bandwidth internet, where people would distribute their favourite applications on physical media like floppy disks. It was a particularly popular way of distributing video game demos, such as those for Doom and Quake.

### Source-available

Software that is distributed in a way that give you access to at least read the source code, but which doesn't provide you any other rights or freedoms, is source-available.

An example of this is Epic's Unreal Engine. According to [the Unreal Engine End User License](https://www.unrealengine.com/en-US/eula/unreal), you can download and use the Unreal Engine, and you can look at its source code, but you're not allowed to publicly redistribute modified versions of the code.

## What is Free Software?

> Surely it’s just software that’s free, right?

We need to distinguish between two related but distinct meanings of the word *free*. There’s *free* in the sense of “free beer”, and free in the sense of freedom. For proponents of “Free Software” (in the capitalized sense), it’s not enough for something to cost nothing for it to be free. It’s not even enough for it to be open source. Free Software, in the strict sense, is software that respects and upholds your freedoms. Which freedoms? Per the [explanation from GNU](https://www.gnu.org/philosophy/free-sw.html):

* The freedom to run the program as you wish, for any purpose (freedom 0).
* The freedom to study how the program works, and change it so it does your computing as you wish (freedom 1). Access to the source code is a precondition for this.
* The freedom to redistribute copies so you can help others (freedom 2).
* The freedom to distribute copies of your modified versions to others (freedom 3). By doing this you can give the whole community a chance to benefit from your changes. Access to the source code is a precondition for this.

I’ve listed out the freedoms because I want you to notice something: This is a fundamentally different kind of thing compared to Open Source as described by the Open Source Foundation. Whereas Open Source is a *legal* definition, Free Software is a *moral* definition. Whereas the goal of Open Source is to compete with proprietary software as a commercially viable alternative, the goal of Free Software is to fundamentally rethink how we relate to software on a personal level. 

## What is Copyleft?

Picture this: You’ve released some Open Source software into the world, and hoping that curious and collaborative people will use it, look at the source code, learn something from it, and maybe even help you find bugs or add features. But then, a big for-profit corporation comes along, takes your code, and uses it in their proprietary software product. On the one hand, your code is being freely used (by the big corporation). But on the other hand that freedom only lasted one generation, so to speak. 

This is the problem that “Copyleft” licenses are meant to solve. A copyleft license gives the user of a piece of software the ability to create and distribute derivative works, *under the condition that those derivative works are also published with a copyleft license*. The goal is that, once you’ve published your work under a copyleft license, it will stay copyleft forever.

## What is a permissive license?

Permissive licenses are sort of the opposite of Copyleft. They permit the immediate user of the licensed software do more with it, including potentially creating proprietary derivative works with it.

The naming conventions of permissive vs copyleft licenses might seem a little bit counterintuitive. Because “permissive” sounds freedom-y, it seems strange that permissive licenses are the ones that can lead to open source software becoming closed source. But the philosophy of copyleft is that if you give people the freedom to restrict other people’s freedom, the net effect is less freedom. A permissive license is sort of like the parent who lets their kid stay out as late as they want, eat candy for dinner, and skip school. The kid might have more freedom in the short term, but it might end up limiting their options later on.

But there are reasons to release your work under a permissive license other than a commitment to absolute anarchy. If your project is very small, or it didn’t take you very long to create, or you plan on abandoning it entirely, it might just be easier to release it into the world with no strings attached rather than to spend your time worrying about how to license it. For projects like hackathons or daily programming exercises that aren’t likely to turn into critical infrastructure in someone else’s technology stack, a big huge license like the GPL might be complete overkill. The license file itself might even be bigger than the entirety of the code that it licenses!

## What is a CLA?

==WARNING: CONTROVERSY AHEAD==

Open source licenses generally cover the intellectual property considerations of source code as it is distributed, used, modified, and redistributed. But most open source projects also have a mechanism that lets people contribute changes back to the original author to incorporate into the software. For example, active projects hosted on GitHub usually let people submit pull requests (PRs).

But this introduces some additional complexity to the intellectual property aspects of the project. Generally speaking, any changes a contributor makes to an open source project are their own intellectual property, and can theoretically come with their own licenses, chosen by their authors, that can be distinct from the license that governs the rest of the software project. 

Why does this matter? Well, imagine I that I created some software, and published it on GitHub with a permissive license. Then you come along and write a new feature, and submit a PR to add it to the project. I think your new feature is great, and I accept the changes. Everyone’s happy. But now, I create a premium version of the software that I sell for 5 bucks, and I keep all of the money. “Wait!” you say, “You can’t take this open source project and sell it for profit!” “Why not?” I say, “It’s my project.” “But”, you reply, “One of the premium features that you’re selling is *my* work. I never gave you permission to sell it!” And the thing is, in this situation, you’re right. The feature you wrote is your intellectual property, and by accepting it into my project, I limited what I could do with the project as a whole.

This is why many projects have a contributor license agreement, or CLA. If a project wants to accept contributions from the public, but it also wants to sustain itself and make money, it will often reject contributions from anyone who hasn’t agreed to certain terms laid out in the license agreement. Usually, those terms basically amount to “You can contribute, as long as you give use permission to use those contributions as we see fit."

If you have alarm bells going off in your head, you’re not alone. Like I alluded to at the beginning of this section, CLAs are a big source of controversy among people in the Free Software movement. A lot of people are rightly skeptical of CLA
