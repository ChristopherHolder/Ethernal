
███████╗████████╗██╗  ██╗███████╗██████╗ ███╗   ██╗ █████╗ ██╗
██╔════╝╚══██╔══╝██║  ██║██╔════╝██╔══██╗████╗  ██║██╔══██╗██║ 
█████╗     ██║   ███████║█████╗  ██████╔╝██╔██╗ ██║███████║██║ 
██╔══╝     ██║   ██╔══██║██╔══╝  ██╔══██╗██║╚██╗██║██╔══██║██║ 
███████╗   ██║   ██║  ██║███████╗██║  ██║██║ ╚████║██║  ██║███████╗
╚══════╝   ╚═╝   ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝╚═╝  ╚═╝╚══════╝
                                                                   

                                                                    
A decentralized peer-to-peer lottery platform. It allows users to create and join lotteries that will randomly award all of the pot to a 		participant.


|----------------------------------------------------------------------------------------------------------------------------|
                                                              
`7MM"""Yb. `7MM"""YMM `7MMF'   `7MF'        `7MMF'`7MN.   `7MF'`7MM"""YMM   .g8""8q. 
  MM    `Yb. MM    `7   `MA     ,V            MM    MMN.    M    MM    `7 .dP'    `YM. 
  MM     `Mb MM   d      VM:   ,V             MM    M YMb   M    MM   d   dM'      `MM 
  MM      MM MMmmMM       MM.  M'             MM    M  `MN. M    MM""MM   MM        MM 
  MM     ,MP MM   Y  ,    `MM A'              MM    M   `MM.M    MM   Y   MM.      ,MP 
  MM    ,dP' MM     ,M     :MM;               MM    M     YMM    MM       `Mb.    ,dP' 
.JMMmmmdP' .JMMmmmmMMM      VF              .JMML..JML.    YM  .JMML.       `"bmmd"'
                                                                                
                                          
We are dividing our project into interaction with the client(Android) and the server.

For the latter we are currently running a Server(159.65.161.113) with Digital Ocean, who is currently running as a node in the Ethereum test Rinkeby Network.
This allows us to generate ethereum wallets and to create transactions. These transactions allow us to create smart contracts which are the fundamental core of our application. This is where we are implementing our solidity and web3py-based programs.

For android, we've been working with Android Studio to deliver an app that will allow our clients to interact with the contracts(Lotteries)
in the form of a feed(Android ListView).

|----------------------------------------------------------------------------------------------------------------------------|
 
  .g8"""bgd   .g8""8q. `7MMM.     ,MMF'`7MM"""Mq.`7MMF'`7MMF'      `7MMF'`7MN.   `7MF' .g8"""bgd 
.dP'     `M .dP'    `YM. MMMb    dPMM    MM   `MM. MM    MM          MM    MMN.    M .dP'     `M
dM'       ` dM'      `MM M YM   ,M MM    MM   ,M9  MM    MM          MM    M YMb   M dM'       `
MM          MM        MM M  Mb  M' MM    MMmmdM9   MM    MM          MM    M  `MN. M MM 
MM.         MM.      ,MP M  YM.P'  MM    MM        MM    MM      ,   MM    M   `MM.M MM.    `7MMF'
`Mb.     ,' `Mb.    ,dP' M  `YM'   MM    MM        MM    MM     ,M   MM    M     YMM `Mb.     MM
  `"bmmmd'    `"bmmd"' .JML. `'  .JMML..JMML.    .JMML..JMMmmmmMMM .JMML..JML.    YM   `"bmmmdPY 


This project relies heavily on server interaction, our server needs to be up and running in order for the application to run.
We assume that someone testing the application would probably not take the effort of creating and imitating the conditions of the
server in their system just to run the application. This means that the code that a tester would use to create the project is that of 
the front end and not the back-end. Again, this means that the group(us) will maintain the server up while testing is necessary.

Front end(If you have an android device):
----------
Inside the Brogrammers_Studio directory there is an 'app-debug.apk' which can be opened by an android device.(Easiest way)

Front end(If you do not have an android device):
----------
-The most practical way to create/open our Android application would be to import our files as a project with Android Studio and running it.
One could also manually activate the emulator from the command line as follows(Assuming ADB emulator is already installed, and after the project is built
with Android Studio):
-To run:
'emulator -avd avd_name' 

'adb install path/to/your_app.apk'


--------------------------------------------------------------------------------------------

EXECUTING THE CODE BELOW IS NOT NECESSARY, AS IT SHOULD ALREADY BE RUNNING IN THE SERVER!!!

--------------------------------------------------------------------------------------------
Back end:
---------
If the tester is interested in the back-end of the project, this code will also be provided in the git repository under the directory /gitjoin/BackendPy.
Which is inside the Brogrammers_Studio directory.Here, inside the scripts directory you can run the script startGeth.sh to make the server an etherum node, and afterwards you can run 'python app.py' .
to set up the interactions

|--------------------------------------------------------------------------------------------------------------------------------|





