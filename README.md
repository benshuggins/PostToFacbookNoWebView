# PostToFacbookNoWebView

Within this program is a network controller that I wrote from scratch that allows you to post to Facebook without a webview.
Facebook has a lot of objections to this. I want to be clear the network controller in this iOS app exchanges tokens it's basically 
something I wrote when I was learning OAuth() and has the options for posting to twitter and Instagram which I can do but 
are not in this repo. Back to FB: I use older cocoapods and I force the program in the podfile to use older pods. After I 
attain the first user token I then exchange it through a series of urlsession.shared.datatask calls to get the desired page
tokens for the user. The trick is that I am only posting on the users business pages and am not revealing how to go further
at this point. This is impressive because the facebook developer documentation was written by a retarded chimpanzee.
Seriously go read it and try and post without a webview. You wont be able to. This network controller is a good example of 
my networking abiities and I enjoy getting through complex problems like this. As of June 27, 2019 this still works perfectly.
I am going to include Twitter and instagram posting natively soon as well. The firebase aspect of this was written by 
someone else I was working with and will be changed to cloudkit soon, as cloudkit is 5 times harder but 5 times better once 
you master it, Im going to include some CKShare with my cloudkit integration... Anyways just needed to get this up for myself.
I will be far more active on github in the next coming while. Thanks feel free to email me through Github. 
