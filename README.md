# <img src="http://www.rice.edu/_images/rice-logo.jpg" width=180> Comp427, Spring 2018, Homework 1
## Rational Paranoia
The homework specifications, as well as the corresponding course slide decks,
can be found on the [Comp427 Piazza](https://piazza.com/class/jqifhp864b37ju).
This assignment is due **Thursday, January 17 at 6 p.m.**

You will do this homework by editing the _README.md_ file. It's in
[MarkDown format](https://guides.github.com/features/mastering-markdown/)
and will be rendered to beautiful HTML when you visit your GitHub repo.

## Student Information
Please also edit _README.md_ and replace your instructor's name and NetID with your own:

_Student name_: Stoyan KOMITOV 

_Student NetID_: sak7 

Your NetID is typically your initials and a numeric digit. That's
what we need here.

_If you contacted us in advance and we approved a late submission,
please cut-and-paste the text from that email here._

## Problem 1
- Scenario: {Stadium}
- Assumptions:
  - I will select Clemson University's Memorial Stadium. It has capacity of 81,500 seats. Furthermore, it houses all of the football team offices and meeting rooms.
  - Memorial stadium has averaged a 100% attendance rate over the past five years, so I will assume such attendance when considering assets, threats, and countermeasures.
  - The team has nonphysical assets (e.g. play schemes) that are of particular value to the team.
- Assets:
  - Howard's rock, the team's good luck charm is stored on the field. This asset cannot be assigned a monetary value, but it's priceless in terms of the team's traditions.
  - Championship awards: Clemson holds multiple national, conference, and division titles, the trophies for which are on display on stadium grounds.
  - Football team equipment: uniforms, exercise machines, etc.
  - Since all the coaches have offices and prepare for games in the stadium, it is not out of the realm of possibilities that the team's set of plays is stored in the stadium. The strategic plays have led the team to success, so protecting their precise inner workings is of utmost importance.
  - Communication systems. I will restrict this to the tools utilized on gameday to communicate between players and coaches.
  - Fan base: the fans provide support to the team.
- Threats:
  - If someone were to steal or vandalize Howard's rock, that would be a huge moral blow to the team.
  - Similarly, awards being stolen would be bad.
  - Tampering with player equipment can lead to injury.
  - If information regarding the team's strategies is leaked, that could result in opponents having an unfair advantage, and therefore hurt the Clemson Tigers' performance.
  - If the communication systems are compromised, opposing team could utilize this information to defend against the Tigers' attempts to score/defend in game.
  - Having 80,000+ people in a highly concentrated area could become a target of a malicious attack that can result in injuries and death.
- Countermeasures:
  - Place Howard's rock in a protective glass case with an armed alarm to notify if tampering occurs.
  - Designate a dedicated room to house awards in. Ensure awards are secured behind bulletproof glass, and have guards on rotation. Perform metal scans on visitors to room, and require identification to enter.
  - Designate a locker for every player's equipment. Provide each player with a difficult-to-pick padlock. Lock locker room via a key players don't have access to .
  - If there are digital records of the team's plays, fully encrypt stadium computers. Place strategic materials in an underground safe and establish a protocol for accessing them.
  - In order to prevent eavesdropping on communication systems, take them off conventional radio waves, and instead set up a private encrypted wireless network restricted to the field.
  - To prevent malicious attacks from visitors, install security checkpoints at every entrance at which visitors are screened for dangerous objects and substances.
## Problem 2
- Scenario: {Grading}
- Assumptions:
  - There are laws in place that protect student record privacy. For example, FERPA. Thus, I am assuming that all individual grades must be kept confidential and that there are legal consequences if that isn't the case. 
  - Grading is performed by hand, by a team of TAs (like in math classes at Rice). Each TA is responsible for a small portion of the overall class body.
  - Assignments are pledged, so that every student is responsible for the work they submit, but they do have access to outside resources like the Internet.
- Assets:
  - A full record of individual grades in a central bookkeeoping system, as well as scores written on submissions. 
  - Problems and solutions that are meant to be kept in-house. It is in my interest to maintain a set of problems that can be reused in future course iterations, and since outside resources are permitted, I do not want these floating around. 
- Threats:
  - Losing someone's assignment. This is feasible given large number of submissions. It is problematic because it would potentially violate FERPA and there would be no way to distinguish a lost submission from one that was not submitted at all.
  - An unauthorized individual viewing scores. This would be a violation of FERPA.
  - An individual leaks problems and solutions into public access.
  - A rogue TA intentionally mis-grades the assignments of his favorite students.
- Countermeasures:
  - Assignments are to be submitted where they will be graded. In this way, the movement of assignments and subsequent risk of loss is minimized. Futhermore, grades are immediately added to central record, AND onto submission to create redundancy if loss occurs.
  - Submissions happen into a US mail-style box (where you can submit but can't easily retrieve submissions). Only I have access to this mailbox, and I am in charge of distributing submissions to TAs for grading. In this way, probability of unauthorized viewers is minimized.
  - As an addititon to the above point, assignments are to be returned by graders directly to their submitters.
  - Grading is done in grading parties to minimize movement of assignment papers, and to expedite the process (ala COMP midterm style). 
  - Provide individuals with sligtly different versions of the same problems, whose characteristics serve as identifying clues. This measure accomplishes two things: even if collaboration were to occur, direct copying of solutions would not work; if someone leaks problems into public, then they can be identified based on problem clues.
  - Ensure conflicts of interest are avoided by preventing TAs grading the work of students they have known ties to. 

## Problem 3
- Scenario: I am designing the next big smart home assistant, Stoyana
- Assumptions:
  - Stoyana is an instant hit and has been adopted by 50M people.
  - Stoyana, much like Alexa or Cortana, has interactive capabilities, like answering verbal quesitons.
  - Users configure Stoyana to control other smart devices around the user's home, like lights or locks. Furthermore, they enable the "always listening for 'Hey Stoyana' que mode" to summon the device with more ease.
  - Stoyana is very smart and learns from the user's habits.
- Assets:
  - Access to stream of user voice input.
  - Access to user home devices with privileges to make changes to their function.
  - Access to user preferences and patterns related to their habits.
- Threats:
  - Malicious entities may want to tap into Stoyana's microphone stream in order to listen in on conversations of Stoyana's trusting users.
  - There may be an attack whose intent is to change the aspects of the smart home. For example, if all smart appliances are turned on in their most power-demanding modes at once, that can maybe blow a fuse or even worse- cause a fire. Alternatively, it could compromise the restricted access to the house if smart locks are utilized.
  - Download user data to profile them in malicious way
- Countermeasures:
  - It may not be a very elegant solution but I believe it's highly effective: introduce a button that physically closes the microphone circuitry to enable user voice input. This would make the product less appealing to those simply looking to yell orders questions across the room, but it provides a sure way to defend against unwanted listeners- if the microphonen is not connected, then it can't be tapped into. 
  - Establish an encrypted data stream between Stoyana and any new smart device incorporated with the home assistant. My idea for this is to use a technology like NFC that requires close contact of the devices to exchange an encryption key, if the original user initiates the pairing between the devices. They would then communicate using this key to ensure the integrity of the messages against malicious middlemen.
  - All communications between Stoyana and outside APIs must occur over secured pathways. Furthermore, Stoyana is to only store user profiles locally in order to prevent third parties from using data in the case of a data leak from a central repo.
