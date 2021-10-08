# Your Boyfriend Decompilation
How to access the game without valid email.
3 approaches possible 
- Retrieving master password (which is unencrypted lmao)
- Accessing the password + email database
- Rewriting the Bond script to load the scene immediately: `SceneManager.LoadScene(1);`

1. Use ILSpy and decompile Build\YourBoyfriend_Data\Managed\Assembly-CSharp.dll
2. Expand Assembly-CSharp, then expand {}
3. Bond is the script that manages game loading. Here you can observe the unencrypted master password, and email databases.

From here you can use whatever approach you like. Personally I prefer using the master password as a non destructive mechanism but you can rewrite the code if you'd like

# Dumps

Master Username: `BSGAdmin`

Master Password: `Calamity`

Email Database: https://ybf.blackshepherd.games/6mWVxrBhl7f5asIYRo6RvwcP5j/20210927_un_25a9JGR4vGtsZoJyCvFkQ2qixaeQsQxDCqT5RpuhHRC.txt

Password: https://ybf.blackshepherd.games/6mWVxrBhl7f5asIYRo6RvwcP5j/20210927_37834AGSAYasOhixaX3O9zu1KUBPHi2pSFMSfGlWxUd7je.txt

The password is `HelloDarling` as of 8th Oct 2021
