<!-- TITLE: Regular School -->
<!-- SUBTITLE: Common bathroom rules at normal schools -->

The following rules are commonly implemented at normal public schools.
# Restroom Passes
A bathroom pass is required to use public school restrooms *at all*, even between classes. Students who lack a restroom pass and cannot hold it until after school must go in their pants.

However, just because a student has a bathroom pass does not automatically mean that the student is allowed to go to the bathroom. Each bathroom pass has a QR code indicating how the student is allowed to relieve herself. Generally, a bathroom pass has three pieces of information associated with it: holding period, toilet permission, and changing permission.

Note that some restroom passes are effectively a punishment, requiring the student to relieve themselves in an embarrassing or uncomfortable manner, such as in front of the class, in their pants, or both.

### Holding Period
The first piece of information indicates how long the student must hold it before allowed to relieve themselves. Typical values are:

* *Immediately:* The student is allowed to relieve themselves whenever they wish.
* *Wait X minutes:* The student must wait for the specified time, then present the (same) bathroom pass again.
* *At end of class:* The student must wait until five minutes before the end of class.
* *After class:* The student must wait for the full class period, then present the bathroom pass to the restroom attendant between classes.
* *Next Class, then X:* The student must wait until the next class; at the start of the next class they may be told to wait an additional amount of time (from the above list).
* *Never:* The worst kind of holding period - the student is not allowed to go to the bathroom, even between classes. They must either hold it until the end of school or have an accident. (If the student does have an accident, the "bathroom pass" is considered used, and they may use a different bathroom pass the next time they go to the bathroom.) This sort of pass is almost always issued as a punishment.

### Toilet Permission
The second piece of information indicates *how* the student is allowed to relieve themselves. Typical values are:

* *Restroom:* The student may use the school restrooms normally like a big girl.
* *Potty:* The student must use a public potty in front of her fellow students. Each classroom has a potty, and additional potties are placed in front of school restrooms.
* *Pants:* The student must go to the bathroom in their pants.
* *Pants (exposed):* Not only must the student go to the bathroom in their pants, but they must stand in front of the class and lift their skirt above their waist or lower their trousers to their thighs.

Note that "pants" toilet permission does *not* count as having an accident for punishment purposes.

### Changing Permission
Sometimes a student may have wet or soiled pants, whether because of an accident or being required to by the bathroom pass. In either case, the changing permission indicates when and how the student may change their dirty underwear. Typical values are:

* *Immediately:* The student may change their underwear immediately upon relieving themselves.
* *Wait X minutes:* The student may not change their underwear until the specified amount of time has passed.
* *At end of class:* The student must wait until five minutes before the end of class.
* *After class:* The student must wait for the full class period, then change themselves between classes.
* *Never:* The student may not change their underwear at all until they next use a bathroom pass.

Additionally, the student's changing permission may be either public or private.

### Choice
Sometimes a bathroom pass may have multiple options, each with a different holding period. For example, a bathroom pass may have the following choices:

* Immediately, Pants (exposed), Never
* At end of class, Pants, Next Class+30min (public)
* Next class+Immediately, Potty, After Class (private)

If the student presents such a bathroom pass, the teacher will tell them they may either go in their pants in front of the class, or wait until the end of class and ask again. If the student chooses to wait, they will be offered the option of going in their pants or waiting until the next class. If the student still chooses to wait, the next teacher will instruct the student to use the potty. The student does not find out how long they will have to wait for a change until after they relieve themselves.

With a choice card, usually (but not always) the shortest holding periods go with the most humiliating toilet permissions and the longest changing permissions.

# Restroom Pass Issuing
At the first day of the semester and the first day after midterms, all students are issued fifteen passes that are "After Class, Restroom, Immediately" and ten passes that are "Immediately, Pants (exposed), Never". These passes are clearly marked, with the restroom passes marked as green and the pants passes marked as red, allowing the student to ration their bathroom passes as they see fit.

For each subsequent week, the student will be issued twenty-five passes, according to the following:

* For each time the student used a pass to go in their pants, the student receives one "Bad" pass. These passes are marked as orange.
* For each *unused* pass that had a toilet permission of "pants" or "pants (exposed)", the student receives one "Average" pass. These passes are marked as yellow.
* For each time the student used a pass to use the potty or go to the restroom, the student receives one "Good" pass. These passes are marked as green.
* For each *unused* pass that had a toilet permission of "restroom" or "potty", the student receives one "Very Good" pass. These passes are marked as blue.

However, if the student had any accidents in the previous week, each accident replaces one of their passes with a "Very Bad" pass, starting with their best passes first. "Very Bad" passes are marked as red.

