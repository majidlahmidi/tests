# tests

time export HOME=/tmp && libreoffice --headless --nologo "-env:UserInstallation=file:///tmp/libO_Conversion__61d44309ea478" --accept="socket,port=13093;urp" --convert-to "xml" "/var/www/html/sites/default/files/private/editique/prevoyance_tableau_garantie.docx" --outdir "/var/www/html/sites/default/files/private" 2>&1
