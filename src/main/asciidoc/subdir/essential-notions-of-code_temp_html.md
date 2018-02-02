= CODAPPS: Essential notions of code
Clément Levallois <levallois@em-lyon.com>
2018-01-22

last modified: {docdate}

:icons!:
:source-highlighter: rouge
:iconsfont: font-awesome
:revnumber: 1.0
:example-caption!:
:sourcedir: ../../../../main/java


:title-logo-image: EMLyon_logo_corp.png[width="242" align="center"]

image::EMLyon_logo_corp.png[width="242" align="center"]
{nbsp} +

//ST: 'Escape' or 'o' to see all sides, F11 for full screen, 's' for speaker notes

== 1. The interactive tool we are using to learn the basics of code
//ST: 1. The interactive  we are using to learn the basics of code

//ST: !
It is useful to learn about coding by reading a lesson like this one, but it is more efficient if you can *practice while you read*.

Indeed, a key competency in coding is to learn the simple discipline of writing text carefully:

//ST: !
- not forgetting a `;` at the end of the line
- not forgetting to put a capitalized letter when it is necessary
- learning how to spot opening accolades `{` and closing accolades `}`
- not confusing when to use commas `,` and semi-colons `;`

//ST: !
It is all very trivial, right? And yet this is what needs the most practice, at the start.

//ST: !
So in this lesson, you will see plenty of interactive screens like this one:

++++
<iframe height="600px" width="100%" src="https://repl.it/repls/DifficultRashAmazontreeboa?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
++++

//ST: !
You can write your code directly on it in this lesson, and and "launch it" to see the results. Here is an explanation of how this works:

//ST: !
image::How-does-the-interactive-tool-work.png[align="Center" title="How does the interactive tool work"]
{nbsp} +

//ST: !
Last note before we start: this lesson is on the [underline]#essentials# of coding, so we go fast and discuss just the most important notions of coding.

If you are interested in (much) longer, more thorough approaches, you can have a look at these two interactive courses:

//ST: !
- https://books.trinket.io/thinkjava/index.html["Think Java"] by Tinklet (Java is the same programmming language as the one we use here)
- https://books.trinket.io/pfe/index.html["Python for Everybody"] also by Tinklet (Python is the most popular programming language for data science)

== 1. Variables
//ST: 1. Variables

//ST: !
If we compare coding to cooking, you could say that `variables` are the ingredients of the recipe.

If we develop a gaming app, we need to have characters and animate them, show their names on screen, record scores...

-> variables are a way to create, define and store all these things we need in our program.

//ST: !
[TIP]
====
You can create all the kinds of variables you want, but to help you, a number of them are already predefined because they are so common:
====

//ST: !
A variable is created and defined this way:

//ST: !
[[anchor-1]]
.Creating a variable
[source,java]
----
String playerName = "Bernard B";
----

What does all this mean? Let's decompose each term:

//ST: !
- `String`: The capital *S* is mandatory. It means this variable specializes in storing *text*. This is the *type* of the variable.
- `player`: this is the name I chose for the variable, it could have been anything else. By convention it always starts *without* a capitalized letter and it has *no space* in it.
- `=`: the right of the equal sign will be the value of the variable.
- `"Bernard B"`: this is the value I store in the variable `player`. *Textual values should be put between quotes " "*.
- `;`: this step of code is finished a the end of the line. The `;` shows this end and *is mandatory* (if you don't put it, the program tries to read the next line as the direct continuation of this one, and it gets confused).

//ST: !
[[anchor-1]]
.Creating a variable
[source,java]
----
String playerName = "Bernard B";
----

So this single line of code creates a variable called playerName, and I immediately give it a value: "Bernard B".

//ST: !
This will be handy when we need to show the player's name on the screen of the app: we will just use the variable `player`, and what ever value in it (the player's name) will be shown.

//ST: !
Try to create a variable by yourself:

[WARNING]
====
You need to put the name of your variable in the line "System.out.println..." if you want to see the result on screen, just like below
====

//ST: !
++++
<iframe height="600px" width="100%" src="https://repl.it/@seinecle/Variable-1?lite=true" scrolling="no" frameborder="no" allowtransparency="true" allowfullscreen="true" sandbox="allow-forms allow-pointer-lock allow-popups allow-same-origin allow-scripts allow-modals"></iframe>
++++



== The end
//ST: The end

//ST: !
Questions? Want to open a discussion on this lesson? Visit the forum https://github.com/seinecle/codapps/issues[here] (need a free Github account).

//ST: !
Find references for this lesson, and other lessons, https://seinecle.github.io/codapps/[here].

//ST: !
Licence: Creative Commons, https://creativecommons.org/licenses/by/4.0/legalcode[Attribution 4.0 International] (CC BY 4.0).
You are free to:

- copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material

=> for any purpose, even commercially.

//ST: !
image:round_portrait_mini_150.png[align="center", role="right"]
This course is designed by Clement Levallois.

Discover my other courses in data / tech for business: http://www.clementlevallois.net

Or get in touch via Twitter: https://www.twitter.com/seinecle[@seinecle]
pass:[    <!-- Start of StatCounter Code for Default Guide -->
    <script type="text/javascript">
        var sc_project = 11592657;
        var sc_invisible = 1;
        var sc_security = "5154b75d";
        var scJsHost = (("https:" == document.location.protocol) ?
            "https://secure." : "http://www.");
        document.write("<sc" + "ript type='text/javascript' src='" +
            scJsHost +
            "statcounter.com/counter/counter.js'></" + "script>");
    </script>
    <noscript><div class="statcounter"><a title="site stats"
    href="http://statcounter.com/" target="_blank"><img
    class="statcounter"
    src="//c.statcounter.com/11592657/0/5154b75d/1/" alt="site
    stats"></a></div></noscript>
    <!-- End of StatCounter Code for Default Guide -->]