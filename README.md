

Kräver följande python paket

* flask
* python-twitter

Sqlite3 databasen har följande utseende:

    CREATE TABLE tweets (id INTEGER PRIMARY KEY NOT NULL, tweet TEXT, time DATETIME DEFAULT CURRENT_TIMESTAMP, tweet_id INTEGER, url TEXT, adress TEXT);

