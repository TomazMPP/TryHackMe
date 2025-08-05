# 🔗 Windows PowerShell  
**📅 August 4, 2025 — Day 9**

> *Discover the "Power" in PowerShell and learn the basics.*

[🔗 Access the room on TryHackMe](https://tryhackme.com/room/windowspowershell)

![Windows PowerShell](https://raw.githubusercontent.com/TomazMPP/TryHackMe/refs/heads/main/Images/windows-powershell.png)


## Introduction</h2>
Ahoy there! If you’re here, you’ve either heard whispers of the marvels of PowerShell and want to discover more, or you’ve sailed over from the first room of the Command Line module—Windows Command Line. Either way, you’re about to embark on a journey to discover the marvels of this powerful shell, learning how to use it to uncover the secrets of any Windows system. Avast, then—on board!

### Learning Objectives</h3>
This is the second room in the Command Line module. It is an introductory room to PowerShell, the second—only historically—command-line utility built for the Windows operating system.

Learn what PowerShell is and its capabilities.
Understand the basic structure of PowerShell’s language.
Learn and run some basic PowerShell commands.
Understand PowerShell’s many applications in the cyber security industry.

---

## Questions

1. **What do we call the advanced approach used to develop PowerShell?**  <br />
`object-oriented`
2. **How would you retrieve a list of commands that start with the verb Remove? [for the sake of this question, avoid the use of quotes (" or ') in your answer]** <br />
`Get-Command -Name Remove*`
3. **What cmdlet has its traditional counterpart echo as an alias?** <br />
`Write-Output`
4. **What is the command to retrieve some example usage for the cmdlet New-LocalUser?** <br />
`Get-Help New-LocalUser -examples`
5. **What cmdlet can you use instead of the traditional Windows command `type`?** <br />
   `Get-Content`
6. **What PowerShell command would you use to display the content of the C:\Users directory?** <br />
   `Get-ChildItem -Path C:\Users`
7. **How many items are displayed by the command described in the previous question?** <br />
   `4`
8. **How would you retrieve the items in the current directory with size greater than 100?** <br />
   `Get-ChildItem | Where-Object -Property Length -gt 100`
9. **Other than your current user and the default "Administrator" account, what other user is enabled on the target machine?** <br />
   `p1r4t3`
10. **This lad has hidden his account among the others with no regard for our beloved captain! What is the motto he has so bluntly put as his account's description?** <br />
    `A merry life and a short one.`
11. **Now a small challenge to put it all together. This shady lad that we just found hidden among the local users has his own home folder in the C:\Users directory. Can you navigate the filesystem and find the hidden treasure inside this pirate's home?** <br />
    `THM{p34rlInAsh3ll}`
12. **In the previous task, you found a marvellous treasure carefully hidden in the target machine. What is the hash of the file that contains it?** <br />
    `71FC5EC11C2497A32F8F08E61399687D90ABE6E204D2964DF589543A613F3E08`
13. **What property retrieved by default by Get-NetTCPConnection contains information about the process that has started the connection?** <br />
    `OwningProcess`
14. **Some vital service has been tampered with. The shady lad modified its DisplayName to reflect his motto. Can you find the service name?** <br />
    `p1r4t3-s-compass`
15. **What is the syntax to execute the command Get-Service on a remote computer named RoyalFortune, assuming no credentials are needed?** <br />
    `Invoke-Command -ComputerName RoyalFortune -ScriptBlock { Get-Service }`


# Completed
![Windows PowerShell](https://raw.githubusercontent.com/TomazMPP/TryHackMe/refs/heads/main/Images/completed-windows-powershell.png)





|Date                       |      All Time|      All Time|       Monthly|       Monthly|Points    | Rooms     |
|:--------------------------|-------------:|-------------:|-------------:|-------------:|---------:| --------: |
|                           |        Global|        Brazil|        Global|        Brazil|          |           | 
| Aug &nbsp; 4, 2025        |         #370940 |           #6884 |         #10366|          #191 | ?  |       22 |

