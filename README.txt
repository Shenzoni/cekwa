Cara pakenya :

install bahan di termux :
apt update && apt upgrade && apt install git -y && apt install python -y
pip install requests

lanjut ke proses ambil api whatsapp :
Buka website : maytapi.com
Register lalu konek whatsapp kalian ( saran WhatsApp tumbal )
Salin code hasil konek disebelah " id: xxxxx ✔️active "  📋

ntar lu bakalan dapat link :
https://api.maytapi.com/api/xxxxx/xxxxx/screen?token=xxxx&time=

salin api untuk di isi ke bagian " PRODUCT_ID "
salin ID untuk bagian " PHONE_ID "
salin screen token untuk bagian " TOKEN "

lalu save file config.json
dan run script python oldcek.py
