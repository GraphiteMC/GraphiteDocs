# Choices Explained
Why are some configuration options set to what they are? Hopefully that is answered here, if not please contact a member of the team for further help.
___
## Global Configuration
* ### server-reloading
    * ##### disable-commands
        - **default**: true
        - **reason**: There has been issues around reloading the server whilst it is running.
* ### server-security
    * ##### disable-chat-reports
        - **default**: false
        - **reason**: Some servers may choose to actively allow players to report others.
    * ##### disable-root-running
        - **default**: false
        - **reason**: Running as root is unsafe and exposes the server to risks. Set it up properly!