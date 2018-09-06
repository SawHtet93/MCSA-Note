# MCSA-Note

Uninstall-WindowsFeature Server-GUI-Mgmt-Infra, Server-GUI-Shell -Restart

(GUI Install)
powershell
Install-WindowFeature Server-GUI-Mgmt-Infra, Server-GUI-Shell -Restart

-----------------------------------------------------

(Password Policy Change)
gpmc.msc > windows setting > Security Setting > 

(Acount Logout Policy)

gpmc.msc> Default Domain Policy > R.C > Edit> policy > Windows > Security Setting > Account logout Policity

(Login Hour )
Adds User and computer > Users > user on R.C > Properties> Account > logon Hours 

(Allow Logon Policity)
Tools > Group Policity Mgmt > Domain Controllerv>  Default Domain Control Policity >  Windows Settings> Security Setting > Local Policity > Allow logon Local > Add User or Group 

or

User > R.C > Allow logon Check box
 gpupdate /force

-----------------------------------------------------

(Security Level Policity) NTFS Permission
Security  tap> Advance > disable inheritance
add for apply user > apply ok

Inheritance = အေမြ႐ရွိ

-----------------------------------------------------
Configuring Local Profiles

Local Profile ဆို folder ေတ ြ  data ေတြမပါ

Romming Profile

SV မွာ
Profile.ေတြသိမ္းဖို့ folder တစ္ခုေဆာက္ > Share Every One 
လုပ္မဲ႕ User မွာ dsa.msc > RC > Profile tap > pase share path ေနာက္မွာ user name
eg :\\SV1\Share\User1

Client
မွာ checkဖုိ့တြက္control panel > System ထဲက User Profile

-----------------------------------------------------

Transfer Operations Master

cmd 
net account ( Check domain)
ntdsutil 
roles
connections
connect to server add
Transfer infrastructure master
Transfer naming master
Transfer pdc master
Transfer RID master
Transfer schema master

Pramiary to Back

-----------------------------------------------------








