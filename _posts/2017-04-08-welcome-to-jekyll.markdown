---
layout: post
title:  "Leaving the Mac for desktop linux"
date:   2017-04-08 19:49:57 +0200
categories: linux, laptop, my-linux-migration
---

Back in 2002 I was studying computing science. My parents supported
me, but I got most of my money from IT related jobs that I did
between lessons. It was also the year that I bought my first Mac.
It was a Powerbook G4 1Ghz for EUR 3500. I had worked my ass off
to afford it. It was a great machine (truly portable, solid battery
life, great ui, unix). I now had daily arguments with my fellows
about the performance advantage of my 1ghz g4 vs their 2ghz intel
machines. Apart from that life was great and I used that machine
_every_ day for the next five years. I'm
on mac number seven[^my-machines] right now. Most machines were
paid for by my employers. None of the machines ever broke
[^replaced-parts]. Yet, after 15 years of Apple and OS X I'm gonna
try to leave the Mac behind.

Wait, what?

I'm gonna switch to linux. I'll tell you why: Some time ago apple
started installing batteries that were not customer replaceable
anymore. I looked it up on ifixit and I knew I could still do it.
No biggie for me. Then apple started glueing batteries to the body
and I knew that I wouldn't buy such a machine for myself. Now
they've started putting those awful touchbars into their machines
and I really hate haptics of those. Good luck on finding drivers
for those and their more recent webcams by the way.
Then, with el capitain they even started taking away root access.
And that's about all I am willing to take.

I'm giving desktop linux a try. My test-machine is a pre owned
lenovo x201. I upgraded it to 8GB RAM, 256GB SSD and replaced the
battery. Total cost was around EUR 600. Which is still a lot of
money for many people, but it's about as cheap as it gets for a
machine that I am willing to use. It's also quite a bargain compared
to new apple or lenovo hardware. Once my migration is complete I'll
probably replace the x201 with a x1 carbon or an x260 or the likes.

Now that I've got a machine I'm gonne need to migrate quite a
bit of software. I'm gonna do it step by stop, post by post. This
is my TODO list. I'm gonna update it with thinks that I missed an
links posts about those.

| Function | macos | linux |
|---------|-------|-------|
| OS | macos | linux |
| Filesystem encryption | Filevault | DeviceMapper |
| Backup   | TimeMachine | Snapper + Restic |
| Day/Night color manager | Flux | redshift gtk |
| Password Manager | 1Password | Enpass |
| Calendar | Aplle Calendar | Thunderbird |
| eMail Client | Apple Mail | Thunderbird |
| Picture Organizer | Adobe Lightroom | Darktable |
| Image manipulation | Photoshop Elements | Gimp |
| Office software | Libre Office | LibreOffice |
| Git Gui | gitx | gitg |


## Footnotes

[^my-machines]: Powerbook G4 1Ghz aka TiBook, A white Macbook, An aluminum Macbook, A Retina Macbook Pro 15 inch, A Macbook Air 13 inch, A Macbook Pro 13 inch, A Macbook Pro Retina 13 inch.
[^replaced-parts]: I replaced the fan on the TiBook when it became noisy and I replaced the batteries on the TiBook and the white macbook.
