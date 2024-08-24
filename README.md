# ```Social Tracker Tool```

# Owenr Information 
<p align="center">
  <a href="https://github.com/Sunnyji7256/readme-typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?lines=Sunny%20Ji&font=Fira%20SemiBold&center=true&width=480&height=45&color=ff0000&vCenter=true&pause=1000&size=40" /></a>
</p>

<p align="center">
  <a href="https://github.com/Sunnyji7256/readme-typing-svg">
    <img src="https://readme-typing-svg.demolab.com/?lines=Full-stack%20web%20app%20and%20BOT%20developer;Experienced%20UI%2FUX%20Designer;2%2B%20years%20of%20coding%20experience;Always%20learning%20new%20things;A.I%20DEVELOPER%20&font=Fira%20Code&center=true&width=500&height=45&color=f75c7e&vCenter=true&pause=1000&size=22" /></a>
</p>

Follow On Github         
<a align="center">
<a href="https://github.com/Sunnyji7256"><img height="40px" title="Github" src="https://img.shields.io/badge/Sunny-Ji-blue?style=for-the-badge&logo=github"></a>               
Telegram Channel          
<a align="center">
<a href="https://t.me/Noob_to_pro_hack"><img height="40px" title="Telegram" src="https://img.shields.io/badge/Hacking by-Noob hacker-red?style=for-the-badge&logo=telegram"></a>
Telegram I'd                
<a align="center">
<a href="https://t.me/Sunny_ki_duniya"><img height="40px" title="Telegram" src="https://img.shields.io/badge/Sunny-Ji 🇮🇳-pink?style=for-the-badge&logo=telegram"></a>

## ABOUT TOOL :
**Title: "The Ultimate Tool for Tracking Social Media Accounts Linked to an Email Address: Discover Everything in One Place"**

**Tool Overview:**
We have an advanced tool that, upon entering an email address, quickly informs you which social media accounts are linked to that email. This tool helps you track social media presence, which is crucial for personal security and account management.

**Features:**
1. **Multi-Platform Search:** The tool searches across Facebook, Twitter, Instagram, LinkedIn, and other popular social media platforms.
2. **User-Friendly Interface:** A simple and intuitive interface that is easy for any user to navigate.
3. **Instant Results:** Provides immediate results after entering the email, allowing you to quickly check account status.

**Use Cases:**
- **Personal Security:** Track the security of your email and protect against unauthorized access.
- **Account Management:** Useful for identifying which platforms your email is registered on, helping you manage your accounts.
- **Digital Footprint Management:** Efficiently manage your online presence and deactivate unnecessary accounts.

**Conclusion:**
If you want to discover the social media accounts associated with your email address, this tool is an ideal solution. It helps you manage your digital footprint efficiently and enhances your online security.

- **This Tool is Only for Education Purpose.**


## AVAILABLE ON :

* Termux
* python3
  
## 🛠️ Installation

### With PyPI

```pip3 install holehe```

### With Github

```bash
git clone https://github.com/megadose/holehe.git
cd holehe/
python3 setup.py install
```

### With Docker

```bash
docker build . -t my-holehe-image
docker run my-holehe-image holehe test@gmail.com
```

## Quick Start

Holehe can be run from the CLI and rapidly embedded within existing python applications.
### 📚 CLI Example

```bash
holehe test@gmail.com
```
### 📈 Python Example

