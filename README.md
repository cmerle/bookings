bookings
========

A bookings app for concerts at local venues


using PostgreSQL

after pip install pyscopg2

sudo ln -s /Library/PostgreSQL/9.2/lib/libssl.1.0.0.dylib /usr/lib
sudo ln -s /Library/PostgreSQL/9.2/lib/libcrypto.1.0.0.dylib /usr/lib

sudo ln -s /Applications/Postgres.app/Contents/MacOS/lib/libssl.1.0.0.dylib /usr/lib
sudo ln -s /Applications/Postgres.app/Contents/MacOS/lib/libcrypto.1.0.0.dylib /usr/lib

make sure to put localhost in HOST in settings.py

if using Postgress.App in MacOS X Mountain Lion and 
if syncdb fails with timezone error in settings.py

Time_Zone = 'US/Phoenix'
USE_TZ = False

