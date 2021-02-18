# HelloJavaAndGroovy
Example maven project combining Java and Groovy into a runnable jar

After spending some frutrating time trying to combine Java, Groovy, and Maven into a jar that can be run at the terminal, I was finally able to come up with a `pom.xml` file that has all the basic components, including shading so the Groovy runtime is included and thus unnecessary to be installed on the target machine.

Hope this helps someone trying to make this particular cocktail of technologies. Enjoy!