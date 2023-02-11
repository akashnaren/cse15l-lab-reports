# CSE 15L Lab Report  
*Akash Premkumar*
*PID: A16822598*
---
## Lab Report 3: Researching Commands
---
Objective: Discuss about commands.
---
In this lab, I have found that 

**What command did I choose?**
So for this assignment, the goal as stated above is quite simple which is to choose one of the commands and then go online and find 
4 commands or alternate ways that we expand on with two examples and disucss of course later of the usefullness and other aspects of the command. 

I ended up choosing the `grep` command. 

Now, this command is very interesting to me because its main functionality is a command line tool that will mainly print
the matching line to the output and color highlight the text it finds. 

Once I went to search the internet to understand this command deeper and find 4 interesting command-line options,
I found some interesting ones. 

Now to organize this, I will first start of by listing the 4 interesting commands and then will digress into them to satisfy all the requirements highlighted in the lab. 

FIRST: `grep  -v`

SECOND: `grep  -o`

THIRD: `grep  -w`

FOURTH: `grep  -i`

---
I do want to state that I am using files from `written_2`
Now here are two examples of these commands being used with two different examples:

FIRST: `grep  -v`

So in the command line terminal: I first inputted:
Example 1:
```
[cs15lwi23ahg@ieng6-203]:written_2: grep -R -v "Lucayans"

non-fiction/OUP/Castro/chQ.txt:Communities in Texas have formally observed Quinceañera birthdays for many generations, whereas such celebrations are not as common in California and other parts of the Southwest. Traditionally this ceremony serves as a coming-out party to indicate that a girl has reached womanhood and is ready for marriage. In the United States this is no longer the case, but the celebration does symbolize the transition from childhood to womanhood. In some celebrations a doll called la muñeca de los recuerdos (the doll of memories) or la última muñeca (the last doll) is given to the celebrant as a symbol of the childhood she is leaving behind. Some people see it as the last vestiges of childhood and la última muñeca as the last doll she will ever receive.
non-fiction/OUP/Castro/chQ.txt:Although not a religious sacrament, the celebrations of Quinceañeras take on a strong religious undertone. The ceremony usually includes a special Mass, where the parents give thanks for having a wonderful daughter, and she gives thanks for having a wonderful family, and the young woman may receive a formal blessing from the priest. The Mass is very similar to a wedding Mass, with the celebrant and her entourage slowly marching down the center aisle of the church. A ceremonial dinner and a dance with live band music usually follow. The celebrant wears a long white gown, similar to a wedding dress; has fifteen maids, damas, with their escorts, chambelanes; and sometimes performs a choreographed dance or waltz. Quinceañera celebrations are held in major cities with large Latino populations, such as Miami, San Antonio, Chicago, Los Angeles, and El Paso. These cities now offer many businesses that cater to Latino families planning Quinceañera celebrations. Although this is a family tradition and ritual, some families use the occasion to lavish on their daughters an extravagant day, never to be forgotten.
non-fiction/OUP/Castro/chQ.txt:Besides the traditional doll, other folkloric elements continue to be incorporated into Quinceañera ceremonies. In Idaho and Oregon, Eva Castellano has continued a tradition she learned from Mexico of making coronas (crowns) made of waxed and paper flowers to be worn by the young girl. Only unmarried girls wear the coronas, which symbolize innocence and purity. Much of the research on Quinceañeras shows that families want to maintain a cultural historical tradition, and the celebration of a daughter’s fifteenth birthday is a means of continuing cultural ties to a Latino heritage.
non-fiction/OUP/Fletcher/ch1.txt:In addition to embedding the states in the rule of law, the new constitutional order embarked on an affirmative program to ensure equality among those citizens subject to the jurisdiction of the United States. The heart of the new consensus is that the federal government, victorious in warfare, must continue its aggressive intervention in the lives of its citizens. It must protect the weak against the risk that they would slip into states of subordination resembling the past from which they sought to escape. According to the Thirteenth Amendment, there could never again be relationships of slavery or involuntary servitude in the United States. The federal government would have to be ever watchful to insure that this kind of slippage would never occur in the private relationships among citizens. Furthermore, under the “equal protection clause,” the states must recognize and promote the equality of those subject to their jurisdiction. To round out the commitment to equality, according to the Fifteenth Amendment ratified in 1870, the states could no longer deny voting rights to citizens on the grounds of their race, color, or previous condition of servitude.
non-fiction/OUP/Fletcher/ch1.txt:These objectives and guarantees are insufficient in themselves to create a constitution, a framework of government. One needs, in addition, a definition of legislative empowerment that would enable the federal government to realize its commitments. This definition is laid down in all three of the postbellum amendments. All three grant the power to Congress to enforce the basic framework “with appropriate legislation.” True, the new Congress takes as a given many of the provisions of the original Constitution. The new order inherits an operating Congress, Executive, and Judiciary. They would be recast in new functions, but the forms remained the same.
non-fiction/OUP/Fletcher/ch1.txt:The argument, then, is that the three Reconstruction Amendments enacted a second American constitution. The terms of this constitution, as culled from the amendments—with some rearrangement and leaving out historically specific clauses—can be stated in a few words:
non-fiction/OUP/Fletcher/ch1.txt:
non-fiction/OUP/Fletcher/ch1.txt:The Second American Constitution
non-fiction/OUP/Fletcher/ch1.txt:§1. All persons born or naturalized in the United States, and subject to the jurisdiction thereof, are citizens of the United States and of the State wherein they reside.
non-fiction/OUP/Fletcher/ch1.txt:§2. No State shall make or enforce any law which shall abridge the privileges or immunities of citizens of the United States.
non-fiction/OUP/Fletcher/ch1.txt:§3. No State shall deprive any person of life, liberty, or property, without due process of law.
non-fiction/OUP/Fletcher/ch1.txt:§4. No State shall deny to any person within its jurisdiction the equal protection of the laws. 
non-fiction/OUP/Fletcher/ch1.txt:§5. Neither slavery nor involuntary servitude, except as a punishment for crime whereof the party shall have been duly convicted, shall exist within the United States.
non-fiction/OUP/Fletcher/ch1.txt:§6. The right of citizens of the United States to vote shall not be denied or abridged by the United States or by any State on account of race, color, or previous condition of servitude.
non-fiction/OUP/Fletcher/ch1.txt:§7. The Congress shall have power to enforce the foregoing provisions by appropriate legislation.
non-fiction/OUP/Fletcher/ch1.txt:
non-fiction/OUP/Fletcher/ch1.txt:These seven propositions summarize the enduring content of the Reconstruction Amendments.13 The key provisions of these amendments define political membership, articulate basic rights, and provide an ambit of legislative competence. So reformed, the American system of government would be able to protect individual rights as well as promote the equality of all persons who survived the war. Of course, we must assume a set of institutions—a Congress, an Executive, and a Judiciary—that will continue to function according to the terms of their initial creation.
non-fiction/OUP/Fletcher/ch1.txt:Still, there is something missing in this filtering off of the three Reconstruction Amendments and calling them a separate constitution. The missing factor is the consciousness of setting forth a new framework of government, a structure based on values fundamentally different from those that went before. To find that consciousness, we need to turn, I wish to argue, to the critical message of the Civil War, the address that would generate a new normative world in which to make sense of the epic war that consumed America from the firing on Fort Sumter to the surrender at Appomattox. The new Nomos, the new framework of values that necessitated a new constitution, comes forth in one of the great prayers of the American civil religion, the Gettysburg Address. It is worth recalling some of the enduring phrases of this civil prayer, the incantations that reverberated in American consciousness:
non-fiction/OUP/Fletcher/ch1.txt:
non-fiction/OUP/Fletcher/ch1.txt:Four score and seven years ago our fathers brought forth on this continent a new nation. . . .
non-fiction/OUP/Fletcher/ch1.txt:[This nation was] conceived in liberty and dedicated to the proposition that all men are created equal.
non-fiction/OUP/Fletcher/ch1.txt:From these honored dead we take increased devotion to that cause for which they gave the last full measure of devotion.
non-fiction/OUP/Fletcher/ch1.txt:We resolve that these dead shall not have died in vain, that this nation, under God, shall have a new birth of freedom. . . .
non-fiction/OUP/Fletcher/ch1.txt:Government of the people, by the people, for the people shall not perish from the earth.
non-fiction/OUP/Fletcher/ch1.txt:In the ensuing chapters, we will look at these words and the entire address in greater detail. For now, I wish to make the unusual claim that these revered words serve as the preamble for the constitutional order that emerged from the unification of the nation. They are a preamble in much the same sense that the language beginning “Conscious of our responsibility before God and humanity” provides the organizing principle of the new German constitution or the following words echo in memory as the convening of the Philadelphia Constitution:
non-fiction/OUP/Castro/chV.txt:La Virgen de Guadalupe
```


