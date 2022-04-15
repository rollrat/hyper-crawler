# hyper-crawler

Crawler Generation using Cef

## v8

```sh
# build v8
git clone https://chromium.googlesource.com/chromium/tools/depot_tools.git
cd depot_tools
gclient sync
cd ..
fetch v8
cd v8
python src\build\util\lastchange.py -o LASTCHANGE
python tools/dev/gm.py x64.release

# make visual studio project
gn gen --ide=vs out/default
```

## ref 

http://www.egocube.pe.kr/lecture/content/html-javascript/202004210001
