# Town Of Host: The Other Roles

## Regarding this mod

This mod is not affiliated with Among Us or Innersloth LLC, Town Of Host, and the content contained therein is not endorsed or otherwise sponsored by Innersloth LLC. Portions of the materials contained herein are property of Innersloth LLC. © Innersloth LLC.

## Releases

AmongUs Version: **2022.7.12**
**Latest Version: [Here](https://github.com/music-discussion/TownOfHost-TheOtherRoles/releases/latest)**

Old Versions: [Here](https://github.com/music-discussion/TownOfHost-TheOtherRoles/releases)

## Features

This mod only needs to be installed on the host's client to work, and works regardless of whether or not other client mods have been installed, and regardless of the type of terminal.<br>
Unlike mods that use custom servers, there is no need to add servers by editing URLs or files.<br>

However, please note that the following restrictions apply.<br>

- If the host changes and does not have this installed, the server isn't modded and is now just a regular Among Us game.<br>
- If someone will original TOH, joins a ToHU lobby, they may experience graphical issues.<br>

Note that if a player other than the host plays with this mod installed, the following changes will be made.<br>

- Display of the special role's own start screen.
- Display of the normal victory screen for the special role.
- Add additional settings.
- etc.

## Features
### Hotkeys

#### Host Only
| HotKey              | Function                       | Usable Scene    |
| ------------------- | ------------------------------ | --------------- |
| `Shift`+`L`+`Enter` | Force End Game                 | In Game         |
| `Shift`+`M`+`Enter` | Skip meeting to end            | In Game         |
| `Ctrl`+`N`          | Show active role descriptions  | Lobby&In Game   |
| `C`                 | Cancel game start              | In Countdown    |
| `Shift`             | Start the game immediately     | In Countdown    |
| `Ctrl`+`Delete`     | Set default all options        | In TOH Settings |
| `Ctrl`+`RMB`        | Execute clicked player         | In Meeting      |
| `RightCtrl`+`RMB`   | Kill clicked player            | In Meeting      |

#### MOD Client Only
| HotKey      | Function                                                               | Usable Scene |
| ----------- | ---------------------------------------------------------------------- | ------------ |
| `Tab`       | Option list page feed                                                  | Lobby        |
| `Ctrl`+`F1` | Output log to desktop                                                  | Anywhere     |
| `F11`       | Change resolution<br>480x270 → 640x360 → 800x450 → 1280x720 → 1600x900 | Anywhere     |
| `Ctrl`+`C`  | Copy the text                                                          | Chat         |
| `Ctrl`+`V`  | Paste the text                                                         | Chat         |
| `Ctrl`+`X`  | Cut the text                                                           | Chat         |
| `↑`         | Go back in time of chat send history                                   | Chat         |
| `↓`         | Go future in time of chat send history                                 | Chat         |

### Chat Commands
You can execute chat commands by typing in chat.

#### Host Only
| Command                                               | Function                                          |
| ----------------------------------------------------- | ------------------------------------------------- |
| /winner<br>/win                                       | Show winner                                       |
| /rename <string><br>/r <string>                       | Change my name                                    |
| /dis <crewmate/impostor>                              | Ending the match as a Crewmate/Impostor severance |
| /messagewait <sec><br>/mw <sec>                       | Set message send interval                         |
| /help<br>/h                                           | Show command description                          |
| /help roles <role><br>/help r <role>                  | Show role description                             |
| /help attributes <attribute><br>/help att <attribute> | Show attribute description                        |
| /help modes <mode><br>/help m <mode>                  | Show mode description                             |
| /help now<br>/help n                                  | Show active setting descriptions                  |
| /changerole role(crewmate, impostor, engineer...).    | Change your In-Game Role (dont get buttons)       |

#### MOD Client Only
| Command        | Function                    |
| -------------- | --------------------------- |
| /dump          | Dump log                    |
| /version<br>/v | Show version of MOD clients |

#### All Clients
| Command                     | Function                                |
| --------------------------- | --------------------------------------- |
| /lastresult<br>/l           | Show game result                        |
| /now<br>/n                  | Show active settings                    |
| /now roles<br>/n r          | Show active roles settings              |
| /template <tag><br>/t <tag> | Show template text corresponding to tag |

### Template
This function allows you to send prepared messages.<br>
Execute by typing `/template <tag>` or `/t <tag>`.<br>
To set the text, edit `template.txt` in the same folder as AmongUs.exe.<br>
Separate each entry with a colon, such as `tag:content`.<br>
Also, you can break lines by writing `\n` in the sentence like `tag:line breaks can be\nmade like this`.<br>

#### Welcome Message
If the tag is set to "welcome" in the template function, it will be sent automatically when a player joins.<br>
For example: `welcome:This room is using the unofficial version of TownOfHost.`

## Roles

| Impostors                           | Crewmates                         | Neutrals                          |
| ----------------------------------- | --------------------------------- | --------------------------------- |
| [BountyHunter](#BountyHunter)       | [Bait](#Bait)                     | [Arsonist](#Arsonist)             |
| [Evil Watcher](#Watcher)            | [Dictator](#Dictator)             | [Egoist](#Egoist)                 |
| [FireWorks](#FireWorks)             | [Doctor](#Doctor)                 | [Executioner](#Executioner)       |
| [Mare](#Mare)                       | [Lighter](#Lighter)               | [Jester](#Jester)                 |
| [Puppeteer](#Puppeteer)             | [Mayor](#Mayor)                   | [Lovers](#Lovers)                 |
| [SerialKiller](#SerialKiller)       | [Nice Watcher](#Watcher)          | [Opportunist](#Opportunist)       |
| [Sniper](#Sniper)                   | [SabotageMaster](#SabotageMaster) | [Terrorist](#Terrorist)           |
| [TimeThief](#TimeThief)             | [Sheriff](#Sheriff)               | [SchrodingerCat](#SchrodingerCat) |
| [Vampire](#Vampire)                 | [Snitch](#Snitch)                 | [Juggernaut](#juggernaut)         |
| [Warlock](#Warlock)                 | [SpeedBooster](#SpeedBooster)     | [Vulture](#vulture)               |
| [Witch](#Witch)                     | [Trapper](#Trapper)               | [Hacker](#hacker)                 |
| [Mafia](#Mafia)                     | [Demolitionist](#demolitionist)   | [PlagueBearer](#plaguebearer)     |
| [Madmate](#Madmate)                 | [Bastion](#bastion)               | [The-Glitch](#the-glitch)         |
| [MadGuardian](#MadGuardian)         | [Bewilder](#bewilder)             | [Werewolf](#werewolf)             |
| [MadSnitch](#MadSnitch)             | [Veteran](#veteran)               | [Guardian-Angel](#guardian-angel) |
| [SidekickMadmate](#SidekickMadmate) | [Child](#child)                   | [Amnesiac](#amnesiac)             |
| [Silencer](#silencer)               | [Sleuth](#sleuth)                 | [Pestilence](#pestilence)         |

### GM

The GM (Game Master) is an observer role.<br>
Their presence has no effect on the game itself, and all players know who the GM is at all times.<br>
Always assigned to a host and is ghosted from the start.<br>

## Impostor

### BountyHunter

Team : Impostors<br>
Basis : Impostor<br>

If the BountyHunters kill their designated target, their next kill cooldown will be much less than usual.<br>
Killing a player except their current target results in an increased kill cooldown.<br>
The target swaps after a configurable amount of time.<br>

#### Game Options

| Name                                     |
| ---------------------------------------- |
| Time To Swap Bounty(s)                   |
| Kill Cooldown After Killing Bounty(s)    |
| Kill Cooldown After Killing Others(s)    |

### FireWorks

Create and idea by こう。<br>

Team : Impostors<br>
Basis : Shapeshifter<br>

The FireWorks can set off fireworks and kill all at once. <br>
They can put a few fireworks by Shapeshift. <br>
After they put all the fireworks and after the other impostors are all gone, they can ignite all fireworks at once by Shapeshift. <br>
They can perform kills after setting off fireworks. <br>
Even if they mistakenly bomb themselves, killing everyone results in Impostor win. <br>

#### Game Options

| Name                |
| ------------------- |
| FireWorks Max Count |
| FireWorks Radius    |

### Mare

Create by Kihi, しゅー, そうくん, ゆりの<br>
Idea by Kihi

Team : Impostors<br>
Basis : Impostor<br>

They can kill only in lights out, but next kill cooldown will be half.<br>
While lights out they can move faster, and yet their name looks red by everyone.<br>

#### Game Options

| Name                            |
| ------------------------------- |
| Mare Player Speed In Lights Out |

### Puppeteer

Team : Impostors<br>
Basis : Impostor<br>

The puppeteer can curse a crewmate and force them to kill the next non-impostor they come near.<br>
The cursed crewmate can kill a mad role also.<br>
It is not possible for puppeteer to perform a normal kill.<br>

### SerialKiller

**Warning**
Broken with latest Among Us Update.

Team : Impostors<br>
Basis : Shapeshifter<br>

The SerialKillers have even shorter kill cooldown.<br>
Unless taking a kill by deadline, they murder themselves instantly.<br>

#### Game Options

| Name                          |
| ----------------------------- |
| SerialKiller Kill Cooldown(s) |
| Time Limit To Suiside(s)      |

### ShapeMaster

**Warning**
Unavailable.

Create and idea by しゅー<br>

Team : Impostors<br>
Basis : ShapeShifter<br>

The ShapeMasters have no Shapeshift cooldown.<br>
On the other hand, their default Shapeshift duration is shorter (default: 10s).<br>

#### Game Options

| Name                   |
| ---------------------- |
| Shapeshift Duration(s) |

### Sniper

Create and idea by こう。<br>

Team : Impostors<br>
Basis : Shapeshifter<br>

Sniper can shoot players so far away. <br>
they kill a player on the extension line from Shapeshift point to release point.<br>
Players on the line of bullet hear sound of a gunshot.<br>
You can perform normal kills after all bullets run out.<br>

Precise Shooting:OFF<BR>
![off](https://user-images.githubusercontent.com/96226646/167415213-b2291123-b2f8-4821-84a9-79d72dc62d22.png)<BR>
Precise Shooting:ON<BR>
![on](https://user-images.githubusercontent.com/96226646/167415233-97882c76-fcde-4bac-8fdd-1641e43e6efe.png)<BR>

#### Game Options

| Name                    |
| ----------------------- |
| Sniper Bullet Count     |
| Sniper Precise Shooting |

### TimeThief

Created by integral, しゅー, そうくん, ゆりの<br>
Idea by みぃー<br>

Team : Impostors<br>
Basis : Impostor<br>

Every kill cuts down discussion and voting time in meeting.<br>
Depending on option, the lost time is returned after they die.<br>

#### Game Options

| Name                              |
| --------------------------------- |
| TimeThief Decrease Time Length(s) |
| Lower Limit For Voting Time(s)    |
| Return Stolen Time After Death    |

### Vampire

Team : Impostors<br>
Basis : Impostor<br>

When the vampire kills, the kill is delayed (the bitten player will die in a set time based on settings or when the next meeting is called).<br>
If the vampire butes [Bait](#Bait), the player will die immediately and a self-report will be forced.<br>

#### Game Options

| Name                  |
| --------------------- |
| Vampire Kill Delay(s) |

### Warlock

Team : Impostors<br>
Basis : Shapeshifter<br>

When a warlock presses kill, the target is cursed. <br>
The next time the warlock shifts, the cursed player will kill the nearest person.<br>
If you shapeshift as Warlock, you can make a regular kill. <br>
Beware, if you or another impostor are the nearest to the player you have cursed when you shift you will be killed.<br>

### Witch

Team : Impostors<br>
Basis : Impostor<br>

The Witches can perform kills or spells by turns.<br>
The players spelled by Witches before a meeting are marked "cross" in the meeting, and unless exiling Witches, They all die just after the meeting.<br>

### Mafia

Team : Impostors<br>
Basis : Impostor<br>

The Mafias can initially use vents and sabotage, but cannot kill (still have a button).<br>
They will be able to kill after Impostors except them are all gone.<br>

### Silencer 

Team : Impostors<br>
Basis : Impostor<br>

The Silencer's first kill attempt will silence the crewmate inside the next meeting.<br>
After the Silence, the Silencer is a regular Impostor.<br>

## Madmate

There are common options for Madmates.
#### Game Options

| Name                          |
| ----------------------------- |
| Madmates Can Fix Lights Out   |
| Madmates Can Fix Comms        |
| Madmates Have Impostor Vision |
| Madmates Vent Cooldown        |
| Madmates Max Time In Vents    |

### Madmate

Team : Impostors<br>
Basis : Engineer<br>

The Madmates belong to team Impostors, but they don't know who are Impostors.<br>
Impostors don't know Madmates either.<br>
They cannot kill or sabotage, but they can use vents.<br>

### MadGuardian

Create and idea by 空き瓶/EmptyBottle<br>

Team : Impostors<br>
Basis : Crewmate<br>

The MadGuardians belong to team Impostors, one type of Madmates.<br>
Compared with Madmates, MadGuardian cannot use vents, while they can guard kills by Impostors after finishing all tasks.<br>

#### Game Options

| Name                                  |
| ------------------------------------- |
| MadGuardian Can See Who Tried To Kill |

### MadSnitch

Create and idea by そうくん<br>

Team : Impostors<br>
Basis : Crewmate or Engineer<br>

The MadSnitches belong to team Impostors, one type of Madmates.<br>
They can see who is the Impostor after finishing all their tasks.<br>
Depending on option, they can use vents.<br>

#### Game Options

| Name                   |
| ---------------------- |
| MadSnitch Can Use Vent |
| MadSnitch Tasks        |

### SidekickMadmate

Create and idea by たんぽぽ<br>

Team : Impostors<br>
Basis : Undecided<br>

The SidekickMadmate is an acquired Madmate Role assigned by Impostors in task phases.<br>
Some kind of Shapeshifter-based Impostors can give SidekickMadmate by Shapeshifting next to a target.<br>

**NOTE:**
- The **"nearest"** Crewmate becomes SidekickMadmate no matter to whom the Impostors Shapeshift.


## Impostor/Crewmate

### Watcher

Team : Impostors or Crewmates<br>
Basis : Impostor or Crewmates<br>

The watcher can see who each player has voted during every meeting. <br>

#### Game Options

| Name               |
| ------------------ |
| EvilWatcher Chance |


## Crewmate

### Bait

Team : Crewmates<br>
Basis : Crewmate<br>

When Bait is killed, the imposter will automatically self report.<br>
This also applies to delayed kills- Once the kill button is pressed, the report will be immediate.<br>

### Dictator

Create and idea by そうくん<br>

Team : Crewmates<br>
Basis : Crewmate<br>

When voting for someone in a meeting, the Dictators forcibly break that meeting and exile the player they vote for.<br>
After exercising the force, the Dictators die just after meeting.<br>

### Doctor

Team : Crewmates<br>
Basis : Scientist<br>

The doctor can see when Crewmates die using vitals anywhere in the map.<br>
By closing the chat, the doctor can see the dead players cause of death next to their name in all meetings.<br>

#### Game Options
| Name                    |
| ----------------------- |
| Doctor Battery Duration |

### Lighter

Team : Crewmates<br>
Basis : Crewmate<br>

After finishing all the task, The lighters have their vision expanded and ignore lights out.<br>

#### Game Options

| Name                          |
| ----------------------------- |
| Lighter Expanded Vision       |
| Lighter Gains Impostor Vision |

### Mayor

Team : Crewmates<br>
Basis : Crewmate or Engineer<br>

The Mayors' votes count twice or more.<br>
Depending on the options, they can call emergency meeting by entering vents.<br>

#### Game Options

| Name                              |
| --------------------------------- |
| Mayor Additional Votes Count      |
| Mayor Has Mobile Emergency Button |
| Number Of Mobile Emergency Button |

### SabotageMaster

Create and idea by 空き瓶/EmptyBottle<br>

Team : Crewmates<br>
Basis : Crewmate<br>

The SabotageMasters can fix sabotage faster.<br>
they can fix both of Comms in MIRA HQ, Reactor and O2 by fixing either.<br>
Lights can be fixed by touching a single lever.<br>
Opening a door in Polus or The Airship will open all the linked doors.<br>

#### Game Options

| Name                                                   |
| ------------------------------------------------------ |
| SabotageMaster Fix Ability Limit(Except Opening Doors) |
| SabotageMaster Can Open Multiple Doors                 |
| SabotageMaster Can Fix Both Reactors                   |
| SabotageMaster Can Fix Both O2                         |
| SabotageMaster Can Fix Both Comms In MIRA HQ           |
| SabotageMaster Can Fix Lights Out All At Once          |

### Sheriff

Team : Crewmates<br>
Basis : Impostor(Only host is the Crewmate)<br>

Sheriff can kill imposters always.<br>
Depending on settings, Sheriff may also kill neutrals.<br>
The sheriff has no tasks.<br>
Killing Crewmates will result in suicide. <br>

* As a measure against blackout, after death, the Sheriff can only see the motion of committing suicide at each meeting. There is no corpse. <br>

#### Game Options

| Name                                                              |
| ----------------------------------------------------------------- |
| Sheriff Can Kill [Arsonist](#Arsonist)                            |
| Sheriff Can Kill [Jester](#Jester)                                |
| Sheriff Can Kill [Terrorist](#Terrorist)                          |
| Sheriff Can Kill [Opportunist](#Opportunist)                      |
| Sheriff Can Kill Madmates                                         |
| Sheriff Can Kill [Egoist](#Egoist)                                |
| Sheriff Can Kill [SchrodingerCat](#SchrodingerCat) In Team Egoist |
| Sheriff Can Kill Crewmates As It                                  |
| Sheriff Shot Limit                                                |

### Snitch

Team : Crewmates<br>
Basis : Crewmate<br>

Once all of the snitch's tasks are completed, the imposters names will be displayed in red.<br>
Dependent on the settings, the snitch may also see arrows pointed in the remaining impostors directions when their tasks are completed.<br>
When the snitch has 0 or 1 tasks remaining, the impostors will be able to see a star next to the name of the snitch and that there is an alive snitch who has 0 or 1 tasks left.<br>
The imposters also see an arrow pointed in the snitch's direction when the snitch has one or less tasks remaining.<br>

#### Game Options

| Name                           |
| ------------------------------ |
| Snitch Can See Target Arrow    |
| Snitch Can See Colored Arrow   |
| Snitch Can Find Neutral Killer |
| Snitch Can Find Coven          |

### SpeedBooster

Create and idea by よっキング<br>

Team : Crewmates<br>
Basis : Crewmate<br>

Finishing all the tasks boosts the player speed of someone alive.<br>

#### Game Options

| Name                 |
| -------------------- |
| Boosted Player Speed |J

### Trapper

Created by そうくん<br>
Original idea by 宿主ランニング<br>

Team : Crewmates<br>
Basis : Crewmate<br>

When killed, the trapper will hold the killer in place.<br>
The time held in place on the body is decided by host in settings.<br>

#### Game Options

| Name            |
| --------------- |
| Freeze Duration |

### Sleuth

Created by Discussions<br>
Original Idea by TOuR<br>

Team : Crewmates<br>
Basis : Crewmate<br>

The Sleuth can report a body to know its role.<br>
The Sleuth has to report to know the role.<br>
The Sleuth has no settings.<br>

### Child

Created by Discussions<br>
Original idea by ???<br>

Team & Basis: Crewmates<br>

When the Child dies by any matter, the Child Wins.<br>

#### Game Options

| Name           |
| -------------- |
| Child Is Known |

### Bewilder

Created by Discussions<br>
Original Idea by Mek<br>

Team : Crewmates<br>
Basis : Crewmate<br>

The Bewilder is similar to bait, meaning that something happens when you kill it.<br>
As Bewilder, when a killer kills you they gain your small vision. Making them have small vision for the rest of the game.<br>
You can customize the vision using Settings.

### Bastion

Created by Discussions<br>
Original Idea by Mek<br>

Team : Crewmates<br>
Basis : Crewmate<br>

The Bastion can also bomb themselves or other Bastions.<br>

### Demolitionist

Created by Discussions<br>
Original Idea by Mek<br>

Team : Crewmates<br>
Basis : Crewmate<br>

When a killer kills the Demolitionist, they have a few seconds to go hide and vent, or else they will die with the Suicide Death Reason.<br>
The time is configurable. You will know when you are bombed when you see an arsonist triangle by your name.<br>

#### Game Options

| Setting Name    |
| --------------- |
| Suicide Time    |

### Veteran

Created by Discussions<br>
Original idea by TOuR<br>

Team: Crewmates<br>
Basis: Engineer

The Veteran can vent to go on Alert.<br>
While Veteran is on alert, any killing role that tries to use their kill button on Veteran, crew roles too if turned on, will make the Veteran lunge to kill.<br>

#### Game Options

| Name                                   |
| ----------------                       |
| Alert Cooldown                         |
| Alert Duration                         |
| Number of Alerts                       |
| Vet Crew Roles                         |
| What Happens if Pestilence Attacks Vet |

## Neutral

#### Settings

| Settings Name   |
| --------------- |
| Block Move Time |

### Arsonist

Team : Neutral<br>
Basis : Impostor<br>
Victory Condition : Douse and ignite all the living players<br>

When an arsonist tries to use the kill button, they douse oil onto the crewmates.<br>
To win as Arsonist, you must douse all fellow players and vent to win.<br>
To douse, you must stand next to a player after pressing kill until the orange triangle is filled in.<br>

* As a measure against blackout, after death, the Arsonist can only see the motion of committing suicide at each meeting. There is no corpse. <br>

#### Game Options

| Name                    |
| ----------------------- |
| Arsonist Douse Duration |
| Arsonist Douse Cooldown |

### PlagueBearer

Team : Neutral<br>
Basis : Impostor<br>
Victory Condition : Be the last one standing with a crewmate<br>

When an PlagueBearer tries to use the kill button, they infect the crewmate.<br>
To win as PlagueBearer, you must be the last one alive with a crewmember.<br>
To infect, you just have to press the kill button. No infecting timer. <br>
After infecting everyone, you turn into Pestilence.

* As a measure against blackout, after death, the Arsonist can only see the motion of committing suicide at each meeting. There is no corpse. <br>

#### Game Options

| Name                    |
| ----------------------- |
| PlagueeBearer Infect CD |

### Pestilence

Team : Neutral<br>
Basis : Impostor<br>
Victory Condition : Kill all Living Player<br>

PlagueBearer becomes Pestilence when they finish infecting.<br>
Pestilence is an unkillable force. When someone tries to kill Pestilence, the pestilence will kill with a lunge. Pestilence can only be voted.<br>

* As a measure against blackout, after death, the Arsonist can only see the motion of committing suicide at each meeting. There is no corpse. <br>

#### Game Options

| Name                    |
| ----------------------- |
| Pesti Kill Cooldown     |
| Pestilence Can Vent     |

### Vulture

Team : Neutral<br>
Basis : Crewmate<br>
Victory Condition : Eat Bodies to Win<br>

The Vulture can use their report button to eat the body. Making it unreportable.<br>
You can still see it though due to techincal limitations.<br>
You can change how many bodies they have to eat.<br>

#### Game Options

| Name                    |
| ----------------------- |
| Body Amount             |

### The Glitch

Team : Neutral<br>
Basis : Impostor<br>

The Glitch can vent to switch killing modes.<br>
After every meeting, they are on killing mode.<br>
Once they vent, they are on hacking mode.<br>
Hack someone to prevent them from reporting, sabotaging, killing, and venting if turned on.<br>

#### Game Options

| Name                    |
| ----------------------- |
| Kill Cooldown           |
| Hack Cooldown           |
| Hack Prevents Vent      |

### Werewolf

Team : Neutral<br>
Basis : Impostor<br>

The Werewolf can vent to activate their rampage.<br>
They can only kill during a rampage.<br>
This requires tweaking until you get it right.<br>

#### Game Options

| Name                    |
| ----------------------- |
| Rampage Cooldown        |
| Rampage Duration        |
| Can Vent While Rampaged |

### Guardian Angel

Team : Neutral<br>
Basis : Engineer<br>

The Guardian Angel can vent to temportarily prevent their target from being killed.<br>
If their target wins, so does the Guardian Angel.<br>

#### Game Options

| Name                        |
| --------------------------- |
| Protect Cooldown            |
| Protect Duration            |
| Number of Protects          |
| GA Knows Target's Role      |
| Target Knows They have a GA |

### Amnesiac

Team : Neutral<br>
Basis : Impostor<br>

The Amnesiac can report a body to take its role.<br>
After reporting, they go on and win with that team.<br>


### Egoist

Create by そうくん<br>
Original idea by しゅー<br>

Team : Neutral<br>
Basis : Shapeshifter<br>
Victory Condition : Satisfy the Impostor victory condition after all the Impostors die.<br>

The Egoists are counted among the Impostors.<br>
They have the same ability as Shapeshifters.<br>
Impostors and Egoists can see but cannot kill each other.<br>
The Egoists have to exile all Impostors before leading to Impostor win.<br>
Egoist win means Impostor lose and vice versa.<br>

**NOTE:**
- The Egoists lose in the following condition:<br>
1. Egoist dies.<br>
2. Impostor win with some Impostors remained.<br>
3. Crewmate or other Neutral win.<br>

#### Settings

| Settings Name       |
| ------------------- |
| Egoist KillCooldown |

### Executioner


Team : Neutral<br>
Basis : Crewmate<br>
Victory Conditions : Have the target voted out<br>

Executioner’s target is is marked with a diamond which only they can see.<br>
If the executioner’s target is voted off, they win alone.<br>
If the target is a [Jester](#jester), they will win an additional victory with the executioner.<br>

#### Game Options

| Name                            |
| ------------------------------- |
| Executioner Can Target Impostor |
| Executioner Can Target Neutral  |
| Role After Target Dies          |

### Jester

Team : Neutral<br>
Basis : Crewmate<br>
Victory Conditions : Get voted out<br>

The Jesters don't have any tasks. They win the game as a solo, if they get voted out during a meeting.<br>
Remaining alive until the game end or getting killed results Jester lose.<br>

### Opportunist

Team : Neutral<br>
Basis : Crewmate<br>
Victory Conditions : Remain alive until the game end<br>

Regardless of the games outcome, Opportunist wins an additional victory if they survive to the end of the match.<br>

### SchrodingerCat

Team : Neutral<br>
Basis : Crewmate<br>
Victory Conditions : None<br>

The SchrodingerCats have no tasks and by default, no victory condition. Only after fulfiling the following condition they obtain victory conditions.<br>

1. If killed by **Impostors**, they prevent the kill and belong to **team Impostors**.<br>
2. If killed by [Sheriff](#sheriff), they prevent the kill and belong to **team Crewmate**.<br>
3. If killed by **Neutral**, they prevent the kill and belong to the **Neutra team**.<br>
4. If exiled, they die with the victory condition same as before.<br>
5. If killed with special abilities of Impostors (except for [Vampire](#vampire)), they die with the victory condition same as before.<br>

#### Game Options

| Name                                             |
| ------------------------------------------------ |
| SchrodingerCat In No Team Can Win With Crewmates |
| Team To Change After Exiled                      |

### Terrorist

Create and original idea by 空き瓶/EmptyBottle<br>

Team : Neutral<br>
Basis : Engineer<br>
Victory Conditions : Finish All Tasks, Then Die<br>

The Terrorists are the Neutral Role where they win the game alone if they die with all their tasks completed.<br>
Any cause of death is acceptable.<br>
If they die before completing their tasks, or if they survive at the game end, they lose.<br>

### Juggernaut

Team : Neutral<br>
Basis : Impostor<br>

The Juggernaut starts from the starting kill cooldown.<br>
However, with every kill, their next kill cooldown decreases by the chosen amount.<br>

#### Game Options

| Name                        |
| --------------------------- |
| Starting Kill Cooldown      |
| Decrease Amount             |
| Juggernaut can Vent         |

### Hacker

Create and idea by Mek<br>

Team : Neutral<br>
Basis : Crewmate<br>

The Hacker's goal is to reach a certain number of points<br>
They reach these points by sabotages.<br>
When a Sabotage is called, and/or the Hacker fixes it, the Hacker gains a point.<br>
Reach the required amount of points to win.<br>

#### Game Options

| Name                 |
| -------------------- |
| Points Amount        |

## Attribute

### LastImpostor

Create and idea by そうくん<br>

An Attribute given to the last Impostor.<br>
kill cooldown gets shorter than usual.<br>
Not assigned to [BountyHunter](#bountyhunter), [SerialKiller](#serialkiller), or [Vampire](#vampire).<br>

#### Game Options

| Name                       |
| -------------------------- |
| LastImpostor Kill Cooldown |

### Lovers

Create and idea by ゆりの<br>

Team : Neutral<br>
Basis : -<br>
Victory Conditions : Alive at the end of the game. (other than task completion)<br>

Randomly assigned to two players (regardless of camp).<br>
This is a third camp in which both players win or die alongside one another.<br>
If your lover wins, you win.<br>
If your lover dies, you die.<br>
If the crewmates win by tasks, the lovers lose.<br>
The lovers can also win if both are still alive at the end of the game and the crewmates don't win by tasks.<br>
If the lovers win, everyone else loses.<br>
Crewmate lovers do not have tasks assigned. <br>

Example of overlapping Roles: <br>
- [Terrorist](#terrorist) Lover: You have tasks and If you die after completing the task, you will win as a terrorist. <br>
- [MadSnitch](#madsnitch) Lover: You have tasks, and you can see the Impostor after completing the task. <br>
- [Snitch](#snitch) Lover: No tasks, Impostor remains unknown. <br>
- [Sheriff](#sheriff) Lover: You can kill Impostors as usual. Whether or not you can kill depends on Roles and Options. (Impostor Lover can be killed. Crewmate Lover cannot be killed) <br>
- [Opportunist](#opportunist) Lover: Win if you survive. <br>
- [Jester](#jester) Lover: If you are voted out, you will win as Jester. If the other Lover is voted out, you are defeated. <br>
- [Bait](#bait) Lover: When the other Lover is killed and you die afterwards, the other Lover immediately reports you. <br>

## DisableDevice

Reference source : [SuperNewRoles](https://github.com/ykundesu/SuperNewRoles), [The Other Roles: GM Edition](https://github.com/yukinogatari/TheOtherRoles-GM)<br>

Various devices can be disabled (currently admin only, MiraHQ not supported)

| Settings Name         |
| --------------------- |
| Disable Admin         |
| ・ Which Disable admin |
## SabotageTimeControl

The time limit for some sabotage can be modified.

| Name                      |
| ------------------------- |
| Polus Reactor TimeLimit   |
| Airship Reactor TimeLimit |

## Mode

### DisableTasks

It is possible to not assign certain tasks.<br>

| Name                       |
| -------------------------- |
| Disable StartReactor Tasks |
| Disable SubmitScan Tasks   |
| Disable SwipeCard Tasks    |
| Disable UnlockSafe Tasks   |
| Disable UploadData Tasks   |

### Fall from ladders

There is a configurable probability of fall to death when you descend from the ladder.<br>

| Name                 |
| -------------------- |
| Fall To Death Chance |

### HideAndSeek

Create and idea by 空き瓶/EmptyBottle<br>

#### Crewmates Team (Blue) Victory Conditions

Completing all tasks.<br>
※Ghosts' tasks are not counted.<br>

#### Impostor Team (Red) Victory Conditions

Killing all Crewmates.<br>
※Even if there are equal numbers of Crewmates and Impostors, the match will not end unless all the Crewmates are killed.<br>

#### Fox (Purple) Victory Conditions

Staying alive when one of the teams (Except Troll) wins.<br>

#### Troll (Green) Victory Conditions

Killed by Impostors.<br>

#### Prohibited items

- Sabotage<br>
- Admin<br>
- Camera<br>
- Exposing by ghosts<br>
- Ambush (This may make it impossible for Crewmates to win with the tasks.)<br>

#### What you can't do

- Reporting a dead bodies<br>
- Emergency meeting button<br>
- Sabotage<br>

#### Game Options

| Name                      |
| ------------------------- |
| Allow Closing Doors       |
| Impostors Waiting Time(s) |
| Ignore Cosmetics          |
| Disable Vents             |

### NoGameEnd

#### Crewmates Team Victory Conditions

None<br>

#### Impostor Team Victory Conditions

None<br>

#### Prohibited items

None<br>

#### What you can't do

Exiting the game with anything other than host's SHIFT+L+Enter.<br>

This is a debug mode with no win Basis.<br>

### RandomMapsMode

Created by つがる<br>

The RandomMapsMode changes the maps at random.<br>

#### Game Options

| Name                |
| ------------------- |
| Include The Skeld   |
| Include MIRA HQ     |
| Include Polus       |
| Include The Airship |

### SyncButtonMode

This mode limits the maximum number of meetings that can be called in total.<br>

#### Game Options

| Name             |
| ---------------- |
| Max Button Count |

### Global RoleBlock Duration

Every role than can roleblock shares the same global cooldown.<br>

## OtherSettings

| Name           |
| -------------- |
| When Skip Vote |
| When Non-Vote  |

#### Client Settings

## Hide Codes

By activating, you can hide the lobby code.

You can rewrite the`Hide Game Code Name`in the config file (BepInEx\config\com.emptybottle.townofhost.cfg) to display any character you like when HideCodes are enabled.
You can also change the text color as you like by rewriting`Hide Game Code Color`.

## Force Japanese

Activating forces the menu to be in Japanese, regardless of the language setting.

## Japanese Role Name

By activating, the Role name can be displayed in Japanese.
If the client language is English, this option is meaningless unless `Force Japanese` is enabled.

## Credits

Roles from:
1. [The Other Roles](https://github.com/Eisbison/TheOtherRoles)<br>
2. [The Other Roles: GM Edition](https://github.com/yukinogatari/TheOtherRoles-GM)<br>
3. [The Other Roles: GM Haoming Edition](https://github.com/haoming37/TheOtherRoles-GM-Haoming)<br>
4. [Nebula on the Ship](https://github.com/Dolly1016/Nebula)<br>
5. [au.libhalt.net](https://au.libhalt.net)<br>
6. [Foolers Mod](https://github.com/MengTube/Foolers-Mod)<br>
7. [Town-Of-Us-R](https://github.com/eDonnes124/Town-Of-Us-R)<br>
8. Mek, My friend on Discord

## Developers
- [Discussions](https://github.com/music-discussion) ([YouTube](https://www.youtube.com/channel/UCAawAIWR5XfJE6T0JdYpzzg)) - Coding
- [MC-AS-Huier](https://github.com/MC-AS-Huier) - Translations
