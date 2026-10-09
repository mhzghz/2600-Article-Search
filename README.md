# 2600-Article-Search

Simple Perl CGI to search (grep) for text strings within issues of [_2600 Magazine_](http://www.2600.com).

Includes OCR'd text data for most articles/issues. This is still kinda experimental and may give weird results if the OCR didn't turn out right.

Now includes a search of text transcripts of [*Off The Hook*](http://www.gbppr.net/2600/oth) and the [Hackers on Planet Earth](http://www.gbppr.net/2600/hope) conferences made using [WhisperAI](http://www.whisperai.com).

Requires aha (https://github.com/theZiz/aha) for converting ANSI color codes into HTML.

     $ sudo apt install aha

This is still kinda experimental and may give weird results if the OCR/WhisperAI didn't turn out right.

The HOPE videos are arranged by YouTube ID, as that's easier to work with via command line utils. (any starting '-' are removed).

Acronyms and computer/hacker slang tend to mess up AI translations, so be creative with your search terms.

**_Try it out!_**

http://gbppr.ddns.net/2600.main.cgi
