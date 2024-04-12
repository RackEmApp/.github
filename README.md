# RackEmApp Release Notes
*Platform - 12th April 2024*
 - Fixed issue saving "result based on match sections" property in league table profile
 - Fixed issue with competition groups league table profiles nlot saving/overwriting with blank values
 - Added Lola's Pool party branding to 147 sports custom screens
 - Removed table clash flag in new season wizard fixtures list for byes as its not relevant
 - Fixed a bug with Bye removal in new season wizard not working
 - Fixed an issue starting a round in a group round which is not a single day event not working

*App - 12th April 2024 (1.0.14)*
 - Fixed issue with Start Match button not appearing
 - Added message at the top of teams screen to make it more obvious that they need to swipe between teams when they are registered to more than one

*Platform - 5th April 2024*
 - Fixed issue with team handicaps not being saved/applied properly to competitions
 - Fixed break indicator in Evolve's custom stream overlay
 - Fixed issue with BD and RD not displaying on group tables, which in turn caused the competition pages to throw an error
 - Added platform dashboard for a quick view of matahces in play
   
*Platform - 2nd April 2024*
 - Removed support for Facebook and Google logins
 - Revamp of the Competition Entry management screen
 - Added "League Table Profiles" to standardise the use of league tables across leagues and competitions, and allow individual divisions to run different league table setups
 - Added Hangfire for background job processing
 - Added Hangfire job to clean up ShotClockSubscribers table

*Platform - 27th March 2024*
 - Fixed an issue when registering a new team from an existing logged in account was not loading the tabkes for the default venue correctly
 - Added support for Receipts to be generated when registering a new team and paying by Stripe