The passes are generated according to the following algorithm.
First, roll 3d6 to see if the pass is actually what it says. On 5 or less (4.6%), generate the pass using one category worse than what the pass is supposed to be; on 16 or more (4.6%), roll one category better. (If you roll 5 or less on a Very Bad pass, it is automatically a "Never" pass. If you roll 16 or better on a Very Good pass, it is automatically "Immediately, Restroom, Immediately".)
Then, consulting the appropriate table, roll 3d6 to determine the number of choices, then roll three times for each choice. If there is more than one choice, add 2 to the rolls for the second choice and 4 to the rolls for the third choice. If you roll Never for the holding period on any choice, don't bother rolling the other two.

## Very Bad passes
These passes are generally issued as a punishment, either for having an accident or for some other misbehavior. None of them allow the student to use the toilet or potty; if the student has a choice, it's generally only to have better odds of *not* having to stand in front of the class to wet or soil themselves and to have less time to spend in their dirty underwear.

Number of choices | Frequency
---|---
3 | 15-18 (9.3%)
2 | 11-14 (40.3%)
1 | 3-10 (50%)

Holding Period | Frequency
---|---
At End of Class | 15-18 (9.3%)
After Class | 12-14 (28.2%)
Next Class | 9-11 (36.6%)
After 1 Hour | 6-8 (21.3%)
Never | 3-5 (4.6%)

Toilet Permission | Frequency
---|---
Pants | 12-18 (37.5%)
Pants (public) | 3-11 (62.5%)

Changing Permission | Frequency
---|---
After Class | 16-18 (4.6%)
Next Class | 12-15 (32.9%)
End of Next Class | 8-11 (46.3%)
Never | 3-7 (16.2%)

## Bad passes
These passes indicate that the student is going to the bathroom more often than the recommended three times per school day. These mostly give the student the choice of going in their pants fairly quickly or waiting a long time to use the potty.

Toilet Permission | Frequency
---|---
Restroom | 17-18 (0.5%)
Potty | 14-16 (15.7%)
Pants | 9-13 (57.9%)
Pants (public) | 3-8 (25.9%)

# Accidents
Sometimes a student isn't able to hold it for as long as their bathroom pass tells them they must, or they need to go to the bathroom more than they have passes. If a student wets or soils themselves wihtout using a bathroom pass, or before their bathroom pass gives them permission, this is considered an *accident*.

All students who start to have an accident must immediately stand up if they are sitting, and remain standing until they have finished going to the bathroom in their pants. They must then report to the nearest responsible adult, declare that they have had an accident, expose their wet or soiled underwear as instructed, and receive a reprimand (and a spanking, at the faculty member's option). Once this is done, they must then remain standing in a visible location with their underwear exposed.

If a student has an accident during class, after receiving their punishment, they must stand in front of the class for fifteen minutes. If there is less than fifteen minutes in class, they must remove their skirt or trousers and go to their next class in just their top and underwear.

If a student has an accident between classes, after receiving their punishment, they must remove their skirt or trousers, stand beside the restroom until the bell rings, and may not put their skirt or trousers on until they reach their next class. This will not count as tardiness, but they must stand in front of the classroom for ten minutes after they arrive at the next class.

If a student has an accident during lunch, after receiving their punishment, they must remove their skirt or trousers, return to their table to collect their tray, and finish their lunch at a standing table on the stage of the cafetorium.

If a student has an accident after the end of school, they will not receive any punishment from the school, but they may not change before going home. Their parents are considered to be responsible for punishing the student appropriately.

# Bathroom Checks
Students are considered to have had an accident if they've leaked even a little bit. Since students have reason to conceal small leaks, faculty members have the authority to take action to keep the student honest.

## Potty Dancing
If a teacher deems that a student is potty dancing (crossing their legs, fidgeting excessively, or otherwise trying to control their bodily functions by means other than their sphincters), the teacher may ask the student if they need to go to the bathroom. If the student answers yes, they must immediately present a bathroom pass, which is handled as normal; if the student answers no, they may not use a bathroom pass for the remainder of class.

## Underwear Checks
If a student has used a bathroom pass, the teacher may do an underwear check. When doing an underwear check, the teacher goes to the student's seat and inserts their hand up their skirt or down their trousers, feeling the crotch and buttocks of the student's underwear for any sign that the student has urinated or defecated. If the student was already wet or soiled before using the bathroom pass, it is up to the teacher's judgment whether the state of the student's underwear indicates just the prior accident or a fresh one. If the teacher deems that the student has had an accident, the student must stand, expose their underwear, and finish going to the bathroom in their pants; they will then receive the appropriate punishment for their accident.