Example 2:
```
[cs15lwi23ahg@ieng6-203]:written_2: grep -R -v "Century"

non-fiction/OUP/Kauffman/ch9.txt:Laws for any biosphere extend, presumably, to laws for any economy. Nor should that be surprising. The economy is based on advantages of trade. But those advantages accrue no more to humans exchanging apples and oranges than to root nodules and fungi exchanging sugar and fixed nitrogen such that both make enhanced livings. Thus, economics must partake of the vast creativity of the universe. Molecules, species, and economic systems are advancing into an adjacent possible. In all cases, one senses a secular trend for diversity to increase, hence for the dimensionality of the adjacent possible to increase in our nonergodic journey.
non-fiction/OUP/Kauffman/ch9.txt:Perhaps again we glimpse a fourth law.
non-fiction/OUP/Kauffman/ch9.txt:
non-fiction/OUP/Kauffman/ch9.txt:
non-fiction/OUP/Kauffman/ch9.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:the look of architecture
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:one
non-fiction/OUP/Rybczynski/ch1.txt:dressing up
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:
non-fiction/OUP/Rybczynski/ch1.txt:Architecture is hard to define. Goethe called it music frozen in space, which, while it captures a sense of rhythm, is too one-dimensional. And it relegates the mother of the arts to an inferior position; just as well to describe music as melted architecture. Nietzsche believed that architecture reflected his pride, man’s triumph over gravity, and his will to power. This notion applies to many buildings, from Gothic cathedrals to skyscrapers, but it is too, well, Nietzschean. The British master Edwin Lutyens referred to architecture as a sort of play: “In architecture, Palladio is the game!” Le Corbusier described his art as “the masterly, correct and magnificent play of masses brought together in light,” which is a good description of one of his own buildings. I am partial to Sir Henry Wotton’s definition. Wotton, who lived a long time in Venice and was a lover of architecture though not an architect, published a treatise on the subject in 1642. “In Architecture, as in all other Operative Arts, the end must direct the Operation,” he wrote. “The end is to build well. Well-building hath three conditions: Commoditie, Firmeness, and Delight.”
non-fiction/OUP/Rybczynski/ch1.txt:Sir Henry’s description, which was based on the writings of the Roman architect Vitruvius, appeals to me because it emphasizes the complexity of the building art. To begin with, architecture has not one but three distinct purposes: to shelter human activity (commodity), to durably challenge gravity and the elements (firmness), and to be an object of beauty (delight). Architecture is always a synthesis of the three. However, the fulfillment of one purpose does not guarantee the satisfaction of the others. There are homely sturdy buildings and beautiful flimsy ones. A well-planned building can be ugly just as a beautiful building can function poorly. Form does not, contrary to Louis Sullivan’s hoary maxim, follow function.
```

What is `grep  -v` doing?: 
Alright, I understand that this must be a lot to take in but I want to highlight the main functionality of `grep  -v` which is used to search for a specific pattern in a file or input and display the matching lines. The -v option is used to invert the match, meaning it will display lines that do NOT match the pattern.

Why is `grep  -v` useful?: 
You can eliminate lines from the output that match the given pattern by using the grep -v option. It's frequently used to filter away lines in which you're not interested and show only the pertinent data. Assume, for instance, that you have a file called fan.txt that contains a lot of log information. You only want to see the lines that don't have the term "error" in them. 


---

SECOND: `grep  -o`

Example 1: 
```
[cs15lwi23ahg@ieng6-203]:written_2:427$ grep -R -o "Century"
non-fiction/OUP/Castro/chR.txt:Century
travel_guides/berlitz1/HistoryEgypt.txt:Century
travel_guides/berlitz1/HistoryFWI.txt:Century
travel_guides/berlitz1/HistoryGreek.txt:Century
travel_guides/berlitz1/HistoryHongKong.txt:Century
travel_guides/berlitz1/HistoryHongKong.txt:Century
travel_guides/berlitz1/HistoryJerusalem.txt:Century
travel_guides/berlitz1/HistoryMalaysia.txt:Century
travel_guides/berlitz1/HistoryMalaysia.txt:Century
travel_guides/berlitz1/WhatToLakeDistrict.txt:Century
travel_guides/berlitz1/WhatToLosAngeles.txt:Century
travel_guides/berlitz1/WhatToLosAngeles.txt:Century
travel_guides/berlitz1/WhatToLosAngeles.txt:Century
travel_guides/berlitz1/WhatToLosAngeles.txt:Century
travel_guides/berlitz1/WhereToItaly.txt:Century
travel_guides/berlitz1/WhereToLakeDistrict.txt:Century
travel_guides/berlitz1/WhereToLosAngeles.txt:Century
travel_guides/berlitz1/WhereToLosAngeles.txt:Century
travel_guides/berlitz1/WhereToLosAngeles.txt:Century
travel_guides/berlitz2/Amsterdam-History.txt:Century
travel_guides/berlitz2/Athens-History.txt:Century
travel_guides/berlitz2/Bahamas-History.txt:Century
travel_guides/berlitz2/California-WhatToDo.txt:Century
travel_guides/berlitz2/California-WhatToDo.txt:Century
travel_guides/berlitz2/California-WhereToGo.txt:Century
travel_guides/berlitz2/Canada-History.txt:Century
travel_guides/berlitz2/CstaBlanca-WhereToGo.txt:Century
[cs15lwi23ahg@ieng6-203]:written_2:428$ 

```

Example 2:
```
[cs15lwi23ahg@ieng6-203]:written_2:428$ grep -R -o "Bahamas"
travel_guides/berlitz1/WhatToFWI.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-History.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-Intro.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Bahamas
travel_guides/berlitz2/Canada-WhereToGo.txt:Bahamas
[cs15lwi23ahg@ieng6-203]:written_2:429$ 
```

What is `grep  -o` doing?: 
When looking for a pattern in a file, the grep -o option is used to display only the matching portion of each line rather than the complete line.

