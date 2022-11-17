# Tahoe-Con 2 2022 Berlin: Un-Agenda

![Photo of an "HR Jar", stuffed with cash and transgressions](https://i.imgur.com/0wBahYy.jpg)

*It was a marvel of just-in-time engineering*

## Introduction:

A small group of core Tahoe folks got to meet up in Berlin, mostly due to being affiliated with the Least Authority Summit. We were able to spend time together in person and have some much-needed conversations face-to-face. The notes below are not complete, nor do they capture the full nuance and magic of the time we spent together. It can't be overstated how valuable spending an extended amount of time in meatspace with the people you have worked with asynchronously, across timezones, in terse (and sometimes verbose) messages, in meetings of various mood, over the years, can be. **These notes are not comprehensive and are meant to serve as an outline of what we were able to unite on and the events that transpired.** We invite any current or interested Community members to reach out with any questions about Tahoe-Con, these notes or suggestions for collaboration. 

## Friday, October 21:
- 17:00: Informal Welcome or Goodbye Pizza @ Pomodorino 
    - In attendance: Shae, Piegames, meejah, Jean-Paul, May-Lee
- 19:00: Tahoe-Con 2 Kick-off @ C-Base
    - In attendance: Shae, meejah, Jean-Paul, May-Lee, Bjørn
        - Tour of C-Base from Fabien from the Bodensee
        - "Stammtisch"/roundtable discussion
            - "Fun Facts"
        - Light sightseeing/walking tour: R.A.W. Gelände
            - [Teledisko](https://www.teledisko.com/) was occupied 

## Saturday, October 22:

- 09:30: Opening Breakfast/agenda planning @ Hotel New Berlin
    - In attendance: Shae, meejah, Jean-Paul, May-Lee
        - Over breakfast, we finalize the Agenda 

- AGENDA:
    - Snake Dev Solid Foundations Proposal 20 min
    - Codewalk 1H
    - Roadmap 30 min
    - What is Governance? 30 min
        - How are BTC spent (what is decision process)
    - Discuss Project Goals 45 min
    - Bonus Round!
    - Talk to Pete

![JP walks the code walk](https://i.imgur.com/FQzRMnV.jpg)

*Code walk and some live coding together*

- 11:00: Morning Session @ Least Authority Offices
    - In attendance: Shae, meejah, Jean-Paul, May-Lee

- Notes:
    - Snake Dev:
        - Summary: 
            - Tahoe has changed a lot in the last two years, and we should change our processes, in particular those involving our contractors through Open Collective, to better serve the organization. In addition, others have recently made it known that they would like to participate in the organization in high-level leadership and we want to open the way for their stewardship. Additionally, we want to continue the work that has been going on with maturing Tahoe's administrative processes.
        - What has been our experience like working with outside contractors over the years?
            - Which contractors have been easy to work with?
            - Which have been challenging?
            - How have contractors helped build (or hinder) the community?
        - Who has been contributing to the project?
            - We think Itamar has been contributing heavily to Tahoe-LAFS
        - Granular invoicing/transparency
        - Shae knows ppl who might want to contribute
        - Need more transparency
        - Know # hrs/pP
        - Pick items from SnakeDev Proposal and make RFP
    - Codewalk
        - Summary:
            - Jean-Paul (driving) and meejah explain Tahoe-LAFS to Shae and even do a bit of live coding 
        - Have erights session
        - WaterKen
    - Roadmap
        - Summary:
            - Part 1: Everyone fills out 5 Post-Its with what they think Tahoe needs to have happen
            - Part 2: We discuss the difficulty level and requirement for outsider participation
            - Part 3: We assign points value to each of the items that were decided on as a means of categorizing difficulty
        - Intro Contributor Docs
        - Ship GBS
        - Talk to Recurse Center
    - Governance
        - Write down stuff
        - Send to board for signoff
        - Document this
        - Quarterly Governance meeting consensus
        - Establish process before bad things happen
        - Why not have public budget?
            - Sensitivity to financial side
            - But free software project
            - Have to update the budget
            - Ask: Whole governance process should be more open
                - Announce in IRC
                - Signal group?
                - mailing list?
            - Have governance group channel
            - Record governance meeting audio
            - Governance monthly meeting
            - Summarize quarterly
            - Other weeks technical
            - Agenda by Friday for Monday meeting
            - Board meeting end of November
            - Estimate hours we will put in across the team

    - 15:00 or so: Break/Shae leaves for the airport

![Multi-colored Post-Its cover the wall with Roadmap items](https://i.imgur.com/VCe6wvL.jpg)

*2023 Roadmap (DRAFT)*

- After 15:00: Final Afternoon Session @ Least Authority Offices
    - In attendance: meejah, Jean-Paul, May-Lee
        - Governance (approx 1 hour)
            - We talk about: 
                - How does the Budget get made?
                - When do we want to meet with the Board?
                - How do we want to redo our meetings schedule?
        - We also tried to get in touch with Pete via IRC
        - Closing session (30 Minutes): Tahoe in 5 years
            - A fanciful brainstorm in which we imagine an idealized outcome for Tahoe-LAFS in 5 years' time

    **        - DREAMS (5-year)**

        - multiple professional tahoe grids
        - multiple tahoe-using client apps
        - certification
        - client apps use third-party grids


        - strava alternative: can share stuff w/ friends over tahoe
        - picture-frame app shares photos over tahoe

        - developers have tutorials for their platforms
        - tahoe client libraries for popular platforms (ios android desktop etc)

        - haskell client libraries
        - high-performace (haskell?) storage server
        - agda / idris server

        - modernized capabilities
          - post-quantumm
          - append-only
            - security properties (transaction log)
            - kind-of like snapshot stuff in magic-folder?
            - sac-weaves, maybe? (sac-lines)
          - multi-writer
          - collaboration
            - CRDTs
            - google-docs, maybe?

        - developers know that they _have to_ use tahoe (or similar)
          - privacy-aware
          - embarassing to NOT do it

        - federated grids
          - e.g. two friends using Strava-thing but on different grid-providers
          - don't have to be customer of _every_ grid so i can see data from friends
          - "guest access"? (e.g. let friends see your shit w/ _no_ provider account)

        - fund future development (revenue stream)
          - sustainable funding
          - keep project going
          - what do other projects?
            - not get popular: die
            - not get popular: passion-project
            - get popular: sell services
            - get popular: get donations

          - maybe Tahoe is its own non-profit
          - join some other foundation

        - revenue streams
          - we run the biggest professionally managed grid there are
          - get micropayments (via API etc)
          - ZKAPs? lightening network
          - ...but amazon does it cheaper than you
            (legal solution? AGPL?)
          - so maybe re-license it somehow, ultimately

          - feels like non-profit route is most compatible with tahoe-now

        - public-benefit corporation?

        - cool stickers (i.e. people WANT our stickers)

        - capability-theory taught to undergrads (with tahoe as the example)
          - probably after PHd theses getting written about ^
          - new capability types? are these PHd / masters work?

        - more core contributers (a "healthy" number)
        - healthy number of them


        * GOALS

         - "the goal of Tahoe-LAFS is to give you soverignty over your data"
         - "you get provable cryptographic control of your data"
           (many twinkle fingers)

- 18:00: Closing Team Dinner @ Jäger und Lustig
    - In attendance: meejah, Jean-Paul, May-Lee
        - Meats on meats to end the meeting :) 

- Bonus Round: On the way back to the hotel take a couple of rides on the zipline in the playground.

## Afterward:

We give thanks to the following, and many more, without whom this project would not exist:

Zooko Wilcox  
Amber O'Hearn  
Liz Steininger  
Brian Warner  
Peter Secor  
The Team at Least Authority  
And everyone else :)   

Community members who expressed interest in, but could not attend this year:

CCX  
Fenn  

Till next time!
