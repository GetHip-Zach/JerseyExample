#Example project for jersey rest api.

### Setting up your Eclipse evironment

'Help' > 'Install New Software...'

http://download.eclipse.org/webtools/repository/mars

Use this URL to download the latest Web Tools Platform SDK

http://download.eclipse.org/technology/m2e/releases

Use this URL to download Maven integration for Eclipse

### Setting up Maven Integration

1. 'Window' > 'Preferences...'

2. Expand the 'Maven' option and select 'Archetypes'

3. Click 'Add Remote Catalog...'

Catalog File:
http://repo1.maven.org/maven2/archetype-catalog.xml

Description:
Remote Access

This will allow you to access the Jersey Archetypes we will be using.

### Creating a new Jersey project with Maven

1. 'File' > 'New' > 'Other...'

2. Expand the 'Maven' folder and select 'Maven Project' then click next

3. Leave the workspace location and working set screen as default and click next

4. Filter the archetype list by typing 'Jersey' in the filter box

5. Select artifact-id 'jersey-quickstart-grizzly2' and click next

6. Set group-id to be your root package (i.e. com.gallup.gethip)

7. Set artifact-id to be your project name (i.e. jersey-example)

8. Set package to be an extension of the group-id (i.e. com.gallup.gethip.jersey)

9. Click finish. You now have a Jersey project created!

This architype contains a Grizzly servlet that can be run immidiately.