Why is `grep  -o` useful?: 
When you simply need to view the matched strings and not the complete line, this option is helpful. This can let you focus on one element of the data without getting distracted by the remainder of the line or extract specific information from a big amount of text data. When you wish to extract specific data from a file for use in additional processing, such as piping the output to another command, the grep -o option can be helpful.


---
THIRD: `grep  -w`

Example 1:


```
[cs15lwi23ahg@ieng6-203]:written_2:430$ grep -R -w "Bahamas"
travel_guides/berlitz1/WhatToFWI.txt:        waters off the Bahamas, Puerto Rico, and the Virgin Islands, but the
travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
travel_guides/berlitz2/Bahamas-History.txt:English sea captains also came to know the beautiful but deserted Bahamian islands during the 17th century. England’s first formal move was on 30 October 1629, when Charles I granted the Bahamas and a chunk of the American south to his Attorney General, Sir Robert Health. But nothing came of that, nor of a rival French move in 1633 when Cardinal Richelieu, the 17th-century French statesman, tried claiming the islands for France.
travel_guides/berlitz2/Bahamas-History.txt:In 1648 a group of English Puritans from Bermuda, led by William Sayle, sailed to Bahamian waters and established the first permanent European settlement on the island they named Eleutheria (now Eleuthera) after the Greek word for freedom. The 70 colonists called themselves the Eleutherian Adventurers, but life was very difficult and the colony never flourished, though Sayle was long honored for the effort. In 1666 a smaller island (called Sayle’s island) with a fine harbor was settled by Bermudians and renamed New Providence. It was later to become known as Nassau, capital of the Bahamas.
travel_guides/berlitz2/Bahamas-History.txt:Most feared of the 1,000 or more swashbucklers operating from the New Providence lair was Edward Teach, better known as Blackbeard. Today you can visit a tower east of Nassau named after him. Another two infamous pirates were women: Anne Bonney and Mary Read had exceptionally bloodthirsty reputations and are still celebrated in the Bahamas. The pirates raided anything on the sea, living totally lawless — and often not very lengthy — lives. Moreover, there was not always a clear distinction between pirates and privateers, the latter officially authorized by their governments to plunder enemy ships during time of war. Anarchy and confusion reigned throughout the area.
travel_guides/berlitz2/Bahamas-History.txt:In 1718, shortly after the Bahamas became a crown colony, Captain Woodes Rogers, a renowned ex-privateer, was named the first royal governor. Arriving in Nassau with a powerful force and promising amnesty for surrender, he became a legend by cleaning out many of the pirates and establishing some order. This incident inspired the national motto Expulsis Piratis — Restituta Commercia (Pirates Expelled — Commerce Restored), which was retained until 1971.
travel_guides/berlitz2/Bahamas-History.txt:A few years later Rogers quit the islands only to return for a second time in 1729 after a period of bankruptcy and debtor’s prison in England. Before he died in Nassau in 1732 he had summoned the Bahamas’ first official Assembly, composed of 16 elected members for New Providence and four each for Harbour Island and Eleuthera. At this time, in all the Bahamas there were only about 2,000 settlers.
travel_guides/berlitz2/Bahamas-History.txt:When the 13 American colonies, enraged by the Stamp Tax, got into the war that eventually brought independence, the Bahamas somewhat reluctantly found itself on England’s side. But reluctance dissolved as profits from privateering once again flowed into Nassau. This time the plundered vessels were American, but not all the victories were won by the privateers. On 3 March 1776, a rebel squadron under Commodore Esek Hopkins arrived and occupied Nassau for two weeks, a bloodless undertaking that emptied the island’s forts of arms and other military supplies. A smaller and equally non-violent American operation against the town in January 1778 lasted less than three days.
travel_guides/berlitz2/Bahamas-History.txt:As the colonies’ war effort picked up steam, both France and Spain weighed in against the British. In May 1782, New Providence surrendered to a large Spanish-American invasion fleet from Cuba and for the next year a Spanish governor ruled the Bahamas.
travel_guides/berlitz2/Bahamas-History.txt:News traveled slowly in those days. The Treaty of Versailles in 1783 formally restored the Bahamas to the British, but actual liberation came through a famous escapade that would never have happened in the age of the telegraph. Lieutenant-Colonel Andrew Deveaux, a loyalist from South Carolina, sailed from Florida with six ships, picked up men and fishing boats at Harbour Island and Eleuthera, and “invaded” Nassau. Though vastly outnumbered and outgunned, Deveaux employed elaborate ruses with his little boats to convince the Spanish defenders that his force was overpowering. The humiliating Spanish surrender is proudly recalled in Bahamian history, even though it was all unnecessary: the peace treaty had been signed the previous week.
travel_guides/berlitz2/Bahamas-History.txt:Deveaux was the first of some 7,000 loyalists who, with slaves and the promise of land grants, came to the Bahamas from the southern American colonies in the wake of the English defeat in the Revolutionary War. This influx profoundly affected the islands. A number of prominent Bahamians today are the descendants of loyalists or their slaves. As a reward for his efforts, Deveaux was given acreage on both New Providence and Cat Island. Other loyalists set up cotton plantations on various islands, and slaves soon became the majority of the population.
travel_guides/berlitz2/Bahamas-History.txt:In the 1780s well over 100 cotton plantations were founded and flourished around the Bahamas. Prosperity from the land finally seemed a possibility. But by the end of the century cotton had fallen victim to a devastating plague of chenille bugs and exhaustion of the weak soil. Most of the planters left the islands and depression returned, only partly relieved by “wrecking,” the freelance business of salvaging cargo from the ships forever running aground in the dangerous Bahamian waters. (Some ships were deliberately misguided by lights on shore; Nassau harbor did not have a proper lighthouse until 1816).
travel_guides/berlitz2/Bahamas-History.txt:Slavery in the Bahamas was not as widespread or as vicious as on many sugar islands in the Caribbean. Some slaves were voluntarily freed or sold their liberty by loyalist owners. After 1804, no slaves were imported into the Bahamas. By 1822, the first registration counted 10,808 slaves on the 17 inhabited islands or island clusters. After Parliament in London abolished slavery in 1833, there was a transitional apprenticeship period of 5 years before all slaves in the colony became fully free on 1 August 1838. This included a few thousand slaves from ships captured by the Royal Navy. They were housed in specially founded settlements on New Providence and the Out Islands.
travel_guides/berlitz2/Bahamas-History.txt:Over the centuries, trouble on the nearby American continent has often meant good news for the Bahamas. When Lincoln ordered a blockade of the southern states in 1861 after the outbreak of the Civil War, the Bahamas quickly boomed. Nassau harbor was busy with ships unloading Confederate cotton and tobacco and taking aboard arms, medicine, and manufactured goods, mainly from Europe, to be run back through the northern blockade. As the war went on, speedy and camouflaged contraband vessels were built to slip past the ever-increasing Federal patrols. Profits from blockade running were incredible, and Nassau went wild. But the extravagant parties and carefree spending stopped abruptly with the North’s victory in 1865. Late the following year an immense hurricane sent a tidal wave over Hog Island (today Paradise Island), smashing Nassau’s flimsy buildings and ruining crops. Other islands were also devastated. As the Bahamas sank back into economic doldrums, citizens turned to agriculture, fishing, or salt raking. The spread of lighthouses and decent navigational charts had crippled the old standby, the wrecking trade.
travel_guides/berlitz2/Bahamas-History.txt:Prohibition brought gloom to millions of Americans, but for the Bahamas it brought the biggest bonanza in history. At the end of 1919, Congress passed the Volstead Act outlawing the manufacture, sale, or transport of intoxicating beverages. The Bahamian islands (where the temperance crusade never had much chance) were perfectly placed to help thirsty Americans. For 14 years, until the controversial law was finally repealed, bootlegging changed Nassau, West End on Grand Bahama, and Bimini beyond recognition. With just as much gusto as they’d shown in the past for wrecking, privateering, and blockade running, Bahamians took to the seas with illegal liquor. Trying to outwit the US Coast Guard was risky but enormously profitable. Fortunes were made by respected Bahamian families turned liquor merchants, rum-running boat captains, notorious criminals, shady ladies, and the Bahamas government (which collected duty on temporarily imported drink).
travel_guides/berlitz2/Bahamas-History.txt:When the boom suddenly came to an end with the worldwide depression and the repeal of Prohibition in 1933, unemployment rose again, despite the first significant tourism the Bahamas had known.
travel_guides/berlitz2/Bahamas-History.txt:In some respects, World War II put the Bahamas on the international map. The colony was chosen to have two of the sites Britain leased to the United States under Franklin D. Roosevelt’s “destroyers for bases” deal in 1940. Allied forces operated submarine-hunting and air-sea rescue stations on the islands; Royal Air Force pilots and Royal Navy frogmen were trained here, and much trans-Atlantic air traffic passed through the Bahamas.
travel_guides/berlitz2/Bahamas-History.txt:In 1943 the Duke intervened in the investigation of the murder of Canadian multimillionaire Sir Harry Oakes, a longtime benefactor of the Bahamas who gave his name to Nassau’s first airfield. The sensational case, never solved, made world headlines for the Bahamas and is still discussed today.
travel_guides/berlitz2/Bahamas-History.txt:After the construction of the first wartime American air bases on New Providence was completed, thousands of Bahamians left to work on farms and in factories in the United States, a migration that continued well into the postwar era. But employment opportunities began to grow at home. From 1950, a promotion campaign under Sir Stafford Sands was hugely successful in attracting tourists to the Bahamas. Denied the sun, sand, and sin of Cuba by Fidel Castro’s takeover in 1959, hundreds of thousands of American vacationers set their sights on the Bahamas. The influx was spurred by gambling, airport and harbor improvement on the major islands, and the creation of the modern city of Freeport (which had been set in motion by the so-called Hawksbill Creek Agreement of 1955). Resort hotels began to appear and the advent of air-conditioning improved the often stifling humidity of summer.
travel_guides/berlitz2/Bahamas-History.txt:Under a new constitution in 1964, the colony was given self-government with a ministerial-parliamentary system. In 1967 elections, the Progressive Liberal Party was victorious, its leader Lynden O. Pindling becoming premier. Following a constitutional conference in London, the Bahamas became fully independent on July 10, 1973, and is now a member of the United Nations and the British Commonwealth. In August 1992 the Progressive Liberal Party, still headed by Lynden O. Pindling, was toppled by the Free National Movement after 25 years in power. Today’s prime minister is Hubert Ingraham.
travel_guides/berlitz2/Bahamas-History.txt:Since independence the Bahamas has kept British systems of judiciary and government yet has moved closer economically to its near neighbor, the US. The Bahamian Government has deliberately pursued tourism as the major industry of the Bahamian commonwealth and is happy to welcome many millions of visitors to its shores. The growth in cruise traffic has been particularly strong. The other islands, called the Family Islands by the government but generally referred to as the Out Islands by the tourist trade, have not shared this huge growth in numbers of visitors. Together they offer tourists almost any form of vacation experience, from the bustle of the busy city to the silence of the desert island.
travel_guides/berlitz2/Bahamas-History.txt:In the 1990s the Bahamian Government began working on ways to expand the country’s economic base. While tourism remains a top priority — the opening of the vast Atlantis resort on Paradise Island leaves little doubt about that — a number of measures have also been taken to make the country’s laws and tax codes more attractive to offshore investors. As a result, money has been making its way into financial institutions on the Bahamas from around the world, and a large number of foreign banks have opened brand-new air-conditioned offices surrounded by carefully manicured gardens.
travel_guides/berlitz2/Bahamas-History.txt:One of the major questions still facing the Bahamas is how to accommodate the increasing numbers of tourists while still preserving the special architectural and social heritage of the Out Islands, as well as of the major towns like Nassau. Will it be possible to enjoy the natural splendors of places like Inagua without upsetting the delicate balance of nature? At the moment, the thinking is that it’s perhaps best to leave these smaller, less developed islands in peace.
travel_guides/berlitz2/Bahamas-Intro.txt:The Bahamas and the Bahamians
travel_guides/berlitz2/Bahamas-Intro.txt:Like a handful of emeralds scattered across blue velvet, the verdant islands of the Commonwealth of the Bahamas stretch across 100,000 sq miles (259,000 sq km) of the Atlantic Ocean. The 700 islands and numerous smaller cays (pronounced “keys”) that comprise this semitropical archipelago start 55 miles (90 km) east of Palm Beach, Florida, and arc 600 miles (970 km) southeast toward eastern Cuba and Haiti, like a series of stepping stones linking North America with the Caribbean.
travel_guides/berlitz2/Bahamas-Intro.txt:The Bahamas islands are the flattened peaks of a huge ancient mountain range that once towered many thousands of feet into the sky. They now lie low in the water, the highest point — Mount Alvernia on Cat Island — being only 206 ft (65 m) above sea level. The eastern coastlines of the islands break the long tidal fetch that travels across the Atlantic; on the sheltered western coastline, coral outcrops have produced vast shallow sand banks that reflect waters of myriad translucent blues and greens.
travel_guides/berlitz2/Bahamas-Intro.txt:Indeed, it was these characteristic shallow banks that gave the Bahamas islands their name. When Spanish explorers came to map the area in the 16th century, they named the area baja mar, or shallow seas, as a warning to the galleons that would be sailing through the waters. The name was later anglicized and the Bahamas were born.
travel_guides/berlitz2/Bahamas-Intro.txt:The islands of the Bahamas were claimed by the English, but hundreds of secret coves became home to pirates and smugglers who turned their backs on nationality to enter the brotherhood of buccaneers. They ruled the seas, plundering ships at will, and then spent their ill-gotten gains in the bars and brothels of Nassau town, the main settlement.
travel_guides/berlitz2/Bahamas-Intro.txt:Later, as the English colonies of North America fought for independence, the islands became a refuge for fleeing loyalists who sought to make a new life on these remote, picturesque cays. Cotton production brought a number of slaves to the islands, but the crops proved to be poor and depleted the already weak soil. Sponge gathering was devastated after a fungus attacked the crop, and sisal was produced more cheaply in South America. The population eked out a living, but little more than that. Things changed in the 1920s, however, when the Bahamas profited from the American policy of Prohibition. Rum-running became a major industry, and well-to-do Americans began making the short trip to the Bahamas to be able to drink legally, and to indulge in other pleasures.
travel_guides/berlitz2/Bahamas-Intro.txt:Since World War II, the Bahamas has worked hard to extend the service it provided during Prohibition and has turned itself into a “paradise” for holiday-makers. The dazzling beaches are covered with fine sand that ranges from bright white to pastel pink. The sun shines year-round, with temperatures ranging from the high 60s to the high 80s fahrenheit. To these natural ingredients have been added just about every amenity and service needed for the perfect holiday. Everything centers on New Providence, where most of the tourists stay and half of the Bahamian population lives. One of the largest cruise ports in the world, Nassau can accommodate 15 large ships at one time. English “pomp,” stout forts, and colonial houses attract history buffs. Grand Bahama, the second most populous island, has Freeport–Lucaya, Nassau’s younger, less genteel “American” cousin; nightlife here is more lavish and audacious than in Nassau. Both islands have large resort hotels that offer water-sports, floor shows, and casinos where you can enjoy the thrill of winning or the dejection of losing. Golf courses entice you to lower your handicap. Tour buses plow a path around the attractions, and duty-free shops tempt you to buy that little luxury item you’ve been denying yourself for so long. Hundreds of day-trippers cruise to both islands, eager to do it all before they have to get back on the boat.
travel_guides/berlitz2/Bahamas-Intro.txt:The lure of the Bahamas is, of course, as much about the sea as it is about the land. The waters of the western Atlantic are still some of the clearest and most beautiful in the world. In summer the shallows are glassy still and range from azure blue to emerald green; the deep ocean channels reflect a deep blue that can best be appreciated from the air. The sandy shallows are ideal for swimming and snorkeling, and since the development of scuba (an acronym for self-contained underwater breathing apparatus) gear in the 1930s, the seas around the Bahamas have become a top destination for diving enthusiasts from around the world. 
travel_guides/berlitz2/Bahamas-Intro.txt:The waters of the Bahamas support a vast range of life and contain 5 percent of the world’s coral. Diving around the reef surfaces and the vertical reef walls is complemented by many ship wrecks and artificial sites — large, concrete blocks which are placed on the sea bed to encourage coral growth — surrounding the islands. Fish species mass in the vast shallows along with urchins and starfish. Yet deep ocean channels cut between some island groups — the Tongue of the Ocean between Andros and New Providence, for example, is 6,000 ft (2,000 m) deep — and these provide a thoroughfare for a number of large fish and marine mammal species, such as sharks, rays, dolphins, and turtles.
travel_guides/berlitz2/Bahamas-Intro.txt:On top of the water, the shallow channels and sheltered seas provide ideal waters for sailing and cruising. Hundreds of unmanned cays offer idyllic destinations and mooring points. The desert island you always dreamed about is somewhere in the Bahamas — the Exumas themselves have one cay for every day of year, and that is only one part of the vast Commonwealth. Many lie only a few hours sailing time from the hubbub of Nassau.
travel_guides/berlitz2/Bahamas-Intro.txt:Every island has its own individual character, forged by a unique history and development, in fact the Bahamas could be said to be several different holiday experiences in one country, so it’s important to choose your island carefully to get the kind of holiday you want.
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Crafts. Bahamians have always had to fend for themselves, and this resourcefulness has led them to become proficient at a number of practical handicrafts, many of which make beautiful souvenirs. Straw goods are the most ubiquitous. The Seminole Indians of Red Bay on Andros are said to produce the finest work on the Bahamas, though each island has its own individual patterns and differences in style. It is still possible to watch the women at work on the islands of Andros and at George Town on Exuma. Straw work can be bought from small workshops in people’s homes or from the better quality straw vendors in Nassau. Prices can be high, but even small bowls make beautiful and practical reminders of your trip. The handmade pieces are likely to become rare within a couple of generations, because so few young Bahamian women are now taking up the craft. Be aware that much of the straw work, particularly the mass-market goods like hats and bags, is not made in the Bahamas but in Taiwan and China. If you want to be sure of getting genuine Bahamian straw work, buy from places such as The Plait Lady, who has a shop on Bay Street in Nassau; you’ll have to pay a little more but you’ll be sure you’re getting an authentic handmade work of art.
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Seashells and sponges can be found in every market and souvenir shop in the Bahamas. They make beautiful, natural souvenirs, but some may come from protected species. Do not buy coral or turtle products as this is illegal and only encourages further damage to these delicate and rare forms of sea life.
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Clothing. If you like, you could take an empty bag and buy your holiday wardrobe when you arrive in the Bahamas. Many of the shops on Bay Street, at the International Bazaar, and the Port Lucaya Market Place offer beachwear and T-shirts galore. Sarongs, printed dresses, and shirts in light fabrics are sold in almost every craft stall in the straw markets. Light-cotton Androsia clothing, made on Andros, is perfect for the Bahamian climate; you’ll find these items all over the Bahamas.
travel_guides/berlitz2/Bahamas-WhatToDo.txt:Duty-free luxury goods. Both New Providence and Grand Bahama have a good range of luxury duty-free goods for sale. The shops tend to be clustered together, which makes it easy to compare prices and quality before you buy; in Nassau you’ll find them on Bay Street and in the International Bazaar, and in the Port Lucaya Market on Grand Bahama. Things to keep an eye out for include gold and silver jewelry and such gem stones as diamonds, sapphires, and emeralds set in gold from Christian Dior and other leading designers. Abaco Gold is a range of jewelry designed and sold only in the Bahamas and unusual pieces such as rare gold and silver coins brought from treasure found on the seabed, and mounted in gold to be worn as pendants or brooches. If it’s time for a new timepiece, you can choose from a comprehensive range of watches by names such as Rolex, Breitling, and Tag Hauer. Fragrances from around the world, fine crystal, and European leather goods are also on display in most of the shops.
```
Example 2:

