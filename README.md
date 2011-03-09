## A hook based plugin system for Codeigniter 2.0+

Ever wanted to implement plugin functionality into your Codeigniter applications and have the ability to define hooks and add hooks to your plugins so users can control aspects of your application like Wordpress? That's where this library comes in. It's still heavily alpha, but should work. This is a complete from the ground up library that has been developed to give you the ability to define hooks including hooks with arguments.

## How do I use this?

I'm glad you asked. If you are familiar with Wordpress action and filter hooks, then you'll be able to learn how to use this. Follow the below steps to start extending baby.

* Download the files from this Github, then paste the folders into your root directory. Nothing should be overwritten (hopefully).
* Autoload the library "plugins"
* Start implementing your action points within your application using the run_action() function.
* In your plugins make sure to utilise the add_action() to register callbacks to your plugin functions when run_action is called.
* What next? Put the kettle on and kick the fuck back.

## Example application  
To see how the system works what better than an example application using a Markdown plugin I developed to show off the functionality of the library. It's located here: https://github.com/Vheissu/Ci-Plugin-System---Example-Plugin-and-Usage

## FAQ's

1. **My grandma says that she doesn't understand how to use this library, where is the documentation?**  
Documentation is coming shortly, it's in the process as we speak. Tell your grandma to shut up and stop running her mouth. Be warned however, it won't come in the form of Scrabble, so your grandma might find it hard to understand.

2. **I included it and I am getting lots of errors.**  
You did something wrong. The current code works as I've tested it drunk and sober and it worked! You're probably making the number one Codeeigniter newbie mistake using Codeigniter 1.7.2 which is super old and probably means you should quit programming and become a full time burger-flipperologist at McDonald's because you're not cut out for this kiddo (as they say in the business).

3. **But Wordpress lets me do x, why can't this library do that?**  
This is not Wordpress. If you have a request make it. If something is missing you think a hook based plugin library should have, tell me. Speaking of which, have you seen the Wordpress code base? Wow, what a mess.

4. **Where can I get some unicorn blood? (for testing purposes of course)**  
This is not a programming question, GTFO. Psst! send me an email, I can hook you up.

5. **I still don't get it. How do I use this damn library? AAAAAAAAAHHH**  
THERE IS NO DOCUMENTATION. IF YOU DO NOT UNDERSTAND AND SOMETHING DOESN'T WORK AND IT IS NOT A BUG, WAIT FOR DOCUMENTATION.