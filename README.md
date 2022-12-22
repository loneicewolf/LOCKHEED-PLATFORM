# LOCKHEED-PLATFORM
**NOTE**:   Not to be confused with the Aerospace-Defense Company [Lockheedmartin](https://en.wikipedia.org/wiki/Lockheed_Martin)


#### Not done. I Will focus on some other projects before moving onto this project. Please consider this project as (in slow-dev)

to read it anyway, click the arrow(expansion)

![image](https://user-images.githubusercontent.com/68499986/209193586-0f6397eb-e74f-4cb7-a356-e6e30d33b19a.png)


<details>
<summary> under_construction </summary>

The LOCKHEED-PLATFORM -better known as 
LP - is a  metasploit and beef-xss -like "platform",
designed for advanced Cyber Assessments.

## Currently done projects that will be included in the LOCKHEED PLATFORM:


## Kernel Section
`(single)Project about Executing system-commands at Kernel-Level (so-called; Kernel-SysCall)`
- [x] https://github.com/loneicewolf/EXEC_LKM


## projects that is not Yet done (but will in the not-so-distant future)

## Hook Section
`Projects about Kernel Hooking calls/and so on;
As to for example hide:
  any type of data(file,directory,proc,dev) and even contents of the data (so, text,raw binaries, ..)
Or another example modify:
A random number generator (which will be more advanced than just using a LD_PRELOAD or just a 'simple' user-mode app-specific hook)
(remember; this is all kernel mode)`

- File
- Folder
- (note the above will *most probably* be built inside 1 whole 'plugin' but will include 2 diff. files for those interested
- Proc and Dev 'files'
- and Networking.

`it is important to note that this will just not only "hook" and that is the end of the conversation; it will "hook" and then "perform" some other action. Say if a file exist at a certain time; has < these certain attribs and contents in it; at (say) this x.y.z location; the hook will call function X (in the LKM_EXEC project) that will - in turn - do something.`
so, a practical more concrete example of this wold be 
a rootkit that shuts down itself every time a ps/lsmod/.. command is run; and is started up again when there are no commands(such as those) running.
(note; a kernelmode rootkit is probably not detected trough ps or lsmod; but in some cases the time it takes for e.g the `ls` command one **can** (and in some cases; it has been proven to even **be** detectable - even if not visible in lsmod))

```
  I have (and will continue doing to) take into account all of the above "things".
  just hiding some files with a certain "tag"(like a prefix) and call that a rootkit; yeah - okay; but if you are serious you would consider some tests and checks (not only hide the file if the file is x.y.z)
  
  I mean for example security vulns in a kernel rootkit doesn't seem like a glorious idea really..
```

---

- https://github.com/loneicewolf/DUQU
- https://github.com/loneicewolf/Gauss-Src
- https://github.com/loneicewolf/gauss-encryptedpayload_decoded
- https://github.com/loneicewolf/Stuxnet-Source
- https://github.com/loneicewolf/flame-sourcecode
- https://github.com/loneicewolf/fanny.bmp
- https://github.com/loneicewolf/Agent.btz
- https://github.com/loneicewolf/Cryptography
-----

## Section 2



## Section 3


## Section 4


## FAQ

(Q) Why the name?
- (A) It was just a name that *fit* the project.

(Q) When will this be *updated* or similar?
- (A) When I have a **bit** (*phun intended*) more time on my hands. Right now it's quite a lot.


---
Will, as usual of course reply to Discord, Mails, Pull and Issue requests.


</details>
