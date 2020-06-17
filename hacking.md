# Homebrew Hacking Rules

## 1. Introduction
The original Shadowrun hacking rules feel convoluted and bothersome. While they might provide fun for experienced players with the Matrix system,
they break the flow for everyone not involved in that system.

Because of these issues, we decided to come up with our own rules to make hacking more intuitive.

We also tried to implement a system, that can be easily used in a combat scenario.

## 2. Basic System

The system is designed for ease of use. It requires very little rules and relies mostly on the interaction of the player and the gamemaster. Creativity
in how you use and combine the commands leads to very engaging gameplay and lots of possibilities for the hacker to support the group or engage with the
world.

You may attempt to hack any system, that you have clear line of sight of. You don't have to have line of sight with your own eyes though - artificial
means count as well.

_Example: Hacker Artemis hacks a security camera from a control room. Through the camera, Artemis can see a computer terminal. The computer terminal and all
other systems that can be seen by either Artemis or the camera are now potential targets for Artemis' commands._

Every command is an opposed test of your ability and the opposing system. The hacking target rolls with _System (SYS) + Firewall (FIR)_ against the
check that the command describes. Which combination of skills and attributes is required for each command is listed in the **"Commands"** section below.

Each opposed test can have four different results:

1. Success: You have more successes than the opposing system. The command is successful and the effects come to be. The gamemaster decides how exactly
the command affects the target or what information you manage to gather.
2. Blocked: You have the same number of successes as the opposing system. The command is not successful but the system does not detect the intrusion. 
You get an additional dice in your next attempt at the same command against the same target, as you now knows more about the defenses of the system.
3. Failure: You have less successes than the opposing system. The command fails and the intrusion is detected. The detection might result in a locked
system or maybe a triggered alarm. The current hacking attempt is ended and the gamemaster has to decide, whether or not a new attempt may be started on this
system.
4. Critical Failure: You have no successes and the opposing system has at least one success. The command fails and the system locks up completely. You
are unable to further try to hack the system. If it is connected to alarms, or has internal alarm systems, those are triggered. Additionally, you have to resist 
the system shock he is experiencing by the systems defenses. You take _SYS + FIR_ psychic damage, but can reduce that damage by one for each success you roll 
on a INT + LOG check.

## 3. Modifiers

The following modifiers are some examples of things that might affect the outcome of the hack. Except for the tethering, everything is optional to use in your games.

### Tether:
You can use a Dek or a Datajack to tether yourself to a physical outlet of the system you want to hack. You dive deep into the matrix space and manipulate the
system at its deepest levels. For this, you gain a dice pool bonus of +2 for all commands you use against the tethered system as long as you are tethered.

While you are tethered, you cannot move more than 1 meter away from the target. If you yourself move more than 1 meter away from the system, or any effect forces you
to move, or moves you by other means, you take _SYS + FIR_ psychic damage, but can reduce that damage by one for each success (s)he rolls on a INT + LOG check.

To remove the tether, you have to use a complex action.

### Example modifiers:

* Extensive talks with a user of the system might give you insight into the security measures or give you a clue of the password the user might use. You get a +2 dice pool 
bonus on commands agains the system.
* Finding documentation about the security system that carelessly is stored unsecured in the office you are breaking into right now might add a +1 dice pool bonus.

## 4. Commands

### Cybercombat
	[Disable] _(LOG)_
	Disable all electronic parts in the targeted object. Has no effect on Cyberlimbs.

	[Reset] _(LOG)_
	Resets the electronics in the targeted object to factory settings.

### Electronic Warfare
	[Control] _(LOG)_
	Take control of the targeted mechanism. Only works on systems that can be controlled remotely or work autonomously.

	[Crack] _(LOG)_
	Crack the encryption of a file.

### Hacking
	[Bypass] _(LOG)_
	Bypass targeted security measure. For example: a password or a firewall.

	[Disrupt/Intercept] _(LOG)_
	Disrupt or intercept the targeted data stream.

### Computer
	[Find/Extract] _(INT)_
	Find and/or extract the queried file from a data system.

	[Obfuscate] _(INT)_
	Scramble and encrypt the targeted data file(s).

	[Execute] _(LOG)_
	Run a file on the targeted system.

### Software
	[Analyze] _(INT)_
	Gather information about target system or file.

	[Create] _(INT)_
	Create a trigger + command combo. The command will execute as soon as the trigger happens.