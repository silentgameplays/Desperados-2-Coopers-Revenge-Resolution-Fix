# Desperados-2-Coopers-Revenge-Resolution-Fix
Desperados 2 Coopers Revenge Resolution Fix

1. Go to Control Panel>Programs>Programs and Features>Turn Windows Features on or off>Legacy Components>Enable Direct Play .NET 3.5 Framework support 

2. Install Game

# 3. (Easy way) Download the settings.ini file from this repo extract and paste it into this folder:
C:\Program Files (x86)\Steam\steamapps\common\Desperados2\configuration\game\ 

# 4.(Hard way)Go into C:\Program Files (x86)\Steam\steamapps\common\Desperados2\configuration\game\ 
* Find the settings.xml file and edit it with notepad 
# Search for:

< Attribute name="ENGINE_RESOLUTION_X" value="1024" type="slong"/ >

< Attribute name="ENGINE_RESOLUTION_Y" value="768" type="slong"/ >

# Change these attributes to: 

< Attribute name="ENGINE_RESOLUTION_X" value="1920" type="slong"/ >

< Attribute name="ENGINE_RESOLUTION_Y" value="1080" type="slong"/ >
