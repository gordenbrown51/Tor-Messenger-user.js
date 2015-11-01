# Tor-Messenger-user.js

This will harden the Tor Messenger user.js for maximum possible security.


This is original released by CHEF-KOCH 2015 under the [GNU GENERAL PUBLIC LICENSE v2](https://github.com/CHEF-KOCH/Tor-Messenger-user.js/blob/master/LICENSE) license. 


Please note that the entire messenger is currently in beta, so everything can be changed with newer versions!


How can I access the about:config stuff under Tor Messenger?
-------------------

* Options - Advanced - General - 'Config Editor'
* The prefs.js is located under: ~\Tor Messenger\Messenger\TorMessenger\Data\Browser\profile.default\


What is the benefit using your stuff?
-------------------

* Well, if you need to ask you never cared about security in Mozilla products (until now), but I'm fine you decided to ask and the answer is very simple. 
* You can before the Messenger first time starts, get the maximum security without playing with any option within the Messenger. So you don't waste your time with the options pages. Of course some options are also hidden, so another benefit is that you have them 'secured'.


Some security things are enabled, why?
-------------------

* Because I don't disable everything due the fact that to disable it have no real benefit except theoretically attacks. If you found real pages with attacks, report it to me and I will posible change that, but as long no one found any page / link which compromise the securty aspect within Tor Messenger I will not change that. I really don't a da** about theoretically pages/attacks which shows xyz possible attack which mostly requires Javascript and such enabled. I prefer real world examples. Theoretically all is possible but so what?!
* E.g. safe-browsing/disk cache/ssl reporting/javascript is enabled for several reasons. Since we use OTR by default it makes no sense to e.g. touch disk cache. The other option are enabled for security reasons or to not lower the 'fun' since it might break other things, a Messenger isn't a browser, please keep that in mind!



Some options are removed will you add it?
-------------------

* No, my philosophy is to always use the latest software and use it with latest security options (if possible), so I won't look behind and add xyz config because someone want to use an outdated version. No, sorry at this point, your own your own if do so. 



References
-------------------

* [Tor Messenger Beta: Chat over Tor, Easily (blog.torproject.org)](https://blog.torproject.org/blog/tor-messenger-beta-chat-over-tor-easily)
* [Official Tor Messenger Downloads](https://dist.torproject.org/tormessenger/)