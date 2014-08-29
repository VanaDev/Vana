Vana
====

#### Background
koolk released TitanMS in 2008 and a group of developers wanted to create a better TitanMS source. The Vana team tried to contact koolk to work with them, but he didn't reply. So they decided to take it upon themselves to fork and develop a better TitanMS. At the same time, a generous cow named MooMoo set up a forum and code repository and these served as the development base for many years.

#### Why "Vana"?
When the original team decided that they wanted to fork, they needed a name. pawitp suggested the name "Vana", from "Vanadium" which is "Titanium" + 1 in the periodic table of elements.

#### What are your goals?
I can't speak for the entire Vana team and so many people have contributed to Vana over the years that I could not possibly begin to speak for them either. However, personally, my goal is to emulate as many versions of MapleStory between .1 and .92 as possible with as much accuracy as I can muster now that it's impossible to retrieve behavior.

All games eventually close their servers regardless of whether online play is the primary source of income or not. When that occurs, the game's contribution to culture is effectively lost because there is no longer a way to play the game. Nexon (the company that publishes MapleStory, you can find them at http://www.nexon.net/) is the sole source of game servers with which to connect and when they decide that it is no longer profitable, it is most likely that they will not open up their source code. It is also far more likely that they will not make available every version even if they do open up their source code. There may be additional legal hurdles in doing so with their proprietary code and other good reasons for this behavior, but the bottom line is that it is lost.

Server emulation allows users to run their own servers and interoperate with the game client, thus preserving the game for any that wish to experience this aspect of gaming culture in the future.

#### Isn't Vana illegal? Aren't you infringing Nexon's copyright?
**I want to make it very clear that I am not a lawyer. If you have any questions about laws, you should direct them toward a lawyer.**

**Additionally, I would like to make it clear that I'm speaking in terms of United States law and laws for your area may or may not be different. Again, it is very important that you consult a lawyer with legal questions.**

To the best of my understanding, this is neither illegal nor violates any copyright or intellectual property law in general. Copyright is frequently misunderstood. It is basically the right to control distribution of a given intellectual property. Vana does not use or distribute graphics, sounds, or any copyrightable content of a similar nature. The only thing Vana uses is data - numbers, names, etc. These things are not copyrightable because they are statements of fact.

Additionally, as all the code was written from the ground up using [clean room design](https://en.wikipedia.org/wiki/Clean_room_design), the code itself also does not violate the copyright on the official server's code.

The protocol used to communicate between server and client is encrypted and this generally falls under an access protection mechanism per the [Digital Millenium Copyright Act](https://en.wikipedia.org/wiki/Digital_Millennium_Copyright_Act) (or DMCA for short) regardless of how weak, strong, or broken it might be. Courts have ruled generally in favor of interoperability when tested, but this is by no means settled law.

I believe Nexon holds a patent for the .wz format itself (or at least it was held in 2008 when Vana was started), but Vana does not utilize this format and never has. There cannot be patent infringement on this particular patent if it's still a valid patent.

Trade secret law tends to require that the subject derives monetary value for not being known to the general public or to other persons that could derive monetary value from it AND that there have been reasonable steps to keep it a secret. It's difficult to argue that any particular functionality of a game server is a trade secret, however, even if that was the case, clean room design tends to put projects in the legal clear. No [non-disclosure agreement ](https://en.wikipedia.org/wiki/Non-disclosure_agreement) (NDA) was signed. The [end user license agreement](https://en.wikipedia.org/wiki/End-user_license_agreement) (EULA), if signed, may change the status. However, there is little legal clarity surrounding mass market EULAs in general.

To my knowledge, we are not violating any other forms of intellectual property law by virtue of them not even potentially applying at all.

In conclusion, it is my understanding that Vana is legal and we are not violating any intellectual property law. If these topics interest you, I recommend reading more over at the [Electronic Frontier Foundation website](https://www.eff.org/issues/coders/reverse-engineering-faq). They have a great deal of comprehensive and useful information related to the subject of reverse engineering.

#### How do I set up the software?
Please see [the wiki](https://github.com/VanaDev/Vana/wiki) which has all sorts of documentation including information for getting started.