```
[cs15lwi23ahg@ieng6-203]:written_2:435$ grep -R -w "islands"
travel_guides/berlitz2/Bahamas-WhereToGo.txt:The Exumas are divided into three distinct sections: Great Exuma Island, Little Exuma Island, and the Exhuma Cays, which lie north of the main islands. The capital, George Town, on Great Exuma Island, is served by regular flights from Nassau and makes the most convenient base for non-sailors. It has a sleepy and laid-back atmosphere and offers a couple of hotels and restaurants. A compact straw and vegetable market sits at the main crossroads. The town lies on the coast at Elizabeth Harbour, a large, sheltered stretch of water that is a popular stopping off point for sailors. The quiet town comes to life every April when it hosts the Family Island Regatta. Thousands of Bahamian working boats fill Elizabeth Harbour, their crews vying for the right to call themselves champion of the regatta.
travel_guides/berlitz2/Bahamas-WhereToGo.txt:Traveling north from George Town you’ll pass Three Sisters Rock, a formation that lies just offshore from a sandy beach; the three rocks are said to represent three sisters who drowned in the waters here. Gradually the island narrows, and past Rolleville, Great Exuma gives way to the Exuma Cays, a ribbon of small islands of which only four are inhabited. Stanial Cay offers accommodation as well as yachting supplies. It also has an airfield with regular service from Fort Lauderdale on the Florida coast. These cays are home to the endangered iguana along with numerous rare plant species. A 22-mile (35-km) stretch north of Conch Cut has been protected for future generations by the creation of the Exuma Cays Land and Sea Park, 175 sq miles (453 sq km) of land and sea that includes some of the best yet most remote beaches in the Bahamas. The park is only accessible by boat — except for the occasional powerboats bringing passengers over from Nassau for a day of snorkeling and picnics on the beach, the only sounds you’ll hear will be the wind whipping through the sails of yachts anchored offshore.
```




