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

THIRD: `grep  -r`

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
---

SECOND: `grep  -o`

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





















**Sources**
1. Link: https://www.geeksforgeeks.org/grep-command-in-unixlinux/
2. Link: https://www.digitalocean.com/community/tutorials/grep-command-in-linux-unix

I simply just seearched up about command line inputs for grep and found these two options. I looked into different options but felt that
these two webpages have the most meaningful/interesting options to choose from. They came from the same search results when I typed in 
command line options for grep `command line options for grep  `

