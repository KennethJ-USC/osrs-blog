# Legacy System Anti-Patterns and Remediation through the Context of Runescape

## Brainstorming

#### Anti-Patterns and Talking Points:

- time/effort investment decisions 
  - permeates throughout this talk (and life)
- Not all old systems are legacy systems, how do they end up like this?
  - inexperience/incompetence...
  - MVP becomes production
    - "This isn't best practice but I'll go back and fix it later."
      - e.g. my name on LACC
  - service robustness not a priority
    - RuneScript created to allow non-technical content devs to code
- BAD Solutions to solving the issues of legacy systems
  - reduce turnover - and system must be robust to individuals leaving the project
    - e.g. Random Event spawning
  - REWRITE EVERYTHING
    - RS3, EoC, and the death of RS
  - "Don't touch anything"
    - LACC - sometimes features MUST be added
  - Broken? Deploy and older working version
    - OSRS - still face same issues
- Approaches to working with legacy systems (e.g. adding features, service migration, security audits)
  - DO understand the product at a high level
  - ​     DO start using version control
    - even if this hasn't been done for the system before
    - even if the service is fundamentally broken as it - and you don't think it can be broken anymore
  - DON'T rely on assumptions about how this "should" work
    - tempting because assumptions like this often would make your life easier
  - TREAD WEARILY - lot of bad information, even from original devs
    - ...that being said
  - CONSIDER: social engineering can be a 10+x speedup
    - attempt to find original dev
  -  DO NOT BE SCARED (i.e. DO) be open to tackling difficult issues as an investment in robustness
  - UNDERSTAND DATE FLOW
    - attempt to fill knowledge black holes
  - DOCUMENT EVERYTHING
    - even things that didn't work
  - 



---



### Abstract

