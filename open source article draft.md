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

