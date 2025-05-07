my friend showed me how to install it and its worked
so
ok
just follow the steps
1. Install java and extract it https://stash.qtpc.tech/Java.7z
![Screenshot](screenshot/screenshot.png)
2. Move "graalvm-jdk-21.0.6+8.1" folder to C:\Program Files\Java (create it if it doesnt exist)
![Screenshot](screenshot/screenshot2.png)
![Screenshot](screenshot/screenshot3.png)
3. Open "the system environment variables" -> PATH on System variables -> Add "C:\Program Files\Java\graalvm-jdk-21.0.6+8.1\bin"
![Screenshot](screenshot/screenshot4.png)
4. Test java on cmd to make sure it works
![Screenshot](screenshot/screenshot5.png)
5. Create a folder named "Celestial" anywhere in the Documents directory, and move the file "celestial-3.2.1-SNAPSHOT-fatjar.jar" into that folder.
![Screenshot](screenshot/screenshot6.png)
6. Create a shortcut, sel "celestial-3.2.1-SNAPSHOT-fatjar.jar", Next and rename for this shortcut if u want then Finish.


![Screenshot](screenshot/sc7.png)
![Screenshot](screenshot/sc8.png)


7. Open Properties of this shortcut and follow me

------------- Put this to the 'Target' directory -------------

"C:\Program Files\Java\graalvm-jdk-21.0.6+8.1\bin\javaw.exe" -jar "C:\Users\ "name" \Documents\Celestial\celestial-3.2.1-SNAPSHOT-fatjar.jar"

------------- "Start in" -------------

C:\Users\ "username" \Documents\Celestial


![Screenshot](screenshot/sc8.png)

so done, u can launch it normally :3 

![Screenshot](screenshot/g1.png)


ah
u can add "LunarPerformance.jar" to "JavaAgents" like this
![Screenshot](screenshot/g2.png)

have fun!