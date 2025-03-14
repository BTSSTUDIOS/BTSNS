# BTS STUDIOS NAMESPACES: A BITCOIN METAPROTOCOL

This is an archived documentation for  v 1.0.01

For more information see:
* https://github.com/btsstudios
* https://BTS.NETWORK

                      
                                    .,,╓╥g╦╦╦╦╦≥╥w,.
                              ²╔╦Ñ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫ÑN╦╥,
                         ,╔╦╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫ÑNw
                      ,╦╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ╦.
                   ,╦╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ╦
                 ,Ñ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫N.
               ,╬╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫N
              ╦╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫N
            ╔╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ.
           ]╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╦
          ╟╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫ÑÑÑÑÑÑÑÑÑÑÑÑÑÑÑÑÑÑÑÑ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫N
         ]╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ╨``                       ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫N
        ]╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ`                           ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫r
        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ         .²,,,,,,,,,,        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫
       ]╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫        ╦╫╫╫╫╫╫╫╫╫╫╫╫╫        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫H
       ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫       :╫╫╫╫╫╫╫╫╫╫╫╫╫╫        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ
      j╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫N       "╩Ñ╫╫╫╫╫╫╫╫╫╫╫        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫
      j╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Nw                           ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫H
      j╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ╨`                          ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫H
      j╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫"         ,.,,,,,,,,,,        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫
       ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫`       ╔Ñ╫╫╫╫╫╫╫╫╫╫╫╫╫        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫
       ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫H
       ╙╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫
        ╟╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫U        "╨╩ÑÑÑÑÑÑÑÑÑÑÑ        ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫H
         ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫N                             ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ
          ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫N.                          ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ
           ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫ÑN╦≥w╓w,,,,,,,,,,,,,,,,,╔╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ
            ╨╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫M
             "╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ`
               ╨╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╨
                 ╨╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ╨
                   ╙╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ"
                     `╨╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ╨`
                        `╙╩╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ╩^
                            `"╨Ñ╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫╫Ñ╨"
                                  `"╙╨╩╩╩ÑÑÑÑÑÑÑ╩╩╩╨^``
    
---
^[ [^ascii ^art ^copy & pasta](http://bts.network ^] 

                   .-----------------------------------------------ú  ú
                   :  ᗺTS STUDIOS : NAMESPACES STANDARD: METAPROTOCOL :
                   ú  ú-----------------------------------------------'

                Your FOREVER home on ᗺITCOIN / v1.00


                         1.  What's this ᗺTS namespaces thing?
                         2.  BTSNS: NAMES ON BITCOIN
                         3.  MINTING SPECIFICATIONS & FORMATS
                         4.  OWNING A PIECE OF THE ACTION
                         5.  ᗺonus stuff
                         6.  Gonna ᗺe ᗺlunt with ya
                         7.  Credits & acknowledgements
                         8.  Contact
                         9.  Status
                         10. Legal Stuff
                         11. References
                         12. TL;DR
                         
                       
                         **Original Post Date:** December 28, 2023
                         **Namespace Creation Date:** July 16, 2023 
                         >https://ordiscan.com/inscription/17352386<


--------------------------------------------
1. WHAT'S THIS ᗺTS STUDIOS NAMESPACES THING?
============================================


   BTS Studios: Namespaces Standard
   
   Welcome to the official documentation for BTS Studios: Namespaces Standard (BTSNS). 
   
   This standard aims to create a decentralized, bitcoin-based top level domain 
   naming system that empowers users to own and control their  digital identities 
   across BTS Studios platforms making your bitcoin address HUMAN READABLE.
   Which makes your bitcoin wallet address even easier to find and use!!!
   
   And it's RUNNING ON BITCOIN, RIGHT NOW!! 🚀
   
   BTS Namespaces are your gateway to the decentralized future of film.  
   Think of them as your digital address in the BTS Studios universe, built on
   the secure foundation of the Bitcoin blockchain.  
   
   These aren't just names; they're your stake in the revolution.  
   Claim your .bts, .art, .movies, .film, or other relevant domains and become
   a part of the movement reshaping Hollywood. It's more than a name; it's a 
   declaration.  It's your flag planted in the landscape of decentralized film. 
   Join us as we build a new era of cinematic experiences, powered by bitcoin
   and owned by the community. 
      
   Secure your piece of the future, one decentralized .bts domain at a time.
      
   Where Film Meets Forever on Bitcoin

   We paid our dues, broke the mold, and now BTS Studios has pulled off a 
   cinematic coup – we’re the first film studio to register and inscribe 
   top-level type domains (NAMESPACES) on the Bitcoin layer one blockchain, 
   upstaging Hollywood and igniting a decentralized film revolution! Join us 
   on this historic journey, own your piece of the future, and let’s rewrite 
   the script together!

   Upstaging Hollywood

   The world of naming is undergoing a seismic shift, and BTS Studios is at the
   forefront of the movement. We’re thrilled to unveil .BTS Names, a unique 
   namespace BUILT DIRECTLY ON THE BITCOIN BLOCKCHAIN, offering an unprecedented 
   level of decentralization, ownership, Elon, Mark, and even Besoz won't be 
   able to take anything away from you lol. 
   
## Built directly on the BITCOIN blockchain

## No Strings Attached:

   Forget the convoluted schemes of DAOs, tokenomics, and premines. 
   BTS Names are refreshingly simple: write a name, own it forever. 
   There’s no central authority, no gatekeeping, no hidden fees, 
   
#  Just YOU, your name, and the immutable power of ᗺITCOIN.

## NO HIDDEN FEES

## NO RECURRING FEES
   
#  So inscribe yourself a .bts name on the most goated blockchain in history!!!!   
   
   
   Imagine the possibilities:

   Use your .bts name as your Lightning address, simplifying Bitcoin 
   transactions and payments.

   Explore .bts names in Bitcoin explorers, showcasing your digital 
   identity on the most secure network in the world.🏆

   Unleash your creativity! .BTS Names can be used in countless ways,
   from personal branding to community projects and beyond.🏆

        ᗺeyond Domains: Domain names you own forever🏆

   .BTS Names are more than just domain names; they’re a gateway to a new era 
   of blockchain-based identity and expression. We’re just scratching the 
   surface of what’s possible, and we invite you to join us on this exciting 
   journey.
   
   
#  The Benefits of .BTS Names:

   Decentralization: You control your name entirely, FREE from any central 
   authority.

   Transparency: All names and transactions are publicly visible on 
   the Bitcoin blockchain.

   Immutable Ownership: The first person to write a name owns it forever,
   no take-backs.
   
   Security: Built on the bedrock of Bitcoin, ensuring the 
   highest level of protection.

   Seamless Integration: Use your .bts name as a Lightning address, 
   public Bitcoin key, and more.

   Community Engagement: Join a vibrant community of Bitcoiners
   and BTS Studios executive producers.

   Endless Possibilities: Explore the limitless creative potential 
   of .BTS Names.

   Future-Proof: Designed to adapt and evolve alongside the 
   ever-changing blockchain landscape.

   Equal Opportunities: Open to everyone, regardless of 
   background or technical expertise.

   Uniting ᗺlockchain and Cinema: A powerful fusion that 
   redefines the future of naming.
   
   Think of your .bts name as your passport to a decentralized film frontier. 
   
   IMAGINE/INSCRIBE:

   * Your “hello.bts” as your Bitcoin address: Ditch the confusing jumble of 
     numbers and letters.Send and receive funds with a name that reflects 
     your personality and passion.

   * Build your own film oasis:.FILM.MOVIES.MUSIC are just some of the 
     namespaces we have created. FIRST IS FIRST

   * Own your story, forever: No more platform take-backs or algorithm blues.
     Your .bts name lives on the Bitcoin blockchain, secure and unchangeable, 
     a digital legacy you can be proud of.

   * This isn’t just about cool tech; it’s about freedom and belonging. 
     We, the BTS Studios team, are film fanatics and crypto believers just 
     like you. We’ve been working tirelessly behind the scenes to build the
     most vibrant film and crypto community on the planet, one .bts name 
     at a time.

   * And getting started is as simple as clicking your fingers. 
     No complex setups, no premines, no confusing jargon. 
     Just choose your .bts name, inscribe it to your Taproot address, and boom!
     You’re a citizen of the decentralized film universe, ready to connect, 
     create, and own your piece of the future.
     
#    THIS IS HOW:

        Choose you .bts name for example HELLO.BTS

        Go to your favorite inscription service like https://ordinalsbot.com/

        Inscribe to your bitcoin taproot address and that’s it!

        This is just the beginning. We’re constantly innovating, pushing 
        boundaries, and building new bridges between the world of cinema 
        and the power of blockchain. Join us on this journey, inscribe your 
        .bts name, and let’s rewrite the story of what it means to be a 
        filmmaker, a crypto enthusiast, and most importantly, a member of 
        the coolest community on the web.

        Don’t forget to share your ordinal inscription!We can’t wait to see
        how you’ll use your name to make your mark on the blockchain. 
        Stay tuned for more exciting updates as we continue to build the 
        future of film and blockchain, one community at a time.

##      AND HAVE A HAPPY NEW YEAR!!!

#    Ready to own your forever? Visit the inscription website and inscribe your .bts name today!
   
   

-----------
2. BTSNS: NAMES ON BITCOIN
===========

   ❌ No token  ❌ No DAO  ❌ No premine  ❌ No gatekeepers  ❌ No fees  
   ❌ No influencers  ❌ No artwork  ❌ No contracts  ❌ No front end  
   ❌ No keys  ❌ No tokenomics  ❌ No TEAM INTERFERENCE  ❌ No spaces 
   ❌ No ads  ❌ No incentives  ❌ No high priests  ❌ No annual fees 
   ❌ No renewal fees  ❌ No whitepaper

   ✅ Not coming soon

   ✅ ALL data on Bitcoin 🔐🟧
   
   ✅ **It works NOW on Bitcoin!**
   
   Built on Bitcoin. Simple.  No tokens, no fees, no nonsense.  It just works. 
   
               
                           😱LIKE RIGHT NOW!😱  


-----------------------------------
3. MINTING SPECIFICATIONS & FORMATS 
===================================


 1. MINTING/REGISTERING NAMES (RULES)
 ------------------------------------------------------
   
   The syntax provided applies to all BTSNS namespaces,
   
   Make your bitcoin wallet sexy again by:


   *  YOUR TAPROOT BITCOIN ADDRESS IS REQUIRED FOR THIS
   
   *  Using text/plain;charset=utf-8 characters and emojis
   
   *  Some indexers might have issues with emojis so assume the risks
   
   *  TrueType, CP437 charset, Emojis, Text Encoding, give em all a try!!

   *  .bts, .film, .art, .movies, .executiveproducer, .photography, .music, 
      are just some of the domains you can register.
      
   *  Hell, you can even have a .meow domain as well 🙀
   
   
#  Mint names
  
   The syntax below applies to all SNS namespaces, 
   
   for example .bts .film .art and so on, plus all future namespaces. 

   New names can be minted (inscribed for the first time) as ordinals with 
   only a Bitcoin transaction. This process is open to anyone   
   that can inscribe. 


# 2. MINTING/REGISTERING NAMES (SIMPLE REGISTRATION)
 ------------------------------------------------------
    Registering names
    Simple registration

    To register a new name within the .bts Name System simply inscribe an 
    ordinal containing your desired name. Here is an example. 
    
### 1. Simple Inscription format    

```
hello.bts
```

3. MINTING/REGISTERING NAMES (ADVANCED)
 ------------------------------------------------------
 
## Advanced Registration

   Advanced registration: take control of your namespace's narrative! 📝 
   JSON5 lets you add those extra chapters, like a director's cut with 
   alternate endings.  
   
   Optional, but highly recommended for those who want to write their own story.
   
   
## 1. Advanced Inscription format   

```json
{
  "p": "bts",
  "op": "reg",
  "name": "hello.bts",
  "avatar": "0e2235a1d1cf30c677f5bb69104fadfd808a495ca01a443fa58b1a2a0043bcfbi0",
  "rev": "bc1pwzc90fetrntx6f83gmzu9qcpzhwgx028jccqdmuedkapvkps60sslucha4",
  "relay": "83b77f64530771b7278867efb3b12e7184b4a65ce4bd0ba11134a6ee06b8ac6ai0"
}
```

## Relay examples

   Relays allow a BTSSNS name to point to another inscription. 
   Similar to an "a record" in DNS on the traditional web2. 

   This is different than recursive inscriptions. 
   Recursion inserts the content of one inscription into another. 
   
   Relay simply establishes a link, pointing one inscription at another, 
   giving the target inscription a human readable name. 
   
   Examples below: 
```
white-paper.sats 
https://www.ord.io/12805283


