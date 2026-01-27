# Alternatives

There's a lot of software I use that I'm kind of bummed about using. Here's where I list *why* I am bummed, and some potential alternatives as I explore them. If I have attempted to actually make any of these moves full-ish time, I'll document here. 


## Operating Systems

### Windows (Easy)
I maintain a Windows box for gaming purposes. It's a very modest machine, having been scraped together piecemeal when I could find deals on parts and when my personalia will allow it. I suppose I also could use it to test Windows builds of software I write, but that is increasingly unnecessary. I'm told there are Linux distros which are specially tuned around gaming stuff, and those might work well. 

Options:
* [Bazzite](https://bazzite.gg/)
* [Cachy](https://cachyos.org/)

I have not investigated either of these beyond their existence. 

### iOS (Hard)
I've used an iPhone since 2008, and am pretty deep into the ecosystem at this point. I know there are other mobile OSes, but the only really viable one is Android, and I feel like that would be a lateral move at best. 

### macOS (Very Hard)
I've used a Mac since... the early 90s? I'm pretty comfortable with it at this point. Even with Apple's software stagnation and questionable UI choices, I don't think going full-time Linux would be a choice at this point for a daily driver. But maybe if the gaming box shift works out, I could reconsider. A lot of software to give up, though...

Options:
* [Ubuntu](https://ubuntu.com/desktop) or [Debian](https://www.debian.org/), most likely

## Software

### Visual Studio Code (Medium)
It's perfectly fine, but they are increasingly pushing AI, performance seems to be degrading, and I'm not sure I want to be on the Microsoft bandwagon at this point. (See Office, below.) I've been using it as my main coding (and writing!) environment since 2017, but I'm not deep in the ecosystem. 

Options:
* [Zed](https://zed.dev/): nice, fast, big single killswitch to turn off AI; lack of support for some stuff I currently do, but plugin community seems like it's growing
* [Nova](https://nova.app/): very Mac-y, smooth, fun, Panic is good; costly, subscription-based, not much community around it, Panic seems to be losing interest
* [CodeEdit](https://www.codeedit.app/): very Mac-y, open source, good vision; not quite cooked yet, had some crashes when I was playing around with it
* Sublime, Vim, etc: I use Sublime as my lower-level text editor already; I am not smart enough for vim

### Microsoft Office (Medium)
Why must Copilot be in everything?! I'm not personally super dependent on this but often times need to collaborate on docs made by other people, so it may be a necessary evil for my line of work. 

Options:
* [Google Docs](https://docs.google.com): Google is a lateral move at best and I prefer native apps
* [LibreOffice](https://www.libreoffice.org/): haven't checked it out in a while, last time was pretty slow and chuggy, produces stuff that doesn't look as good
* [Pages](https://www.apple.com/in/pages/)/[Numbers](https://www.apple.com/in/numbers/)/[Keynote](https://www.apple.com/in/keynote/): I already use Keynote for most presentations, but the others seem less good overall; upside is they are free with macOS

### Mail.app
Because of my various life of academia, work, religious organizations, and personal mail, at any time I have 5-6 email accounts I regularly use. I like keeping them separate, but I also like accessing them through a shared interface --- preferably a native one. For about ten years I've settled on the built-in Apple Mail.app as it hits all those points pretty well. But it's never been great for search and seems to be languishing. It is also locked to macOS, which limits flexibility for OS movements, as mentioned above. 

Options:
* [Thunderbird](https://www.thunderbird.net): has recently allegedly gotten the ability to handle Exchange accounts, so likely worth a look

### Xcode
I've basically excised this from my toolkit already, using command line and VSCode. I think it needs to at least stick around on the drive because other things use its command line tools for building. I don't especially want another big IDE, though --- a fancy text editor is sufficient. 

### asdf
I *love* the idea of a single piece of software handling installation, upgrades, version management, etc. for a wide variety of my software tools. This is a great idea for a thing to exist. Unfortunately asdf is really poorly executed --- plugins behave inconsistently, things break, installed packages don't always make it through upgrades, etc. 

Options:
* [mise](https://mise.jdx.dev/): written in Rust; one of their selling points is that they are compatible with asdf plugins, which does not fill me with confidence! my problems with asdf are the plugin inconsistencies, not the lack of rust. 
* [vfox](https://vfox.dev/): only learned about this while searching to compile this list; definitely worth a deeper investigation

### Base
When I'm monkeying around with a complicated SQLite project it's handy to have a GUI explorer of database files. I kind of feel bad picking on [Base](https://menial.co.uk/base/), because it's actually pretty good at what it does! But my purchased version 2 sat unupdated forever, and the very recent (as of this writing) version 3 is a whole new purchase which makes me look around. 

Options:
* [SQLiteStudio](https://sqlitestudio.pl/): perfectly cromulent; FOSS; just looks pretty clunky on macOS
* [SQLiteBrowser](https://sqlitebrowser.org/): kind of the same story 
* just writing my own stupid set of queries when I need them: look.

### Pixelmator Pro
I purchased this a while back as a replacement for Photoshop when Adobe went over to subscription prices. It's pretty good and I like it! But then Apple bought it and rolled it into a subscription. 🙃 Unclear if my exising purchase will continue to work into the future. I also use heavy-duty image editing only sporadically.

Options:
* [Photoshop](https://www.adobe.com/products/photoshop.html): LOL no
* [Acorn](https://flyingmeat.com/acorn/): I'm kinda worried that it's too "scrappy" which means it might die? Hard to put my finger on what my issue is here... I've heard good things overall though. Mac-only. 
* [GIMP](https://www.gimp.org/): LOL no

### Affinity Designer
Around the same time I was moving away from Photoshop, for the same reasons I was looking for an Illustrator replacement. I never quite liked this as much as I did Illustrator, which was like an extension of my hands for _years_. Affinity Designer also never handled RTL text (like Hebrew and Arabic) and were super dismissive whenever this was brought up to them. Booooo. In any case, it's now been bought by Canva and rolled into [the Affinity super-app](https://www.affinity.studio/), which is freemium and pushing AI subscriptions. Still doesn't do RTL text. 

Options:
* [Inkscape](https://inkscape.org/): better than GIMP is for raster images, but not by much; FOSS, which is good, but slow and clunky UI
* [Graphite](https://graphite.art/): only in alpha, but looks interesting; maybe getting more into animation and procedural generation stuff, but worth keeping an eye on; FOSS
* [GodSVG](https://www.godsvg.com/): only in alpha, might be more focused on simpler icon-like designs, but that's also ok; FOSS

### Firefox
I've been a Firefox kid since it was still called Phoenix. When everyone else was falling for Chrome, I avoided it because it had really bad accessibility options for my particular disability and were also pretty arrogant about it when people brought it up to them. Booooo! I'm told they got better but I remained pretty 😤 about it. I still like FF quite a bit, but always keep a skeptical eye on them because the Mozilla Foundation is pretty sketchy. They also seem to be getting hyped about AI. Blergh. There are lots of other usable browsers, but needs to be a pretty big value-add for me to consider changing my daily driver. 

Options:
* [Chrome](https://www.google.com/chrome/): have it on my computer for the sake of testing stuff, but still don't love it
* [Safari](https://www.apple.com/safari/): better than people think, but always feels a little weird to me. maybe just need to spend more time with it. not cross-platform, though, so would need non-Mac options. 
* [Orion](https://orionbrowser.com/): 👀; I like the look of this, especially if I go down the Kagi road in larger sense (below)

### Backblaze
Pretty good backup, but I keep reading that the company might go out of business? Also the few times I've needed to do a serious restore from them the process has been arduous and faulty. 

Options:
* [Arq](https://www.arqbackup.com/): seems like the best software option, but would need to be paired with storage option
  * storage options: ???

### Homebrew
Every power user's go-to for installing stuff on macOS. I like that it handles both command line and GUI software. Performance is good, service is reliable. Big cons: can only install latest version of most software (without major headaches), and they change policies so fast that sometimes stuff ends up getting excluded... Biggest con is the project leadership, which is very autocratic. 

Options:
* CLI:
  * [Nix](https://nixos.org/#): kind of solving a different problem but seems like some folks are using it for a Homebrew replacement? Need to research more
  * [MacPorts](https://www.macports.org/): the OG; a little less polished than Homebrew; don't know as much about project leadership or policies (might just be a grass-is-greener situation)
* GUI:
  * I don't think there are any?! Other than just going back to installing manually?! BOOOOOOO.

## Services

### Dreamhost
I've used them for 20+ years and they aren't bad; I like having shell access, lots of space. They do not appear to be profiteering jackasses. At the same time: my upload speeds have become terrible from anywhere in the world. There's some bug that locks me out of SSH access intermittently and they don't seem to care. Most of my web stuff is just static hosting, some PHP is nice to have but not needed. 

Options:
* (need to research this as my needs are simultaneously simple [don't need general app deployment, by and large] and complicated [would like to be able to actually SSH in, compile software, etc])

### Google
They got the AI brainworms, and even before then I was losing faith in them because the ads were infecting everything. 

Options:
* [Bing](https://www.bing.com): LOL no
* [DuckDuckGo](https://duckduckgo.com/): some people love it but I've always found their results to be kind of lousy (I think they're sourced from Bing anyway?)
* [Kagi](https://kagi.com/): this is very intriguing; I played with a free trial for a bit but was getting anxious by counting my searches; definitely seems to be high quality; do I want another subscription? 

### Gmail
See above w.r.t. Google. I also have to pay for extra storage and it's annoying to me. 

Options:
* [iCloud](https://www.icloud.com/): I already pay for the storage of my photos, so the email would be a drop in the bucket; have to trust Apple instead of Google but I'm pretty ok with that as lesser evil
* [Proton](https://proton.me/): I'm not that paranoid and not hyped about another subscription; have heard whispers that they're also not as private as they claim? 

### GitHub
They got the AI brainworms and their UX has seemed to be in pretty steep decline for a while. 

Options:
* [Gitea](https://about.gitea.com/): would probably host myself, but then need storage somewhere (could maybe leverage a hosting platform)
* [Codeberg](https://codeberg.org/): what Zig uses
* [Gitlab](https://about.gitlab.com/): what other folks use and are happy with, but also has some brainworms lately
