# mark-whiskeyman.github.io
Quick Links 
- [Professional Self Assessment - as a word document](https://docs.google.com/document/d/1w8PyG8870DTxBw3W6Kq7zjHofBkN26KZAtnFsqaOc3s/edit?usp=sharing).
- [Screen capture CodeReview](https://drive.google.com/file/d/1OrZgqBEq__totvvLUANpjs12Zg_7lT2x/view?usp=sharing)
- [Enhancement 3 Databases Narrative  - as a word document](https://docs.google.com/document/d/1u8MXPjENobWeloMATqxaTnQFK8JpWAlID3pZ5amxoRY/edit?usp=sharing)
- [Enhancement 2 Algorithms Narrative - as a word document](https://docs.google.com/document/d/1PvHcMLF3eQ-nVpq8_DUb85CJygjr-xWyvHTqJKQ2sJ8/edit?usp=sharing)
- [Enhancement 1 Design Narrative - as a word document](https://docs.google.com/document/d/1VaamAJ3VHv0WdWRr3UyGx3mwj7UpTQcCq4LvY8ua2Yg/edit?usp=sharing)
-UPDATED 02-13-2021 [FyreBrund as a runnable Jar](https://drive.google.com/file/d/1ukaMPno6ff30J7OnlhY6qhG_-IUBhrzx/view?usp=sharing)
- [Project FyreBrund git clone](https://recursivefunction@bitbucket.org/recursivefunction/fyrebrund.git) 
[https://recursivefunction@bitbucket.org/recursivefunction/fyrebrund.git](https://recursivefunction@bitbucket.org/recursivefunction/fyrebrund.git)
**Known Issues: Google Chrome has trouble viewing this sometimes. Microsoft Edge Can't click the link**

If you experience these issue:
1. Try closing all Chrome windows and reopening. 
2. or Copy and paste the link into Microsoft Edge
3. or Try using another browser


## Hello! My name is Mark Whiskeyman!
Whatever I put my mind to I achieve. 
There is no obstacle I will not overcome.
What do you want me to achieve for your company? 

## About me:

In 2015 I decided to change my career by going back to school!
Right now, I am an Assistant Manager. 
Soon I will develop software. 
Later I will lead a software development team. 

# e-Portfolio 

## Professional Self-Assessment
See the [FULL TEXT HERE](https://github.com/mark-whiskeyman/mark-whiskeyman.github.io/blob/master/Professional_Self_Assessment.md).

The artifact selected for this e-portfolio showcases my skills in the Areas of Software Design and Engineering, Data Structures and Algorithms, and Databases. The e-portfolio focuses on 5 outcomes. The outcomes are discussed in detail in the assessment itself, here they are in brief:

- Building Collaborative Environments.

- Deliver Professional Quality Communications.

- Solving Problems with Algorithms and Data Structures. 

- Using Well founded software development techniques.

- Building with a security mindset.

### Code Review July 2020: 
### Last Days of the Fyebrund
[Screen capture CodeReview](https://drive.google.com/file/d/1OrZgqBEq__totvvLUANpjs12Zg_7lT2x/view?usp=sharing)

This is an example of a code review I have done for a game I am working on. This code review shows where the code was at the beginning of the project and the planned enhancements. 

## Project: Last Days of the FyreBrund - Latest updates at the top
This is a project I have been working on in my spare time. 
This is a text-based menu space trading game. 
The current iteration is built using Java and can be found here:
[git clone](https://recursivefunction@bitbucket.org/recursivefunction/fyrebrund.git)

### ENHANCEMENT_3 Databases
See the [FULL TEXT HERE](https://github.com/mark-whiskeyman/mark-whiskeyman.github.io/blob/master/Enhancement_3.md).

The final Enhancement of the artifact deals with Databases. 

Here we used MongoDB to import a CSV file into "documents". Then we allowed the user to search the documents (ships) by name of ship, type of ship, or size of ship. Although the user’s interface is simplified, searching the data is done in several ways. The data is either aggregated in the pipeline, or searched using a find function, or searched using a regex function that allows for partial matches for typed queries. 

Using databases was easier in the sense that the database uses a driver and function calls to deliver the resources. I did not have to write my own logic, then test it, and then debug it. Thus, the database aspect was slightly less complicated than anticipated. 

After Enhancement 3 we are now here: 

|   **BANK**  |**SHIPYARD**|**WPNDepot**|**Navigate**|**Cargo** |**Encounters**     | **Databases**       |
|-------------|------------|------------|------------|----------|-------------------|---------------------|
| Make Loans  | Buy Ships  | Buy Wpns   | *Select*   |Buy Cargo | Encounter enemies | -import csv         |
| Repay Loans | Sell Ships | Sell Wpns  |  Location  |Sell Cargo|  -Fire on enemy   |  into document       |
| Spend Money |            |            | *Change*   |          |  -Launch Missiles | - Aggregate          |
| Earn Money  |            |            |  Location  |          |  -Bribe enemy     | - Find               |
|             |            |            |            |          |  -Attempt Retreat | - Search by          |
|             |            |            |            |          | Enemies can       |   close matches      |
|             |            |            |            |          |  -Fire weapons    | - Search by ship type | 
|             |            |            |            |          |  -Attempt Retreat | - Search by ship size|
|             |            |            |            |          |Encounter friends  |                       |

### ENHANCEMENT_2 Algorithms and Data Structures.:
### Last Days of the Fyebrund
See the [FULL TEXT HERE](https://github.com/mark-whiskeyman/mark-whiskeyman.github.io/blob/master/Enhancement_2.md).

The Second Enhancement deals with Algorithms and Data Structures.

In this addition to the artifact I have added enemy and friendly encounters.

This addition required major use of algorithms including the use of IF...ELSE, SWITCH,
Random number generation, selection from arrays and lists, aggregating data,
guard conditions, TRY...CATCH, etc. 

Here is a simplified version:

1. Determine current player level 
2. Select a ship from the ship file within one level of player
3. Determine if ship is enemy or friendly 
4. If enemy 
4.  -A Add weapons to the enemy based on level of enemy ship
4.  -B Decide turn order 
4.  -C Allow player to choose action on their turn
4.    --C.1 Fire Weapons
4.    --C.2 Launch Missiles 
4.    --C.3 Attempt bribe
4.    --C.4 Attempt retreat
4.  -D Enemy chooses action based on outcome probability of battle on their turn
4.    --D.1 If outcome favorable fire weapons 
4.    --D.2 if outcome less favorable fire missile
4.    --D.3 if outcome bad attempt retreat
4.  -E Exit battle if player or enemy is dead, retreating, bribed otherwise repeat at 4.B
5. If Friendly 
5. -A Display message of peace 
6. Exit Encounter 
  

After Enhancement 2 we are now here: 

|   **BANK**  |**SHIPYARD**|**WPNDepot**|**Navigate**|**Cargo** |**Encounters**
|-------------|------------|------------|------------|----------|-------------------|
| Make Loans  | Buy Ships  | Buy Wpns   | *Select*   |Buy Cargo | Encounter enemies |
| Repay Loans | Sell Ships | Sell Wpns  |  Location  |Sell Cargo|  -Fire on enemy   |
| Spend Money |            |            | *Change*   |          |  -Launch Missiles |
| Earn Money  |            |            |  Location  |          |  -Bribe enemy     |
|             |            |            |            |          |  -Attempt Retreat |
|             |            |            |            |          | Enemies can       |
|             |            |            |            |          |  -Fire weapons    |
|             |            |            |            |          |  -Attempt Retreat |
|             |            |            |            |          |Encounter friends  |


We still need to add The Ability to

[] Interact with A database


### ENHANCEMENT_1 Software design/Engineering.:
### Last Days of the Fyebrund
See the [FULL TEXT HERE](https://github.com/mark-whiskeyman/mark-whiskeyman.github.io/blob/master/Enhancement_1.md).

The first enhancement added was for the user to be able to buy and sell cargo. Although this seems simple there are many Software Engineering principles at use here. 
  
  Specifically, ideas such as 
  
  -Functional decomposition
  
  -Incrementally building
  
  -Building on known good code and 
  
  -Object-Oriented Design 
  
  With Object oriented design I am using an “is-a”, “has-a” relationship to ensure clean coding technique. 
The thought process here for Object Oriented Design is such:

I started with a player

A player has a bank account

A player has a ship 

A ship has weapons... and so on.

After Enhancement 1 we are now here: 

|   **BANK**  |**SHIPYARD**|**WPNDepot**|**Navigate**|**Cargo** |
|-------------|------------|------------|------------|----------|
| Make Loans  | Buy Ships  | Buy Wpns   | *Select*   |Buy Cargo |
| Repay Loans | Sell Ships | Sell Wpns  |  Location  |Sell Cargo|
| Spend Money |            |            | *Change*   |          |
| Earn Money  |            |            |  Location  |          |

We still need to add The Ability to

[] Have Enemy Encounters

[] Interact with A database

### ENHANCEMENT_0 Original State.: 
### Last Days of the Fyebrund
This is the initial state of the build. This area lays a lot of the foundation for what we will be expanding on. Things like buying and selling ships may not seem difficult, but designing the ships to be balanced and playable was the tricky part. 

So far The player can Do the Following: 

|   **BANK**  |**SHIPYARD**|**WPNDepot**|**Navigate**|
|-------------|------------|------------|------------|
| Make Loans  | Buy Ships  | Buy Wpns   | *Select*   |
| Repay Loans | Sell Ships | Sell Wpns  |  Location  |
| Spend Money |            |            | *Change*   |
| Earn Money  |            |            |  Location  |

We still need to add The Ability to

[] Buy and Sell Cargo 

[] Have Enemy Encounters

[] Interact with A database






