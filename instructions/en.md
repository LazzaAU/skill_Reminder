**Using this Reminder:**

You can set a reminder / timer or alarm by saying the following examples to Alice

- Set a reminder for 10 minutes
- set a timer for 10 minutes
- set a alarm for 10 minutes

In the following utternaces you can do as above to change between reminder or timer or alarm 
( just say reminder instead of timer or alarm )

 - "Set a alarm for 1 hour",
 - "Set a alarm for 1 minute",
 - "Can you create a timer for 3 hours please",
 - "Set a reminder in 10 minutes",
 - "create a reminder for 20 miuntes please",
 - "Set a 15 minute timer please",
 - "Set a reminder for tuesday at 8 am",
 - "Set a alarm for 8 am tomorrow",
 - "Add a 20 minute timer",
 - "create a reminder for 2 pm",
 - "Add a timer for 4pm"
 
 Alice will then ask you to set a message for the timer/reminder/alarm
 
 The reminder will then get stored in the database so if you reboot Alice she will
 restart the reminder on startup. Redundant timers will get deleted automagically
 
 You can also ask her things like :
 
 "How long is left on my timer"
  Alice will then tell you the remaining time if you only have one timer set
  Otherwise if you have multiple timers she will then respond with a list of the active timers
  that you have.
  
  To select the correct timer respond with the number of the timer she has just mentioned
  IE : " number 1"
    or reminder number 2
    
  same applies if you ask alice to "delete a reminder"
  If you ask her to delete all reminders she will ummmm....delete all reminders, after prompting you to confirm :) 
 
 **Additional events** :
 - Asking Alice to set a "Food Timer" will let alice know your cooking and therefore she will remind 
    you half way through the timer to check your food.
 - Alice can now set a "Timer" (only) without a message by saying things like
    * set a quick timer for 3 minutes
    * create a short timer for 2 minutes
    * keywords to trigger this are : "quick", "short" "breif", "simple", "lazy"
    and she will now set a timer event without the need for a topic
    
    NOTE: the limitation on this quick timer function are.
    * if you reboot you'll loose the timer 
    * you won't be able to stop the timer as it has no topic
    * you won't be able to ask how longs left on the timer as it has no topic
    * This only works for timer event, not reminder or alarm events
     
 **Sound folder**
 
 There is a sound folder with a seperate folder for each event.
 To replace the sound file with one of your choice just make sure the new sound file is named
    the same. IE: Reminder.wav unless you want to edit the code to suit
 
     
NOTES. *This skill will mostly work with Telegram and dialogView , however, it maynot work %100 due to current limitations
using continued dialog from dialogView or Telegram*

###Some Pre defined timers

The reminder skill comes with some pre defined timers for quick action.
These are as follows:

1. Brushing teeth - 2 minute timer
2. Making cup of tea - 3 minute timer
3. Making a pot of tea - 7 minutes
4. Washing your hands - 20 second timer

To activate any of these try saying sentences such as the below. or variations of it

- "Time to brush my teeth"
- "It's pot of tea time"
- "I'm making a cup of tea"
- "tell me when to stop washing my hands"
- "we're brushing our teeth"


