# UE4-CacheSettings

Original: https://answers.unrealengine.com/questions/255793/derived-data-cache-1.html

Open BaseEngine.ini > UnrealEngineVersion\Engine\Config\BaseEngine.ini
Find: [InstalledDerivedDataBackendGraph]
Change: Path="%ENGINEVERSIONAGNOSTICUSERDIR%DerivedDataCache"
to: Path="%GAMEDIR%LocalDerivedDataCache"
All cache will be saved in to directory of your project
