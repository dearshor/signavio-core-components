signavio-core-components
========================

Forked from http://code.google.com/p/signavio-core-components/ . I'd like to customize the build config to fit my need, and use git to track these  changes.

How to install and run the Signavio Core Components. 
See http://code.google.com/p/signavio-core-components/wiki/InstallationInstructions

I have changed build.properties to use "Activiti" configuration, with other corresponding changes made in first build process either, so you just 
  git clone git://github.com/dearshor/signavio-core-components.git
  cd signavio-core-components
  ant ant build-all-in-one-war
 then use can find the activiti-modeler in "signavio-core-components/target" folder