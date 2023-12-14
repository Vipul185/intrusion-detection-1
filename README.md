## Features

 - Secrets are stored in an encrypted SQLite database with [SQLCipher](https://www.zetetic.net/sqlcipher/)
 - Within the database, each password and notes are encrypted with a unique salt using AES-256 encryption with [pycryptodome](http://legrandin.github.io/pycryptodome/)
 - Master key is hashed with a unique salt
 - Possibility to create an unlimited number of vaults
 - Clipboard cleared automatically
 - Automatic vault locking after inactivity
 - Password suggestions with [password-generator-py](https://github.com/gabfl/password-generator-py)
 - Import / Export in Json