{ 
  "p": "sns",
  "op": "reg",
  "name": "white-paper.sats",
  "relay": "85b10531435304cbe47d268106b58b57a4416c76573d4b50fa544432597ad670i0",
}
Relays to an early inscription of the Bitcoin white paper: https://www.ord.io/54


taprootwzrd.sats
https://www.ord.io/12806132


{
  "p": "sns",
  "op": "reg",
  "name": "taprootwzrd.sats",
  "relay": "0301e0480b374b32851a9462db29dc19fe830a7f7d7a88b81612b9d42099c0aei0",
}
Relays to the infamous 4 megggor: https://www.ord.io/652
```


##    Registration Limitations: The Script You Must Follow. 📜

###   In this grand cinematic undertaking, certain rules are non-negotiable:
  
   *  The First Take Wins: Only the initial inscription of a 
      name or namespace will be deemed valid. 🎬
   
   *  One Scene, One Action: Each ordinal inscription is 
      limited to a single name operation. 🎞️ 

   *  Embrace the Spectrum: Any UTF-8 character is permissible,
      allowing for a diverse cast of names. 🎭
      
   *  The Power of Lowercase: Capitalization is merely a costume;
      all names and namespaces  will be indexed in their lowercase form. 🤏
      
   *  No Gaps in the Story: Spaces within a name are strictly forbidden,
      ensuring a seamless narrative. 📝
      
   *  The Single Period Rule: Only one period is allowed within a name. ⚫
      

#  BTSNS Core Overview
    
    Names on BITCOIN, they’re like a box of chocolates – you never know what 
    characters you’re gonna get! 🍫 Because it’s permission-less, no one's 
    playing character police. Other systems? They’re like a tightly 
    scripted drama. We started full well knowing this was going to be 
    open source and once its out in the wild, it cant be stopped. 
    
    It's our 'Let's see what happens' kind of
    movie, and it's been a wild ride! 🎢
    
### OUR GIFT TO THE WORLD, ENJOY!
     
    Writing names to Bitcoin is permissionless, meaning no service can enforce
    character validation at the point of inscription. Other naming systems 
    have  struggled with complexity and disputes over valid characters.
    These realities, combined with the fact that BTSNS began as an experiment, 
    makes this a growing process. It's literally the wild west! 

    Solution: BTSNS Core
    
    BTSSNS Core defines a stricter subset of valid characters and a limit on 
    length which will improve BTSSNS robustness for applications 
    like future wallet integration's and resolution. 

    
##   Core Character Set
   
  *  Letters (a-z)

  *  Numbers (0-9)

  *  Hyphen (-)

  *  Underscore (_)

  *  Upper or lowercase characters are both valid, but will indexed as lowercase.

   
##   Core Name Length
    
  *  Name: Must be ≤ 63 characters

  *  Namespace: Must be ≤ 63 characters

  *  Combined: name, plus name space plus . can be up to 127 characters

  *  These constraints mirror DNS standards and prevent indexing edge cases.
  
  *  There is no specification for subdomains in BTSSNS yet.
  
     These constraints? They're like those unexpected plot twists in a
     M. Night Shyamalan movie – they might seem weird at first, but 
     they're there to prevent indexing 'edge cases' that would totally 
     ruin the ending. 🎬



   
   
| Key      | Required? | Expected          | Description                                                                                             |
|----------|-----------|-------------------|---------------------------------------------------------------------------------------------------------|
| p        | Yes       | bts               | Helps indexers identify the btsns protocol.                                                              |
| op       | Yes       | reg               | Tells indexers this is a new name.                                                                      |
| name     | Yes       | BTS name          | Name: Your desired name. Including .bts, or another namespace, is required.                               |
| avatar   | No        | Inscription ID    | Avatar or profile pic. Specify with inscription ID.                                                      |
| rev      | No        | Bitcoin address   | Reverse resolution: Sets the Bitcoin address for this name.                                              |
| relay    | No        | Inscription ID    | Tells indexers this BTS name is a pointer, or relay, to another inscription. Specify with inscription ID. |

----------------------------
4. OWNING A PIECE OF THE ACTION
============================


 3.1. A Whole New World
 --------------------------

   Just like real-world ownership, BTS Studios tokenizes films.
   This means fans can invest in projects they believe in, own 
   digital assets like GOLDEN TICKET NFTs, and share in the 
   success of the films they support.


 3.2. Streaming
 --------------

   Stream Seamlessly, Rewardingly:
   
   Forget the limitations of traditional streaming services. 
   BTS Studios offers a decentralized platform where fans 
   can stream films directly, with a portion of the revenue 
   automatically shared with the filmmakers and token holders.
   
   This creates a win-win situation for everyone involved.


------------------
5. BONUS STUFF
==================


   We recommend going about this a certain way, to maximize privacy one should
   create a new taproot address via you favorite wallet provider. There are 
   many methods but we prefer using hardware wallet solutions like "ledger" etc.
   
   
   
   *  "SUPERPOSITION" the movie is still being developed
   
   *  Original ᗺlog post Originally published on December 28, 2023
   
   *  You can watch Bidkar act in one of the pirates of the Caribbean movies 

      
      
      
-----------------------------
6. GONNA ᗺE ᗺLUNT WITH YA 🫵
=============================


   Were so decentralized, It's Scary (But in a Good Way) Okay, folks, let's
   talk decentralization. In a world of *permissioned* chains and 
   *permissioned* apps (aka, the "please sir, may I have some more" of 
   the blockchain world), BTS Studios went full *Mad Max* and built something
   truly untamable 🤯
   
   We're not getting rich off this. 😉 BTS Studios doesn't make money 
   from the namespaces themselves. This is about building something bigger
   than us, where the community – the folks holding those domains as sats 
   and the miners keeping the lights on – are the ones who truly benefit.
   
   And get this:Not even *we* can mess with it.  The BTS Studios team? 
   We're hands-off.  We built it, we launched it, and now it's out there 
   in the wild, thriving on pure Bitcoin power.  Think of us as the benevolent
   overlords who unleashed this beast... but without the "overlord" part.
   We make *zero* profit from the names themselves – it's all yours, baby.
   You, the domain holder, and the miners keeping the Bitcoin train chugging
   along are the only ones reaping the rewards.  We're just here to watch
   the revolution unfold (and maybe sell some popcorn). 🍿

   So, grab your .bts, .art, .movies, .film – whatever floats your 
   decentralized boat – and join the party. TODAY! 
   These namespaces are forever.  Seriously.  
   We're building the future of film!  
   Or at least, we're really trying our ᗺest.  
   Don't tell anyone we said that. 😅
   
   
   *  BTS STUDIOS team makes no profits and made this to be FULLY DECENTRALIZED.
   
   *  Only the inscribers and bitcoin miners make a profit. 

   *  Try to shut down BTS Studios Namespaces.  Go ahead.  We dare you.  
      (Hint: You'd have to shut down Bitcoin.  Good luck with that.) 



-----------------------------
7. CREDITS & ACKNOWLEDGEMENTS
=============================


   - Memes, documentation and carrying the torch by BIDKAR.BTS
   
   
   THANKS TO:
   ----------
   
   - That random asciiart website, for this cool ascii art. 
   
   - Bigblueterminal for markdown help
   
   - The .sats folks, for being the inspiration to create our own namespace.
     THANK YOU
   
   - Satoshi Nakamoto, for creating BITCOIN, the most awesome thing 
     since sliced ᗺread.
   
   - The rest of the BTS STUDIOS TEAM ANDRE.BTS,LANDON.BTS,JOEY.BTS 
     would like to say hi
     
   - The world for being what it is and making us reralize that true decentralization
     is rare.
     

----------
8. CONTACT
==========


   I can be reached at:   email - Bidkar -AT- BTS -DOT- NETWORK
                            www - http://BTS.NETWORK
                           blog - http://BLOG.BTS-STUDIO.IO

   Spam and/or excessive dumbness will be ignored, deleted, spindled,
   mutilated, and given a rotten tomato rating.
      
---------
9. STATUS
=========
   
   Version 1.0.0 is live on Bitcoin mainnet! Our protocol is now officially 
   'superpowered'. Though we are stable, like any good superhero, we are
   always looking to improve our powers. Share your feedback, and help us 
   'evolve'!


--------------
10. LEGAL STUFF
==============


   BTS STUDIOS namespaces is completely open source and free to use.

   You should have received a copy of the license along with this work. If
   not, see <http://creativecommons.org/licenses/by-sa/4.0/>.

             
             
             (c) 2025 BTS STUDIOS - BIDKAR.BTS - ANDRE.BTS - LANDON.BTS


------------------
11. REFERENCES
==================
### References

  .bts Namespace inscription date and time: https://ordiscan.com/inscription/17352386

  .movies Namespace inscription date and time: https://ordiscan.com/inscription/19867600

  .film Namespace inscription date and time: https://ordiscan.com/inscription/18503962

  .music Namespace inscription date and time: https://ordiscan.com/inscription/18506661

  “Elon Musk’s X takes @X handle from longtime 
  Twitter user”: https://www.nbcnews.com/tech/tech-news/elon-musks-takes-x-handle-longtime-twitter-user-rcna96074

  Ordinal inscriptions service https://ordinalsbot.com/

------------------
12. TL;DR
==================


### TL;DR

BTS Studios NameSpaces is like the wild west of domain names but with Bitcoin’s Ordinal protocol
as their trusty six-shooter. They’ve created a bunch of fun namespaces (like .bts and .art) 
that let you stake your claim on the bitcoin blockchain.

there is only one rule

FIRST IS FIRST

There’s no central
sheriff here—just you, your claim, and the bitcoin blockchain.

Use ANY inscriber (BTS STUDIOS INSCRIPTION TOOL COMING SOON)

CANT BE SHUT DOWN:YOU HAVE TO SHUT DOWN BITCOIN : GOOD LUCK WITH THAT

The future? It could be awesome—or full of memes. Either way, it’s an exciting 
ride for those ready to embrace the decentralized wild west!


[LINKS]:  https://bts.network
          https://bts-studios.io/
          https://blog.bts-studios.io/