```python
import trio
import httpx

from holehe.modules.social_media.snapchat import snapchat


async def main():
    email = "test@gmail.com"
    out = []
    client = httpx.AsyncClient()

    await snapchat(email, client, out)

    print(out)
    await client.aclose()

trio.run(main)
```
![](https://github.com/megadose/gif-demo/raw/master/holehe-demo.gif)
## Module Output

For each module, data is returned in a standard dictionary with the following json-equivalent format :
```json
{
  "name": "example",
  "rateLimit": false,
  "exists": true,
  "emailrecovery": "ex****e@gmail.com",
  "phoneNumber": "0*******78",
  "others": null
}
```

- rateLitmit : Lets you know if you've been rate-limited.
- exists : If an account exists for the email on that service.
- emailrecovery : Sometimes partially obfuscated recovery emails are returned.
- phoneNumber : Sometimes partially obfuscated recovery phone numbers are returned.
- others : Any extra info.


Rate limit? Change your IP.

## Modules
| Name                | Domain                                 | Method            | Frequent Rate Limit |
| ------------------- | -------------------------------------- | ----------------- | ------------------- |
| aboutme             | about.me                               | register          | ✘               |
| adobe               | adobe.com                              | password recovery | ✘               |
| amazon              | amazon.com                             | login             | ✘               |
| amocrm              | amocrm.com                             | register          | ✘               |
| anydo               | any.do                                 | login             | ✔               |
| archive             | archive.org                            | register          | ✘               |
| armurerieauxerre    | armurerie-auxerre.com                  | register          | ✘               |
| atlassian           | atlassian.com                          | register          | ✘               |
| axonaut             | axonaut.com                            | register          | ✘               |
| babeshows           | babeshows.co.uk                        | register          | ✘               |
| badeggsonline       | badeggsonline.com                      | register          | ✘               |
| biosmods            | bios-mods.com                          | register          | ✘               |
| biotechnologyforums | biotechnologyforums.com                | register          | ✘               |
| bitmoji             | bitmoji.com                            | login             | ✘               |
| blablacar           | blablacar.com                          | register          | ✔               |
| blackworldforum     | blackworldforum.com                    | register          | ✔               |
| blip                | blip.fm                                | register          | ✔               |
| blitzortung         | forum.blitzortung.org                  | register          | ✘               |
| bluegrassrivals     | bluegrassrivals.com                    | register          | ✘               |
| bodybuilding        | bodybuilding.com                       | register          | ✘               |
| buymeacoffee        | buymeacoffee.com                       | register          | ✔               |
| cambridgemt         | discussion.cambridge-mt.com            | register          | ✘               |
| caringbridge        | caringbridge.org                       | register          | ✘               |
| chinaphonearena     | chinaphonearena.com                    | register          | ✘               |
| clashfarmer         | clashfarmer.com                        | register          | ✔               |
| codecademy          | codecademy.com                         | register          | ✔               |
| codeigniter         | forum.codeigniter.com                  | register          | ✘               |
| codepen             | codepen.io                             | register          | ✘               |
| coroflot            | coroflot.com                           | register          | ✘               |
| cpaelites           | cpaelites.com                          | register          | ✘               |
| cpahero             | cpahero.com                            | register          | ✘               |
| cracked_to          | cracked.to                             | register          | ✔               |
| crevado             | crevado.com                            | register          | ✔               |
| deliveroo           | deliveroo.com                          | register          | ✔               |
| demonforums         | demonforums.net                        | register          | ✔               |
| devrant             | devrant.com                            | register          | ✘               |
| diigo               | diigo.com                              | register          | ✘               |
| discord             | discord.com                            | register          | ✘               |
| docker              | docker.com                             | register          | ✘               |
| dominosfr           | dominos.fr                             | register          | ✔               |
| ebay                | ebay.com                               | login             | ✔               |
| ello                | ello.co                                | register          | ✘               |
| envato              | envato.com                             | register          | ✘               |
| eventbrite          | eventbrite.com                         | login             | ✘               |
| evernote            | evernote.com                           | login             | ✘               |
| fanpop              | fanpop.com                             | register          | ✘               |
| firefox             | firefox.com                            | register          | ✘               |
| flickr              | flickr.com                             | login             | ✘               |
| freelancer          | freelancer.com                         | register          | ✘               |
| freiberg            | drachenhort.user.stunet.tu-freiberg.de | register          | ✘               |
| garmin              | garmin.com                             | register          | ✔               |
| github              | github.com                             | register          | ✘               |
| google              | google.com                             | register          | ✔               |
| gravatar            | gravatar.com                           | other             | ✘               |
| hubspot             | hubspot.com                            | login             | ✘               |
| imgur               | imgur.com                              | register          | ✔               |
| insightly           | insightly.com                          | login             | ✘               |
| instagram           | instagram.com                          | register          | ✔               |
| issuu               | issuu.com                              | register          | ✘               |
| koditv              | forum.kodi.tv                          | register          | ✘               |
| komoot              | komoot.com                             | register          | ✔               |
| laposte             | laposte.fr                             | register          | ✘               |
| lastfm              | last.fm                                | register          | ✘               |
| lastpass            | lastpass.com                           | register          | ✘               |
| mail_ru             | mail.ru                                | password recovery | ✘               |
| mybb                | community.mybb.com                     | register          | ✘               |
| myspace             | myspace.com                            | register          | ✘               |
| nattyornot          | nattyornotforum.nattyornot.com         | register          | ✘               |
| naturabuy           | naturabuy.fr                           | register          | ✘               |
| ndemiccreations     | forum.ndemiccreations.com              | register          | ✘               |
| nextpvr             | forums.nextpvr.com                     | register          | ✘               |
| nike                | nike.com                               | register          | ✘               |
| nimble              | nimble.com                             | register          | ✘               |
| nocrm               | nocrm.io                               | register          | ✘               |
| nutshell            | nutshell.com                           | register          | ✘               |
| odnoklassniki       | ok.ru                                  | password recovery | ✘               |
| office365           | office365.com                          | other             | ✔               |
| onlinesequencer     | onlinesequencer.net                    | register          | ✘               |
| parler              | parler.com                             | login             | ✘               |
| patreon             | patreon.com                            | login             | ✔               |
| pinterest           | pinterest.com                          | register          | ✘               |
| pipedrive           | pipedrive.com                          | register          | ✘               |
| plurk               | plurk.com                              | register          | ✘               |
| pornhub             | pornhub.com                            | register          | ✘               |
| protonmail          | protonmail.ch                          | other             | ✘               |
| quora               | quora.com                              | register          | ✘               |
| rambler             | rambler.ru                             | register          | ✘               |
| redtube             | redtube.com                            | register          | ✘               |
| replit              | replit.com                             | register          | ✔               |
| rocketreach         | rocketreach.co                         | register          | ✘               |
| samsung             | samsung.com                            | register          | ✘               |
| seoclerks           | seoclerks.com                          | register          | ✘               |
| sevencups           | 7cups.com                              | register          | ✔               |
| smule               | smule.com                              | register          | ✔               |
| snapchat            | snapchat.com                           | login             | ✘               |
| soundcloud          | soundcloud.com                         | register          | ✘               |
| sporcle             | sporcle.com                            | register          | ✘               |
| spotify             | spotify.com                            | register          | ✔               |
| strava              | strava.com                             | register          | ✘               |
| taringa             | taringa.net                            | register          | ✔               |
| teamleader          | teamleader.com                         | register          | ✘               |
| teamtreehouse       | teamtreehouse.com                      | register          | ✘               |
| tellonym            | tellonym.me                            | register          | ✘               |
| thecardboard        | thecardboard.org                       | register          | ✘               |
| therianguide        | forums.therian-guide.com               | register          | ✘               |
| thevapingforum      | thevapingforum.com                     | register          | ✘               |
| tumblr              | tumblr.com                             | register          | ✘               |
| tunefind            | tunefind.com                           | register          | ✔               |
| twitter             | twitter.com                            | register          | ✘               |
| venmo               | venmo.com                              | register          | ✔               |
| vivino              | vivino.com                             | register          | ✘               |
| voxmedia            | voxmedia.com                           | register          | ✘               |
| vrbo                | vrbo.com                               | register          | ✘               |
| vsco                | vsco.co                                | register          | ✘               |
| wattpad             | wattpad.com                            | register          | ✔               |
| wordpress           | wordpress                              | login             | ✘               |
| xing                | xing.com                               | register          | ✘               |
| xnxx                | xnxx.com                               | register          | ✔               |
| xvideos             | xvideos.com                            | register          | ✘               |
| yahoo               | yahoo.com                              | login             | ✔               |
| zoho                | zoho.com                               | login             | ✔               |
