# Day 4 Interview Questions:-
##Why do hackers prefer Linux?
  Answer:Because it is open-source, it allows security professionals to inspect the inner workings of the operating system and build custom environments tailored to specialized tasks.
##Difference between cp and mv?
  Answer:cp creates a duplicate copy of a file or directory while leaving the original intact, whereas mv transfers or renames the original file or directory, leaving nothing behind at the source location.
##Difference between grep and find?
  Answer:find searches for files and directories based on metadata like names, sizes, or dates, whereas grep searches for specific text patterns inside the contents of files.
##Explain Linux permissions.
  Answer:Linux permissions control who can view, modify, or execute files and directories on a system. This security model protects the operating system from unauthorized user actions or malicious software
##Difference bewtween chmod 777 and chmod 755?
  Answer:chmod 777 and chmod 755 is that chmod 777 allows absolutely anyone to modify or delete a file or directory, while chmod 755 restricts write/modify access exclusively to the owner.
##what does pwd do?
  Answer:The pwd command in Linux stands for "print working directory." It prints the absolute path of the directory you are currently in, starting all the way from the root directory (/).
##What is root user?
  Answer:The root user is the absolute administrator and most powerful account in Linux, possessing unrestricted access to all commands, files, services, and system settings. Also known as the superuser, this account bypasses all standard permission checks, giving it the authority to alter or delete any part of the operating system.
##Why curl is important and preffered in security testing?
  Answer:cURL (Client URL) is an indispensable command-line tool used for transferring data across networks. In security testing, it is preferred because it offers raw, unshielded communication with servers, eliminates GUI overhead, and allows testers to precisely manipulate every component of an HTTP request (like headers, methods, and payloads)
##Difference between curl and Postman?
  Answer:The primary difference between cURL and Postman is that cURL is a lightweight, text-based command-line tool used to quickly transfer data via the terminal, while Postman is a full-featured graphical application designed for complete API development, team collaboration, and automated testing. Developers typically reach for cURL when they need to fire off a quick, one-off request without leaving the terminal, and shift to Postman when they need to manage complex API environments or share workflows with a team.
##Why does penetration tester use the terminal instead of GUI tools?
  Answer:Penetration testers prefer the terminal over GUI tools because it enables automation, consumes fewer system resources, and provides fewer limitations. The terminal allows testers to access deep, hidden functionalities, script repetitive tasks, and easily pipe the output of one tool into another.
##Which command shows the current directory?
  Answer:pwd
##Which command finds a file?
  Answer:find
##Which command searchs text inside a file?
  Answer:grep
##Which command shows the current logged in user?
  Answer:whoami or who
##Difference between > and >> ?
  Answer:> overwrites an existing file's contents, while >> appends new data to the end of the file without erasing what is already there. Both are output redirection operators used in Linux shells to send the output of a command to a file instead of displaying it on the terminal screen
##Which command displays only first 10 lines of a file?
  Answer:head
##What is difference between cat and less?
  Answer:cat and less is how they handle file viewing: cat dumps an entire file's content directly into the terminal all at once, while less opens an interactive, scrollable interface to read the file page-by-page.
##Can normal user modify /etc/passwd? Why?
  Answer:No, a normal user cannot directly modify the /etc/passwd file.
  Allowing normal users direct write access to /etc/passwd would create an immediate, critical privilege escalation security hole. If a normal user could modify this file, they could easily change their own User ID (UID) to 0 (the root UID), instantly granting themselves full administrative control over the entire operating system.
