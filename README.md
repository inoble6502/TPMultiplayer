UE4 Third Person Multiplayer project

notes:
-tests hosting/joining a session on one connection
-players are replicated by default
-added in TPMultiplayer/Config/DefaultEngine.ini
[OnlineSubsystem]
DefaultPlatformService=Null
-In the Create/Find Session nodes in ThirdPersonGameInstance, the 'Use LAN' options are check but they seem to work when both are unchecked as well