---

FOURTH: `grep  -i`

Example 1:
```
[cs15lwi23ahg@ieng6-203]:written_2:436$ grep -R -i "Lucayans"
travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
[cs15lwi23ahg@ieng6-203]:written_2:437$ grep -R -i "lucayans"
travel_guides/berlitz2/Bahamas-History.txt:Centuries before the arrival of Columbus, a peaceful Amerindian people who called themselves the Luccucairi had settled in the Bahamas. Originally from South America, they had traveled up through the Caribbean islands, surviving by cultivating modest crops and from what they caught from sea and shore. Nothing in the experience of these gentle people could have prepared them for the arrival of the Pinta, the Niña, and the Santa Maria at San Salvador on 12 October 1492. Columbus believed that he had reached the East Indies and mistakenly called these people Indians. We know them today as the Lucayans. Columbus claimed the island and others in the Bahamas for his royal Spanish patrons, but not finding the gold and other riches he was seeking, he stayed for only two weeks before sailing towards Cuba.
travel_guides/berlitz2/Bahamas-History.txt:The Spaniards never bothered to settle in the Bahamas, but the number of shipwrecks attest that their galleons frequently passed through the archipelago en route to and from the Caribbean, Florida, Bermuda, and their home ports. On Eleuthera the explorers dug a fresh-water well — at a spot now known as “Spanish Wells” — which was used to replenish the supplies of water on their ships before they began the long journey back to Europe with their cargoes of South American gold. As for the Lucayans, within 25 years all of them, perhaps some 30,000 people, were removed from the Bahamas to work — and die — in Spanish gold mines and on farms and pearl fisheries on Hispaniola (Haiti), Cuba, and elsewhere in the Caribbean.
[cs15lwi23ahg@ieng6-203]:written_2:438$ 
```

