// PyPhoto_Downloader | PyPhoto_Downloader.py
// Copyright (c) 2020, David Bitencourt (https://github.com/dabit-7)
// Licensed under the MIT (http://www.opensource.org.licenses/mit-license.php)

import os
import requests
from time import time
from datetime import datetime
from multiprocessing.pool import ThreadPool


data = datetime.now()
tstamp = data.strftime ('%Y-%m-%d_%H-%M-%S')

def url_response(url):

    path, url = url
    r = requests.get(url, stream = True)
    with open(path, 'wb') as f:
        for ch in r:
            f.write(ch)




urls = [
("PHOTO-" + tstamp + ".jpg","http://www..."),
]




start = time()

for x in urls:
    url_response (x)


print(f"Time to download: {time() - start}")
ThreadPool(9).imap_unordered(url_response, urls)

         
