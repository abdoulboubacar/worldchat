#worldchat.io

A chat application that can translate messages simaltaneously around the world. Built on top of APIs with a <a href="http://unicorn.io">php REST HTTP client</a> and a little jQuery.

### Installation:

1) `git clone git@github.com:Mashape/worldchat.git`

2) `cd worldchat/server && composer install`

3 Ceate a <a href="http://firebase.com">firebase database</a> and signup for a mashape <a href="https://www.mashape.com/translated/mymemory-translation-memory">MyMemory Translation API</a> freemium account.

4) Configure `/server/config.php` with your firebase reference and mashape API key

5) Deploy!

### Troubleshooting

If your having problems, try <a href="http://xkcd.com/149/">using sudo</a>. 

Maybe you don't have <a href="http://getcomposer.org/doc/00-intro.md#system-requirements">composer installed</a>?

No bueno? Add an issue here on github or get in touch with <a href="http://twitter.com/montanaflynn">me on twitter</a> and I'll help you out.