# NotThatBig-Font
 I designed some letter to be used in terminal scenarios where you need something a little bigger but don't want something as big as something like using most figlet fonts. I tried my best to keep them legible, (mostly) monospace, and only using the box drawing unicode symbols. I would love if these got integrated into something like the glow markdown renderer or bk / epr for rendering header text instead of just some bold text. It should look fine in any font but I designed it using Fira Code Mono so that's where it probably looks best.

# Comparison to Figlet Fonts of Similar Size

Heres a listing of all the font in Figlet that I found using this command.

```
foreach ($font in $(figlet -l)) {
    $out = figlet -f $font AaBbCcDdEeFf
    # Convert output to array of lines
    $lines = $out -split "`n"
    # Filter: only show if 3 lines or fewer
    if ($lines.Count -le 3) {
        Write-Host "`n$font:`n"
        $lines | ForEach-Object { $_ }
        Write-Host "`n"
    }
}
```
## >= 3 High fonts
```
/\ /\ ]3 ]3 ( ( |) |) [- [- /= /= 
                                  
/-\/-\|3|3((|)|)33FF
/-\/-\|3|3((|)|)[-[-|=|=
 _     _     __    _     __    __  _
|_| _ |_)|_ /   _ | \ _||_  _ |_ _|_
| |(_||_)|_)\__(_ |_/(_||__(/_|   | 
01000001 01100001 01000010 01100010 01000011 01100011 01000100 01100100 01000101 01100101 01000110 01100110 
  __     __    ___   ___   __    __    ___   ___   ____  ____  ____  ____ 
 / /\   / /\  | |_) | |_) / /`  / /`  | | \ | | \ | |_  | |_  | |_  | |_  
/_/--\ /_/--\ |_|_) |_|_) \_\_, \_\_, |_|_/ |_|_/ |_|__ |_|__ |_|   |_|   
╔═╗┌─┐╔╗ ┌┐ ╔═╗┌─┐╔╦╗┌┬┐╔═╗┌─┐╔═╗┌─┐
╠═╣├─┤╠╩╗├┴┐║  │   ║║ ││║╣ ├┤ ╠╣ ├┤ 
╩ ╩┴ ┴╚═╝└─┘╚═╝└─┘═╩╝─┴┘╚═╝└─┘╚  └  
 ____ ____ ___  ___  ____ ____ ___  ___  ____ ____ ____ ____
 |--| |--| |==] |==] |___ |___ |__> |__> |=== |=== |--- |---
65 97 66 98 67 99 68 100 69 101 70 102 
 +-+-+-+-+-+-+-+-+-+-+-+-+
 |A|a|B|b|C|c|D|d|E|e|F|f|
 +-+-+-+-+-+-+-+-+-+-+-+-+
 ___   ___  ____  ____   ____  ____ _____ _____ _____ _____ _____ _____ 
||=|| ||=|| ||=)  ||=)  ((    ((    ||  ) ||  ) ||==  ||==  ||==  ||==  
|| || || || ||_)) ||_))  \\__  \\__ ||_// ||_// ||___ ||___ ||    ||    
 _   _   _  _   __  __ 
//\a[|}b((c[|)d[|-e[|-f
                `-     
41 61 42 62 43 63 44 64 45 65 46 66 
   ____    ____  _____ _____  ____  ____  ____  ____  ____  ____  ____  ____ 
  / () \  / () \ | () )| () )/ (__`/ (__`| _) \| _) \| ===|| ===|| ===|| ===|
 /__/\__\/__/\__\|_()_)|_()_)\____)\____)|____/|____/|____||____||__|  |__|  
 /1  /1  /�1  /�1 /` /`  /`.  /`.  /.�  /.�  /��  /�� 
/�/ /�/ /.I  /.I  L- L- /.-� /.-� /..  /..  /�   /�   
.^. .^. I�D I�D ,�� ,�� I`. I`. I.` I.` I�� I�� 
I^I I^I I.D I.D `.. `.. I./ I./ I.. I.. I�  I�  
         |  |         |  |  _  _ |\ |\
 //| //| |/ |/ |_ |_ \| \| |/ |/ |  | 
                                      
AaBbCcDdEeFf
.- .- -... -... -.-. -.-. -.. -.. . . ..-. ..-. 
.- .- -... -... -.-. -.-. -.. -.. . . ..-. ..-. 
101 141 102 142 103 143 104 144 105 145 106 146 
░█▀█░█▀█░█▀▄░█▀▄░█▀▀░█▀▀░█▀▄░█▀▄░█▀▀░█▀▀░█▀▀░█▀▀
░█▀█░█▀█░█▀▄░█▀▄░█░░░█░░░█░█░█░█░█▀▀░█▀▀░█▀▀░█▀▀
░▀░▀░▀░▀░▀▀░░▀▀░░▀▀▀░▀▀▀░▀▀░░▀▀░░▀▀▀░▀▀▀░▀░░░▀░░
  ^    ^    ^    ^    ^    ^    ^    ^    ^    ^    ^    ^  
 /A\  /a\  /B\  /b\  /C\  /c\  /D\  /d\  /E\  /e\  /F\  /f\ 
<___><___><___><___><___><___><___><___><___><___><___><___>
NnOoPpQqRrSs
____  _    ___   __  ___   _   ___   _   ___   _  ____ __  
__|_) _|) (_|_) (_) (   ) | | (   ) (_)_| ' | (|)   ' | |) 
                               `-'                         
 /|  |)| /` _|\ |[~ _ [~[`
/-|(||)|)\,(_|/(|[_(/_| | 
                          
.', .',  _ _   _ _           _ _   _ _  ,' ,' |_  |_  
 |   |  |_)_) |_)_) (_| (_| | ) ) | ) )  |  | |_) |_) 
        |     |       |   | |     |                   
AaBbCcDdEeFf
 /\  _ |~)|_ /~` _|~\ _|(~ _ |~ |`
/~~\(_||_)|_)\_,(_|_/(_|(_(/_|~~|~
                                  
|~| _ |~)|_ |~ _|~\ _|[~ _|~ |~
|~|(_||_)|_)|_(_|_/(_|[_}_|~~|~
//-\ //-\ ][3 ][3 << << ][_) ][_) ]E ]E ][= ][=
```
