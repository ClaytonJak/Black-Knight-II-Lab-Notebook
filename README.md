## Black Knight II Lab Notebook
###Clayton Jaksha | AY16-1
### *Retrospective/General Observations*
This semester's Black Knight II capstone work was a lot of spinning tires in the mud and a lot of small gains. We also learned a great deal about being concise and picking proper language in briefings. That said, we have made progress. Hopefully this engineering unit will be complete by May.

#### 13OCT15
Morale is high, we came in with LTC Burrow and discussed the broad picture of what Black Knight II needs to accomplish---everything from launch to normalized operations.
We all know very little about what anything actually is, but we're ready to learn.
#### 15OCT15
Today we got more familiarized with the space lab in Thayer Hall and the equipment that was purchased last year. We also sought out a Linux machine to use with the flight computer after reading the NanoMind A712D datasheet. We do not have the Linux machine as of yet (with Eclipse installed).
#### 19OCT15
We received the linux machine! Today I spent almost the entire class just having Tom show me how to use Linux. It's completely different from what I'm used to. It does seem to make enough sense though and there are plenty of resources that I can reference elsewhere.
#### 21OCT15
Today Tom and I made a [gmail account](clayton.jaksha@gmail.com) for the purposes of interfacing with the Gomspace support help desk. We also explored the files that are included with the NanoMind A712D in two flash drives. It seems there is a code repository and a set of installation instructions. It appears everything that is needed to get the development environment up and running is included with the NanoMind, which is convenient.
#### 23OCT15
Sprint 1 Review. A lot of work was put in offline to make this happen. All work can be found on [trello board](https://trello.com/b/nvrMijWc/black-knight-ii). Biggest comments from Sprint 1 review were mostly on briefing style and incorporating more of the Scrum Agile process into our work. We definitely have work to do on how we do business. I don't think we were doing enough self-assessment and cross-talk at the beginning of each class.
#### 27OCT15
Today we reviewed our work from Sprint 1 and rehashed how to go about the agile scrum process. We needed this time to recenter our efforts and chart the course ahead for sprint 2. We also realized that the git for Gomspace NanoMind software was inoperable; the link was dead. So we sent out an email to Gomspace requesting the development software.
#### 29OCT15
Coming back into class, we had no word from Gomspace, so we sent a strongly worded email over there requesting assistence. We almost immediately received a response from Johan from Gomspace saying that he had fallen ill. He told us to ask Gomspace support for the nanomind-v1.4 tar ball. We did just that. They also opened a help-desk account for us at Gomspace... which will surely be necessary.
#### 02NOV15
We have now received the tar ball, but are struggling with a particular file in there ".waf". We're not sure exactly what it does, but when we try to configure and build .waf, the whole installation collapses. We've tried a number of different ways around it (sudo, uninstall/reinstall, etc) but nothing works. We sought help from Gomspace.
#### 04NOV15
Johan told us to study up on the GCC compiler, explaining that that was the key to understanding .waf and ensuring everything compiled correctly. We checked to see that GCC was installed in the correct directory, and it is, so we're still at a loss as to why .waf is not building. We sought more help from Gomspace.
#### 06NOV15
After sending an example of some C code we compiled with gcc, Johan told us to check again that GCC was installed into the correct path. We uninstalled and reinstalled, but that still didn't allow .waf to configure. Very frustrated at this point.
#### 10NOV15
Sprint 2 Review. Like the sprint 1 review, we didn't slack off to make this product.
#### 13NOV15
We sent a full error report to Gomspace of the errors we receive when we try to run "./waf configure" and "./waf build". Hopefully this time they will be able to be of some help.
#### 17NOV15
No reponse from Gomspace, trying all sorts of things, tires in the mud though. Tom and I have been trying everything to make this work. We've uninstalled and reinstalled countless times and everything matches the instructions from Gomspace and from Johan. Nothing seems to be working.
#### 19NOV15
It is now one week without any contact whatsoever from Gomspace. We reached out to them again in a much more strongly worded fashion, reminding them of the capital (money and time) we've invested into their product and how we should be committed as a team towards getting this product into space because it gives their product flight heritage, thus making it more valuable. They responded almost immediately. Johan gave us a new image of the previous tar ball and, finally, a breakthrough. .waf finally configured and built (which was unreal). However, we got hung up on something new: installing OpenOCD in the JTAG directory. It seemed that the install did not go successfully. We screencapped the error report and sent it to the GOMSPACE help desk.
#### 23NOV15
Gomspace got back to us on the OpenOCD, saying that it was a known issue, so we shouldn't have a problem with it down the road. If we do... well... it's a known issue.

Now we're looking to upload a "hello world" onto the computer. However, we have no idea how to do that. So, we reached out to Gomspace again.
#### 30NOV15
Today we attempted to brief our PDR and completely missed the mark. We met up to revise and recenter our brief and our information. We left with a few due-outs for each group.
#### 02DEC15
Failed PDR briefing today. We were not prepared. Flight computer needs to estimate packet sizing.
#### 04DEC15
Was not here for this class, but Tom told me that the practice brief again did not go well. Apparently we are still missing information on packet sizing and we need to reformat our briefing style entirely. We will meet and recenter again.
#### 08DEC15
Today we reviewed the LA Hacks team's sprint 2 review, which LTC Burrow said was a very good example of what a sprint review should look like.
We feel confident that the sprint review for sprint 3 will reflect the work done for this sprint, which was almost entirely PDR work.
I wish I could have been able to do more work to get the flight computer operational.
