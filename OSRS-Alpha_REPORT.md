# OSRS Alpha | Report
This files serves as the official report for OSRS 'Alpha', (referred to as OSRS-A).

The creation, primary purpose, objectives, accomplished tasks, incidents, and eventual shutdown are cataloged and documented in this report.

## Creation
OSRS-A was created upon discovering an advanced technology labeled 'UniVault' to store Items. UniVault accept submission of 5 items at once, and would review the items to check for size and duplicates. A single copy of the system was capable of storing 124,200 Standalone Items alongside another 124,200 Shulkers.

Seeing the potential in this technology, Sir Kaddicus III initiated a project to run an instance of UniVault in a secure facility, with no limit on size, and the potential to expand the system if needed.

## Primary Purpose
The primary purpose of OSRS-A was to have a localized, personal copy of UniVault, capable of storing all artifacts within the Kædykos Nebula, including artifacts uncovered and cataloged by PCI and other groups.

## Objectives
A number of objectives were held in mind when creating OSRS-A
* Localized, completely controlled by chosen individuals
* No limit on NBT, unlike other known instances
* Personalized building and location
* Actively maintained

## Accomplishments
Two instances of OSRS-A were successfully created on **██████**, with one being located in a facility owned and operated by Sir Kaddicus III in the **████████** system, and the other being located in the MH System, partially owned and operated by a 3rd party.

UniVault was brought in immediately, and initiated. The physical system was fabricated and erected shortly after.

Testing commenced, with a number of incidents occurring. 27 Shulkers were submitted to the system, with 26 labeled _Accepted_, 1 being flagged as _Duplicate_, and 1 causing a _Disconnect Incident_.

## Incidents
A number of incidents occurred during the setup and testing of OSRS-A.

- Operator Status Unobtainable
    - This incident was caused by the systems framework not recognizing valid commands. A workaround solution was identified and deployed, resulting in Operator status being correctly obtained.
- Physical System Generation
    - The physical system was generated successfully, but it was determined to be impossible to generate a customized version. 
    - Furthermore, modification of the system was complicated (though not impossible), requiring the entire system to be taken offline while physical modifications occurred. 
    - If a storage device or terminal was accidentally altered during physical modifications, the entire process had to be restarted, as the system would not repair or regenerate storage devices, or terminals.
- Duplication Abuse
    - While UniVault claims to distinguish between Duplicates of Items or Shulkers, it was determined if even slight alterations were made to them, such as Name Changes, UniVault would read them as new Items or Shulkers, and accept them into the system.
    - This incident poses a severe danger to the system, as malicious users could fill the system with thousands of junk Items or Shulkers, each with a slightly altered Name, and UniVault would read them as unique Items or Shulkers.
- Removal of Unwanted Items or Shulkers
    - Following the Duplication Abuse Incident, removal of Items was attempted, but unsuccessful. No method was found that allowed removing Items or Shulkers from the system. 
    - Should another Duplication Abuse Incident occur, it would be potentially disastrous for the system, as none of the maliciously added Items or Shulkers could be removed.
- Disconnection
    - Upon loading a single Shulker by the name of █████████████, the user attempting to load it was expelled from the system.
    - Investigations were inconclusive, determining only that the Shulker in question worked in other locations and on other systems, but not here.
    - It has also been tentatively determined that UniVaults NBT Size Restriction was **not** a factor in the incident.
- Path Transversal Exploit
    - UniVault allows loading in "hand-picked" storage device data from a file automatically by reading the name.
    - No checks to sanitize what is fed as input were in place. 
    - Simply put, by manipulating the name of a storage device in a specific way that you then use, you can access any file on the system framework, and load it. I could not even begin to explain just how disastrous this is.
- Large Submissions
    - Submissions are locked to 5 Items or Shulkers at once, resulting in a severe input bottleneck.
    - When preparing for repeated submissions, 9 shulkers were lined up, with 5 being submitted. The remaining 4 would on occasion be removed as well, but not submitted.
    - Reproducing the disappearance produced inconclusive results, and some user error is suspected.

## Shutdown
On ██████ both instances of OSRS-A were shutdown.

Following collation of Incidents, it was decided that OSRS-A was not a viable system, and was actually quite problematic, with issues occurring from startup, and a number of potentially disastrous issues uncovered. 

Sir Kaddicus III closed the project, completely wiping the instance that was located on his facility.

The secondary instance in the MH System remains, but is not active, and has been locked down for security reasons.

# Conclusion
OSRS-A started off with interesting technology known as UniVault, but encountered a number of issues, including severe exploits and security risks. Following Incidents related to these issues, the project was shut down.

It is recommended that the UniVault technology be investigated and monitored for potential improvements. In the meantime, manual cataloging of Items and Shulkers remains the best option.


Signed,
### ***Sir Kaddicus III***