# CryptSync
CryptSync is a small utility that synchronizes two folders while encrypting the contents in one folder. That means one of the two folders has all files unencrypted (the files you work with) and the other folder has all the files encrypted.

[![Build status](https://ci.appveyor.com/api/projects/status/w2hl21ow5i8qtqr0?svg=true)](https://ci.appveyor.com/project/stefankueng/cryptsync)
[![Build Status](https://tortoisesvn.visualstudio.com/tortoisesvnGitHub/_apis/build/status/CryptSync)](https://tortoisesvn.visualstudio.com/tortoisesvnGitHub/_build/latest?definitionId=4)


The synchronization works both ways: a change in one folder gets synchronized to the other folder. If a file is added or modified in the unencrypted folder, it gets encrypted. If a file is added or modified in the encrypted folder, it gets decrypted to the other folder.

This is best used together with cloud storage tools like OneDrive, DropBox or Google Drive.

Please see the [Homepage](https://tools.stefankueng.com/CryptSync.html) for more details.