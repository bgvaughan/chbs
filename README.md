chbs
====

NAME
    chbs - correct horse battery staple

SYNOPSIS
    chbs [--help|--man] [--num #] [--min #] [--max #] [--dict|--file {path}]

OPTIONS
     Parameters for words
            --num [#]       Number of words in the passphrase. (Default: 4)
            --min [#]       Minimum number of characters per word. (Default: 1)
            --max [#]       Maximum number of characters per word. (Default: 16)
 
     Word list source
            (Default: an internal list of about 4000 common English words.)
            --dict          The system spelling dictionary word list.
            --file [path]   Any arbitrary text file, mined for words.
 
     Help
            --help          Show the usage details, then exit.
            --man           Show the usage details and a description, then exit.

DESCRIPTION
    chbs generates passphrases comprised of randomly chosen words. A
    passphrase of four to six words is reasonably strong, and much easier to
    remember and to type than a sequence of random characters.

    Inspired by Randall Munroe's xkcd comic, http://xkcd.com/936/

AUTHOR
    Brian G. Vaughan <bgvaughan@gmail.com>

COPYING
    Copyright (C) 2013 Brian G. Vaughan

    This program comes with ABSOLUTELY NO WARRANTY. This is free software, and
    you are welcome to redistribute it under certain conditions. See the GNU
    General Public License for more details.