Example 2:
```
[cs15lwi23ahg@ieng6-203]:written_2:438$ grep -R -i "canada"
non-fiction/OUP/Abernathy/ch1.txt:Proposition 5:  Even with full implementation of GATT, a viable apparel industry can remain in North America, drawing on a range of production processes in the United States, Canada, Mexico, the Caribbean, and Latin America.
non-fiction/OUP/Fletcher/ch9.txt:The same could be said of devotion to the nation. The state must engage in some elementary gestures of national pride. It must define and disseminate a flag, a national anthem, and celebrate holidays such as the Fourth of July, Veterans’ Day, and the birthdays of great national leaders. Nations that fail to do these things have trouble melding their people into a single culture of national identity. A good example is Israel, which has yet to find a holiday that Jews and Arabs can celebrate together. We live in a time of national disintegration—witness Czechoslovakia, the Soviet Union, and the near-misses in Canada—and, therefore, the state is properly advised to cultivate a common identity and a sense of shared history and destiny.
non-fiction/OUP/Fletcher/ch9.txt:There is no doubt that free speech has its victims, and in most European societies and in Canada, the courts rush in to protect the victims against being offended. A good example is the way every major jurisdiction outside the United States treats Holocaust denial. Someone publishes a book saying that Auschwitz never happened, that it is a lie propagated by the Jews. This is a punishable act in Germany, France, Israel, the Netherlands, Canada—just about everywhere where people believe that the government must intervene in order to protect those who might be disturbed and offended by the obscene lie. By intervening and putting the Holocaust denier on trial, of course, they only broadcast the lie to a larger audience, and they convert the mad dissident into a martyr in his own circle.
non-fiction/OUP/Kauffman/ch3.txt:Most broadly, I believe a general biology awaits founding. And I believe that autonomous agents will prove central to that eVort. The next feature of autonomous agents that I will note in closing this chapter will be central to any general biology. Precisely because an autonomous agent links exergonic and endergonic reactions in work cycles, the breakdown of high-energy sources here can be used to build up structure and organization there. Indeed, the coevolution of autonomous agents naturally leads to a linked web of exergonic and endergonic reactions within and between the autonomous agents. Breakdown of this stuV here is linked to the excess build up of that stuV there. By these linkages, sunlight spattered carelessly on this swirl of stuV ninety-three million miles from our average star cumulates into the wondrous structure of the giant redwoods, tall on the western slopes of the United States and Canada. Precisely because autonomous agents carry out work cycles, they = we = literally build a biosphere.
non-fiction/OUP/Rybczynski/ch2.txt:Gothic has not—so far—come back into fashion. Early in his career, Paul Rudolph designed a building for Wellesley College that attempted to relate architecturally to the Collegiate Gothic surroundings. It was his first large commission, and it was not a success. “Wellesley shook me,” Rudolph later recalled, “and I returned to the International Style in my next building.”3 Eero Saarinen built a Gothicized dormitory at Vasser. Philip Johnson and John Burgee designed a Gothic-inspired skyscraper in Pittsburgh that was a giant abstracted glass version of the British Houses of Parliament. This was one of several stylistic forays that Johnson and Burgee made in the 1980s, including a Chippendale-top skyscraper in New York, a French Provincial high-rise in Dallas, and a neo-Burnhamesque tower in Chicago. None is particularly satisfactory, perhaps because they lack conviction. Moshe Safdie’s National Gallery of Canada in Ottawa is more successful. It mimics the Gothic chapter house-cum-library of the adjacent parliament buildings in a crystalline structure of steel and glass. This episode in Safdie’s oeuvre was unique, however, and Gothicized forms do not reappear in his later buildings.
non-fiction/OUP/Rybczynski/ch3.txt:I mentioned the New York Public Library competition when I gave a public lecture in connection with a recent architectural competition for the new Salt Lake City Public Library. The library board had conducted a national search for an architect, visited new libraries across the country, and solicited proposals from prominent architects. They had narrowed their list to four firms: Charles Gwathmey and Robert Siegel are respected New York architects with a long record of university buildings and museums, including a new library of science, industry, and business for the New York Public Library system. Moshe Safdie had built major civic buildings in Israel, Canada, and the United States, and recently completed the public library in Vancouver, British Columbia. Moore Ruble Yudell is a Los Angeles firm founded by the late Charles Moore, with whom John Ruble and Buzz Yudell built several university libraries and a public library in Berlin. Will Bruder, the least well-known of the four, is a southwesterner and the architect of the new, well-regarded Phoenix Public Library.
travel_guides/berlitz1/HandRJamaica.txt:        Canada); fax 957-5289; e-mail <info@breezes.com>; website
travel_guides/berlitz1/HandRJamaica.txt:        953-9153, 800-330-8272 (toll-free from US and Canada); fax 953-2244;
travel_guides/berlitz1/HandRJamaica.txt:        Tel. 993-2602, 993-2705, 800-633-3284 (toll-free from US or Canada);
travel_guides/berlitz1/HandRJamaica.txt:        Tel. 965-3145, 965-3185, 800-OUTPOST (toll-free from US and Canada);
travel_guides/berlitz1/HandRJamaica.txt:        Andrew’s; Tel. 944-8400, 800-OUTPOST (toll-free from US and Canada);
travel_guides/berlitz1/HandRMadrid.txt:        in the U.S. and Canada, or 91/521 28 57; fax 91/532 87 76; web site
travel_guides/berlitz1/HandRMadrid.txt:        800/325-3535 in the U.S., 800/325-3589 in Canada, or 91/360 80 00; fax
travel_guides/berlitz1/HistoryFWI.txt:        Canada to the British.
travel_guides/berlitz1/HistoryHawaii.txt:        Canada, and Australia from Waikiki, millions fell under the spell of a
travel_guides/berlitz1/HistoryHongKong.txt:        were prompted to apply for citizenship elsewhere, notably in Canada and
travel_guides/berlitz1/HistoryJapan.txt:        thought to be worth more than the entire real-estate value of Canada.
travel_guides/berlitz1/WhereToFrance.txt:        Memorials in the Square du Canada and the beautiful
travel_guides/berlitz2/Bermuda-history.txt:In the years that followed, Bermuda’s fortunes picked up as the first steamships began to arrive on a regular basis. In 1883 Princess Louise (daughter of Queen Victoria) arrived on a lengthy visit en route to her new home farther north, as the wife of the Governor General of Canada. She extolled Bermuda to those in her upper-class English circles, and wealthy tourists began to arrive soon thereafter. By the turn of the century, Bermuda was a well-known winter destination for visitors from the US and Canada as well as Britain. The Princess Hotel was opened in Hamilton in 1885 to commemorate the visit.
travel_guides/berlitz2/California-WhatToDo.txt:The golf capital of California, however, is without doubt the Monterey Peninsula, with 18 full-sized courses, half of them public. The other nine, which include world-famous tournament courses, can be played through arrangements with certain hotels in the area, though at high cost. The best of the public courses are Del Monte in Monterey, Pebble Beach, Spyglass Hill, and the Rancho Canada in Carmel. There are also good golf courses in Palm Springs.
travel_guides/berlitz2/Canada-History.txt:I s it history or blarney to suggest that St. Brendan, a sixth-century monk from Galway, was the first European to reach Canada? The good people of Newfoundland, where he is said to have landed, like to think he was. After all, on his return he told of being attacked by insects as big as chickens. “Of course,” say the Newfies, “they must have been our giant mosquitoes!”
travel_guides/berlitz2/Canada-History.txt:This takes some of the wind out of the sails of John Cabot, the Venetian navigator who claimed Canada’s eastern seaboard for England’s Henry VII in 1497. Locals fight over whether it was Nova Scotia or Newfoundland he actually discovered. Cabot himself mistook it for the northeast coast of Asia. In fact, Breton, Basque, and Portuguese fishermen had been here long before him but kept to themselves the secret of the coastal waters’ teeming cod fisheries. Initially, the English were attracted to Canada only by the fish, preferring to concentrate their colonizing activities farther down the American coast.
travel_guides/berlitz2/Canada-History.txt:The French came looking for gold and diamonds, spices, and a passage to Asia. In 1535 Jacques Cartier ventured up the St. Lawrence as far as Hochelaga Village, dominated by a hill he named Mont Réal (Mount Royal). Cartier was not exactly showered with honors when he returned with eleven barrels of worthless yellow iron pyrites and glittering quartz. For the next 70 years, Canada was all but ignored until the French turned to the more lucrative new fur trade.
travel_guides/berlitz2/Canada-History.txt:But Britain backed this vested interest with tough diplomacy and a powerful navy, while Louis XIV was too wrapped up in his European power plays to pay much attention to French Canada. Although the British made no military conquests here during the War of Spanish Succession (1700–1713), their negotiators forced the French in the ensuing Treaty of Utrecht to give up all of Acadia (Nova Scotia) except Cape Breton. There, the French fortress of Louisbourg, which defended the sea approaches to Québec, was seized by the British in 1744. It was returned four years later in diplomatic negotiations, only to fall once and for all in 1758 in an assault mounted from the new British naval base of Halifax. In the final struggle for Québec, the courageous French military commander, Marquis de Montcalm, led outnumbered troops to a victory at Ticonderoga. But, poorly coordinated with local Canadian militia, they lost the city of Québec in 1759 to Britain’s General James Wolfe on the Plains of Abraham. Both Montcalm and Wolfe were killed in the battle.
travel_guides/berlitz2/Canada-History.txt:At first, British immigrants did not exactly flock to Canada either. Governor James Murray sympathized with the Québécois, whose bravery he much admired. Although the established church was now Anglican, Catholic privileges and tithes were restored. These were enshrined in the Québec Act of 1774, which also maintained French civil law alongside British criminal law and gave French Catholics seats on an appointed governmental council. But when American revolutionaries invaded Québec in 1775 in the hope of winning the French-Canadians over to their cause, the latter did not rally to the British side until the American soldiers started taking the habitants’ livestock and supplies.
travel_guides/berlitz2/Canada-History.txt:When American Independence was declared, some 40,000 Loyalists — New Englanders and Germans from Pennsylvania, but also some Indians and black African slaves — moved north to Canada. The most resilient settled on Prince Edward Island and in Nova Scotia, around the Bay of Fundy, while a majority migrated to Niagara and the Eastern Townships in southern Québec.
travel_guides/berlitz2/Canada-History.txt:To cope with the rival claims of Loyalists and Québécois, the Constitutional Act of 1791 divided the colony into Upper Canada (Ontario) and Lower Canada (Québec), separated by the Ottawa River. Under lieutenant governors, each province had a parliamentary system modeled on the Houses of Commons and Lords, while Lower Canada’s French language and civil and religious institutions were safeguarded.
travel_guides/berlitz2/Canada-History.txt:With great pioneering skill, Upper Canada’s first lieutenant governor, John Simcoe, pushed new highways north from Lake Ontario and west to Hamilton. He established the provincial capital at a trading post, Toronto, in the heart of a malarial swamp, and renamed it York. A landed gentry made up of army officers, government officials, and commercial speculators ran the province, creating a hereditary aristocracy known as the Family Compact. More Americans were lured over the border with land grants; the population rose from 14,000 in 1792 to 90,000 by 1812. French-Canadians were also multiplying rapidly, from 60,000 when New France was abandoned in 1760 to 330,000 fifty years later.
travel_guides/berlitz2/Canada-History.txt:Canada bore the brunt of US hostility in the War of 1812. The Americans were convinced that the British were backing Indian raids on American settlements along the Canadian border. Congress called for nothing less than the conquest of Canada, but Major-General Isaac Brock’s tiny Canadian force, allied with Chief Tecumseh’s Shawnee Indians, routed a half-hearted American invasion along the Niagara frontier. The Americans burned and looted York, provoking a violent British reprisal raid on Washington.
travel_guides/berlitz2/Canada-History.txt:Though greatly outnumbered, Anglo- and French-Canadians fought victoriously side by side at Châteauguay. But after the war, the militia of Louis-Joseph Papineau’s patriotes became the backbone of growing anti-British agitation. With British immigration on the increase, Québécois autonomy was threatened by moves towards one government for Lower and Upper Canada. Landowners such as Papineau feared being swamped by projected improvements of the St. Lawrence trade route. In the general paranoia, the patriotes even accused the British of fostering Québec’s 1832 cholera epidemic. Papineau asked London for guarantees of autonomy for a Lower Canada assembly dominated by French-Canadians. British rejection in 1837 led to riots opposing patriotes and British militia. After a victory at St.-Denis, the French-Canadians were crushed by Governor John Colborne’s troops north of Montréal. Habitants’ farmhouses were burned down, earning Colborne the nickname of Old Firebrand (Vieux Brûlot), and defeat left an even more enduring bitterness than the original British conquest. Papineau fled to the United States.
travel_guides/berlitz2/Canada-History.txt:In the same year, hatred of the high-handed Tory oligarchy in Upper Canada provoked a rebellion among small farmers and tradesmen beset by economic depression. Their champion, newspaper editor and first mayor of Toronto, William Lyon Mackenzie, proposed a US-style republic. Heeding his call of “Up them, brave Canadians, get ready your rifles and make short work of it,” a few hundred irregulars gathered at Montgomery’s Tavern north of Toronto. But a Tory militia led by bagpipes put down the so-called Mackenzie Rebellion in a skirmish lasting just a few minutes. Short work indeed.
travel_guides/berlitz2/Canada-History.txt:Governor General “Radical Jack” Durham was sent to put the house in order; he proposed a unified assembly governing Canada’s domestic affairs. He scorned the Québécois for “retaining their peculiar language and manners. They are a people with no history and no literature.” But Lower Canada’s pragmatic Louis-Hippolyte Lafontaine accepted the British framework as a means of asserting the Québécois’ right to equal representation. In the new United Provinces of Canada set up in 1841, he formed a delicate alliance with Toronto reformer Robert Baldwin. Immigration increased to meet an ambitious public works program of canals to bypass the St. Lawrence rapids and cross the Niagara peninsula, as well as of new cities, mines, and roads.
travel_guides/berlitz2/Canada-History.txt:Choosing a permanent capital for these United Provinces wasn’t easy. In the perennial Anglo-French conflict, bilingual Montréal was too troublesome, while English-speaking Toronto or French-speaking Québec City would favor one community at the expense of the other. Royal Engineer officers sent watercolors of likely sites for Queen Victoria’s approval. The choice went to Bytown, a puny lumber depot renamed Ottawa after the river on which it stood, diplomatically situated between Upper and Lower Canada.
travel_guides/berlitz2/Canada-History.txt:To the east, and remote from the centers of power, the people of Newfoundland and the Maritime Provinces lived in small, isolated communities with no unifying geography comparable to the Great Lakes or St. Lawrence River. Newfoundland turned its back on the hostile interior to reap the harvests of the sea. Always psychologically closer to London than to Ottawa, Newfoundland did not become part of Canada until 1949. Yankee Loyalists struggled valiantly with a region they called Nova Scarcity. The British had scattered Nova Scotia’s French Acadians, some to the nearby islands of St. Pierre and Miquelon (still French today), others as far as Louisiana, while a small nucleus remained in New Brunswick. The potential of Prince Edward Island’s fertile soil was squandered by absentee land speculators who milked it only for the rent and left the settlers no motivation to develop it.
travel_guides/berlitz2/Canada-History.txt:The British North America Act of 1867 created the Dominion of Canada. John A. Macdonald, an Ontario Tory, was the first Prime Minister. To resist a turbulent United States torn by civil war, Anglo-Canadians wanted a strong central government delegating little more than municipal affairs to the provinces. French-Canadians insisted on a federal system with stronger provincial governments, to protect specific Québécois interests in property and civil rights. Henceforth, national unity always played second fiddle to ethnic, religious, and above all economic regional interests.
travel_guides/berlitz2/Canada-History.txt:But Laurier saw the limits of British support when the British and American negotiators of the Alaska boundary tamely accepted the US claims to a southern coastal “panhandle,” which denied Canada sea access to the Yukon goldfields. He asserted greater national autonomy by taking over British military installations and shipyards at Esquimalt on Vancouver Island and Halifax, Nova Scotia. When Alberta and Saskatchewan acceded to provincial status in 1905, and the country’s mining, lumber, paper, and pulp industries burgeoned, Laurier championed a new transcontinental railway that would take a more northerly route to serve them — the state-owned Canadian National Railway (C.N.R.).
travel_guides/berlitz2/Canada-History.txt:Under Tory government, the country supported Britain with 500,000 men in World War I, losing over 60,000 on the battlefield. Emotional European nationalism spread to Canada. Citizens of German and Austrian origin were dismissed from public service, the German language was banned in schools, and Berlin, in Ontario, was renamed Kitchener.
travel_guides/berlitz2/Canada-History.txt:William Lyon Mackenzie King, who became leader of the Liberal Party after Laurier’s death, made Canada progressively more independent of Britain. At the Imperial Conference of 1926 he won the acknowledgement that Canada was autonomous in external affairs and thus not subject to a common, British-dominated policy for the whole Empire. This led to the 1931 Statute of Westminster, which effected the equality of Britain and the Dominions, thus consecrating Canada’s full autonomy in home and foreign affairs. The governor general in Ottawa became the symbolic representative of the Crown rather than of the British government. But the provinces insisted that the Constitution remain with London rather than let Ottawa infringe on their prerogatives.
travel_guides/berlitz2/Canada-History.txt:At the same time, the country came more and more into the American economic and cultural orbit. The boom years of the 1920s saw the growth of a “branch-plant economy;” with American automobile, rubber, chemical, and clothing factories springing up around the Great Lakes at Hamilton, Oshawa, Windsor, and Montréal. The boom in American popular culture inundated Canada with radio, movies, and mass-market magazines. Québec, in particular, tried to resist the invasion, even going so far as to ban adolescents from cinemas. Apart from the Group of Seven, a spirited band of Ontario painters who were seeking a distinctive “national” style, most Canadian-born artists — actors, musicians, and writers — felt obliged to seek fame and fortune in New York, London, or Paris.
travel_guides/berlitz2/Canada-History.txt:Canada’s Great Depression was felt first by farmers in the Prairie Provinces, unable to get rid of their surplus from the wheat glut of 1928. Even the drought in 1929 did not ease matters, and ten more years of bad harvests meant they would not recoup their losses. Other sectors of the economy — timber, fisheries, mining, and construction — ground to a halt as production outstripped demand. Spirits were raised by the escapist fare of the new Canadian Radio Broadcasting Commission, today’s C.B.C. — Hollywood extravaganzas, and home-grown media stunts, not the least of which was the hullabaloo surrounding the Dionne quintuplets, born in Ontario in 1934.
travel_guides/berlitz2/Canada-History.txt:Trans-Canada Airlines, the forerunner of Air Canada, started up in 1937, and air travel became vital for covering the vast distances, fighting forest fires, and carrying provisions and wages to remote corners of the far north. Natural enough, then, that involvement in World War II began with a British Commonwealth Air Training Plan, using Canada’s safer skies to prepare pilots for combat. At the outbreak of war, Canada’s reputation for welcoming immigrants and refugees from all over the world was tarnished by the blocking of Communists and Jews from Hitler’s Germany. Asked how many he would allow in, Justice Minister Ernest Lapointe said: “None is too many.” After 1941, citizens of Japanese origin were interned and had their property confiscated.
travel_guides/berlitz2/Canada-History.txt:Economically, the country was closer than ever to the United States. The consumer boom accentuated dependency on America’s Canada-based branch-plant manufacturers of cars, radios, TVs, and refrigerators. The United States was also Canada’s main customer for raw materials and energy in what was a veritable explosion of industrial achievement. North Manitoba nickel and Labrador iron were replacing depleted resources south of the border; huge oil strikes were made near Edmonton, Alberta, in 1947; a uranium reactor started up in Ontario in 1952; and hydro-electric plants mushroomed all across the country. The St. Lawrence Seaway was opened in 1959. Six years later, drivers could cross the entire continent on the Trans-Canada Highway.
```

---













**Sources**
1. Link: https://www.geeksforgeeks.org/grep-command-in-unixlinux/
2. Link: https://www.digitalocean.com/community/tutorials/grep-command-in-linux-unix

I simply just seearched up about command line inputs for grep and found these two options. I looked into different options but felt that
these two webpages have the most meaningful/interesting options to choose from. They came from the same search results when I typed in 
command line options for grep `command line options for grep  `

