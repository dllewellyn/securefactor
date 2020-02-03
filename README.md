# securefactor
Intellij plugin for secure Android refactoring


## Obfuscating strings

First you'll need to import the obfuscation library 

```
repositories {
    maven {
        url "https://dl.bintray.com/dllewellyn/kotlin-string-obfuscator"
    }
}

dependencies {
    implementation 'com.secure.obfuscated:kotlin-string-obfuscator:1.0.0' // Check latest version first! 
}
```

![](obfuscate.gif)


## Migrating to EncryptedSharedPreferences and EncryptedFile

First, import the library 

```
implementation "androidx.security:security-crypto:1.0.0-alpha02"

```

### Converting to encrypted shared preferences

![](encryptedsharedprefs.git)


### Converting to encrypted file

![](encryptedfile.gif)
