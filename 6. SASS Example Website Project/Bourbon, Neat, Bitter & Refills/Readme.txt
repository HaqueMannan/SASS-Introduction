-------------------------------------------
Install & Use Bourbon
-------------------------------------------

To install Bourbon on your machine go into your terminal and enter the following command:

$ sudo gem install bourbon

This will install Bourbon from the gem file manager.


To install the Bourbon files into your project, in the terminal CD into your project folder and then run the command:

$ bourbon install

This will install the Bourbon files into your file directory and you are ready to use the Bourbon files in your projects.

Look at the Bourbon documentation on their website providing examples of using their mixins and variables within your project.
https://www.bourbon.io/docs/latest/

-------------------------------------------
Install & Use Neat
-------------------------------------------

To install Neat on your machine go into your terminal and enter the following command:

$ sudo gem install neat

This will install Neat from the gem file manager.

To install the Neat files into your project, in the terminal CD into your project folder and then run the command:

$ neat install

This will install the Neat files into your file directory and you are ready to use the Neat files in your projects.

Look at the Neat documentation on their website providing examples of using their mixins and variables within your project.
https://neat.bourbon.io/docs/latest/


-------------------------------------------
Install & Use Bitter
-------------------------------------------

To install Bitters on your machine go into your terminal and enter the following command:

$ sudo gem install bitters

This will install Bitters from the gem file manager.

To install the Bitters files into your project, in the terminal CD into your project folder and then run the command:

$ bitters install

This will install the Bitters files into your file directory and you are ready to use the Bitters files in your projects.

Look at the Bitters documentation on their website providing examples of using their mixins and variables within your project.
http://bitters.bourbon.io/

You may want to install a minified normalise SCSS file and import it before neat in your plugins-dir file before the importing biters. Also note that Bourbon should be imported before Bitters in your plugins-dir file.

-------------------------------------------
Install & Use Refill
-------------------------------------------

You do not need to install refills for it to work as it relies on Bourbon and Neat. However, Refills does not currently work with Neat as the @media mixin no longer exists in the latest version of Neat. You must use an older version within your project for it to work.

Look at the Refill documentation on their website providing examples of using their mixins and variables within your project.
http://refills.bourbon.io/