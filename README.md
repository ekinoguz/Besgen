# Besgen

Live demo [here](http://ekinoguz.github.io/Besgen/).

## You should be interested in Besgen if:

* You don't like password manager tools, that save all your passwords somewhere.
* You use different passwords in every website.
* You keep forgetting and resetting your passwords all the time.

## What is Besgen?

Besgen is an extremely simple password generation and retrieval website. The idea is instead of remembering your complex password, you only need to remember basic keywords, and Besgen will help you convert these keywords into a complex password.

Besgen consists of 3 text fields, which are used to generate a random password using HMAC-SHA256. You can input whatever you want to each field, and Besgen will create the same password for you as long as you input the same text, in same order. If your browser allows, it will save the password to your clipboard automatically. Otherwise, your password will be visible on screen for 5 seconds. [Want to give it a try](http://ekinoguz.github.io/Besgen/)?

As an example, your keywords for Facebook can be (surfingisthebest, facebook, password), for Twitter (surfingisthebest, twitter, password), or for an answer to a security question at AAA (surfingisthebest, aaa, question_dog) (assuming your question is something about your dog). Each of these keywords will generate a complex password for you. Use your creativity to come up with your own scheme, and let the Besgen do the work.

![alt text](https://github.com/ekinoguz/Besgen/blob/master/screenshot.png?raw=true "Screenshot")

## License

This software is distributed under MIT License (see [LICENSE](LICENSE)
for more).
