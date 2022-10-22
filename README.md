- 👋 Hi, I’m @ido245
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ido245/ido245 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Minecraft Crash Report ----
// Daisy, daisy...

Time: 22.10.2022, 16:09
Description: Mod loading error has occurred

java.lang.Exception: Mod Loading has failed
	at net.minecraftforge.logging.CrashReportExtender.dumpModLoadingCrashReport(CrashReportExtender.java:55) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?] {re:classloading}
	at net.minecraftforge.client.loading.ClientModLoader.completeModLoading(ClientModLoader.java:170) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.lambda$new$1(Minecraft.java:557) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.Util.m_137521_(Util.java:397) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading}
	at net.minecraft.client.Minecraft.lambda$new$2(Minecraft.java:551) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.LoadingOverlay.m_6305_(LoadingOverlay.java:135) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:879) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1046) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:665) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:205) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:31) ~[fmlloader-1.18.2-40.1.84.jar%2317!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:149) [bootstraplauncher-1.0.0.jar:?] {}


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Thread: Render thread
Stacktrace:
	at net.minecraftforge.logging.CrashReportExtender.lambda$dumpModLoadingCrashReport$7(CrashReportExtender.java:58) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?] {re:classloading}
-- NO MOD INFO AVAILABLE --
Details:
	Mod File: NO FILE INFO
	Failure message: Mod File EasyEmerald-Forge-1.19.0-1.4.1.jar needs language provider javafml:41 or above to load
		We have found 40
	Mod Version: NO MOD INFO AVAILABLE
	Mod Issue URL: NOT PROVIDED
	Exception message: MISSING EXCEPTION MESSAGE
Stacktrace:
	at net.minecraftforge.logging.CrashReportExtender.lambda$dumpModLoadingCrashReport$7(CrashReportExtender.java:58) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?] {re:classloading}
	at java.util.ArrayList.forEach(ArrayList.java:1511) ~[?:?] {}
	at net.minecraftforge.logging.CrashReportExtender.dumpModLoadingCrashReport(CrashReportExtender.java:56) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?] {re:classloading}
	at net.minecraftforge.client.loading.ClientModLoader.completeModLoading(ClientModLoader.java:170) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.lambda$new$1(Minecraft.java:557) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.Util.m_137521_(Util.java:397) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading}
	at net.minecraft.client.Minecraft.lambda$new$2(Minecraft.java:551) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.gui.screens.LoadingOverlay.m_6305_(LoadingOverlay.java:135) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at net.minecraft.client.renderer.GameRenderer.m_109093_(GameRenderer.java:879) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91383_(Minecraft.java:1046) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.Minecraft.m_91374_(Minecraft.java:665) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:accesstransformer:B,pl:runtimedistcleaner:A}
	at net.minecraft.client.main.Main.main(Main.java:205) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?] {re:classloading,pl:runtimedistcleaner:A}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?] {}
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?] {}
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?] {}
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?] {}
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:31) ~[fmlloader-1.18.2-40.1.84.jar%2317!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-9.1.3.jar%235!/:?] {}
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:149) [bootstraplauncher-1.0.0.jar:?] {}


-- System Details --
Details:
	Minecraft Version: 1.18.2
	Minecraft Version ID: 1.18.2
	Operating System: Windows 10 (amd64) version 10.0
	Java Version: 17.0.1, Microsoft
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Microsoft
	Memory: 775060800 bytes (739 MiB) / 1476395008 bytes (1408 MiB) up to 2147483648 bytes (2048 MiB)
	CPUs: 8
	Processor Vendor: GenuineIntel
	Processor Name: Intel(R) Core(TM) i5-1035G1 CPU @ 1.00GHz
	Identifier: Intel64 Family 6 Model 126 Stepping 5
	Microarchitecture: Ice Lake (Client)
	Frequency (GHz): 1.19
	Number of physical packages: 1
	Number of physical CPUs: 4
	Number of logical CPUs: 8
	Graphics card #0 name: Intel(R) UHD Graphics
	Graphics card #0 vendor: Intel Corporation (0x8086)
	Graphics card #0 VRAM (MB): 1024.00
	Graphics card #0 deviceId: 0x8a56
	Graphics card #0 versionInfo: DriverVersion=27.20.100.9365
	Memory slot #0 capacity (MB): 8192.00
	Memory slot #0 clockSpeed (GHz): 2.67
	Memory slot #0 type: DDR4
	Virtual memory max (MB): 14103.33
	Virtual memory used (MB): 10744.55
	Swap memory total (MB): 6144.00
	Swap memory used (MB): 0.00
	JVM Flags: 9 total; -XX:HeapDumpPath=MojangTricksIntelDriversForPerformance_javaw.exe_minecraft.exe.heapdump -Xss1M -Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M
	ModLauncher: 9.1.3+9.1.3+main.9b69c82a
	ModLauncher launch target: forgeclient
	ModLauncher naming: srg
	ModLauncher services: 
		 mixin PLUGINSERVICE 
		 eventbus PLUGINSERVICE 
		 slf4jfixer PLUGINSERVICE 
		 object_holder_definalize PLUGINSERVICE 
		 runtime_enum_extender PLUGINSERVICE 
		 capability_token_subclass PLUGINSERVICE 
		 accesstransformer PLUGINSERVICE 
		 runtimedistcleaner PLUGINSERVICE 
		 mixin TRANSFORMATIONSERVICE 
		 fml TRANSFORMATIONSERVICE 
	FML Language Providers: 
		minecraft@1.0
		lowcodefml@null
		javafml@null
	Mod List: 
אוק׳2022 16:08:50.894] [main/INFO] [cpw.mods.modlauncher.Launcher/MODLAUNCHER]: ModLauncher running: args [--username, igdh190, --version, 1.18.2-forge-40.1.84, --gameDir, C:\Users\idora\AppData\Roaming\.minecraft, --assetsDir, C:\Users\idora\AppData\Roaming\.minecraft\assets, --assetIndex, 1.18, --uuid, 50b6f02cc63e43b89387e14c694a746b, --accessToken, ????????, --clientId, YmZjYTlmNDEtOGY2NS00YTQyLWE0MjktZTlhYzBkYjA1MjEx, --xuid, 2535416413103905, --userType, msa, --versionType, release, --launchTarget, forgeclient, --fml.forgeVersion, 40.1.84, --fml.mcVersion, 1.18.2, --fml.forgeGroup, net.minecraftforge, --fml.mcpVersion, 20220404.173914]
[22אוק׳2022 16:08:50.901] [main/INFO] [cpw.mods.modlauncher.Launcher/MODLAUNCHER]: ModLauncher 9.1.3+9.1.3+main.9b69c82a starting: java version 17.0.1 by Microsoft
[22אוק׳2022 16:08:51.228] [main/INFO] [mixin/]: SpongePowered MIXIN Subsystem Version=0.8.5 Source=union:/C:/Users/idora/AppData/Roaming/.minecraft/libraries/org/spongepowered/mixin/0.8.5/mixin-0.8.5.jar%2314!/ Service=ModLauncher Env=CLIENT
[22אוק׳2022 16:08:52.226] [main/WARN] [net.minecraftforge.fml.loading.moddiscovery.ModFileParser/LOADING]: Mod file C:\Users\idora\AppData\Roaming\.minecraft\libraries\net\minecraftforge\fmlcore\1.18.2-40.1.84\fmlcore-1.18.2-40.1.84.jar is missing mods.toml file
[22אוק׳2022 16:08:52.234] [main/WARN] [net.minecraftforge.fml.loading.moddiscovery.ModFileParser/LOADING]: Mod file C:\Users\idora\AppData\Roaming\.minecraft\libraries\net\minecraftforge\javafmllanguage\1.18.2-40.1.84\javafmllanguage-1.18.2-40.1.84.jar is missing mods.toml file
[22אוק׳2022 16:08:52.243] [main/WARN] [net.minecraftforge.fml.loading.moddiscovery.ModFileParser/LOADING]: Mod file C:\Users\idora\AppData\Roaming\.minecraft\libraries\net\minecraftforge\lowcodelanguage\1.18.2-40.1.84\lowcodelanguage-1.18.2-40.1.84.jar is missing mods.toml file
[22אוק׳2022 16:08:52.250] [main/WARN] [net.minecraftforge.fml.loading.moddiscovery.ModFileParser/LOADING]: Mod file C:\Users\idora\AppData\Roaming\.minecraft\libraries\net\minecraftforge\mclanguage\1.18.2-40.1.84\mclanguage-1.18.2-40.1.84.jar is missing mods.toml file
[22אוק׳2022 16:08:52.416] [main/INFO] [net.minecraftforge.fml.loading.moddiscovery.JarInJarDependencyLocator/]: No dependencies to load found. Skipping!
[22אוק׳2022 16:08:52.513] [main/ERROR] [net.minecraftforge.fml.loading.LanguageLoadingProvider/LOADING]: Missing language javafml version [41,) wanted by EasyEmerald-Forge-1.19.0-1.4.1.jar, found 40
[22אוק׳2022 16:08:54.483] [main/INFO] [cpw.mods.modlauncher.LaunchServiceHandler/MODLAUNCHER]: Launching target 'forgeclient' with arguments [--version, 1.18.2-forge-40.1.84, --gameDir, C:\Users\idora\AppData\Roaming\.minecraft, --assetsDir, C:\Users\idora\AppData\Roaming\.minecraft\assets, --uuid, 50b6f02cc63e43b89387e14c694a746b, --username, igdh190, --assetIndex, 1.18, --accessToken, ????????, --clientId, YmZjYTlmNDEtOGY2NS00YTQyLWE0MjktZTlhYzBkYjA1MjEx, --xuid, 2535416413103905, --userType, msa, --versionType, release]
[22אוק׳2022 16:08:56.204] [main/WARN] [oshi.util.platform.windows.PerfDataUtil/]: Failed to add PDH Counter: \Paging File(_Total)\% Usage, Error code: 0xC0000BB8
[22אוק׳2022 16:08:56.205] [main/WARN] [oshi.util.platform.windows.PerfCounterQueryHandler/]: Failed to add counter for PDH counter: \Paging File(_Total)\% Usage
[22אוק׳2022 16:08:56.206] [main/WARN] [oshi.util.platform.windows.PerfCounterQuery/]: Disabling further attempts to query Paging File.
[22אוק׳2022 16:08:56.239] [main/WARN] [oshi.util.platform.windows.WmiQueryHandler/]: COM exception: Invalid Class Win32_PerfRawData_PerfOS_PagingFile
[22אוק׳2022 16:09:08.631] [Render thread/WARN] [net.minecraft.server.packs.VanillaPackResources/]: Assets URL 'union:/C:/Users/idora/AppData/Roaming/.minecraft/libraries/net/minecraft/client/1.18.2-20220404.173914/client-1.18.2-20220404.173914-srg.jar%2360!/assets/.mcassetsroot' uses unexpected schema
[22אוק׳2022 16:09:08.634] [Render thread/WARN] [net.minecraft.server.packs.VanillaPackResources/]: Assets URL 'union:/C:/Users/idora/AppData/Roaming/.minecraft/libraries/net/minecraft/client/1.18.2-20220404.173914/client-1.18.2-20220404.173914-srg.jar%2360!/data/.mcassetsroot' uses unexpected schema
[22אוק׳2022 16:09:08.698] [Render thread/INFO] [com.mojang.authlib.yggdrasil.YggdrasilAuthenticationService/]: Environment: authHost='https://authserver.mojang.com', accountsHost='https://api.mojang.com', sessionHost='https://sessionserver.mojang.com', servicesHost='https://api.minecraftservices.com', name='PROD'
[22אוק׳2022 16:09:09.919] [Render thread/INFO] [net.minecraft.client.Minecraft/]: Setting user: igdh190
[22אוק׳2022 16:09:10.212] [Render thread/INFO] [net.minecraft.client.Minecraft/]: Backend library: LWJGL version 3.2.2 SNAPSHOT
[22אוק׳2022 16:09:12.273] [Render thread/FATAL] [net.minecraftforge.fml.ModLoader/CORE]: Error during pre-loading phase
net.minecraftforge.fml.ModLoadingException: Mod File EasyEmerald-Forge-1.19.0-1.4.1.jar needs language provider javafml:41 or above to load
§7We have found 40
	at net.minecraftforge.fml.ModLoadingException.lambda$fromEarlyException$0(ModLoadingException.java:50) ~[fmlcore-1.18.2-40.1.84.jar%2361!/:?]
	at java.util.stream.ReferencePipeline$3$1.accept(ReferencePipeline.java:197) ~[?:?]
	at java.util.AbstractList$RandomAccessSpliterator.forEachRemaining(AbstractList.java:720) ~[?:?]
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509) ~[?:?]
	at java.util.stream.AbstractPipeline.wrapAndCopyInto(AbstractPipeline.java:499) ~[?:?]
	at java.util.stream.ForEachOps$ForEachOp.evaluateSequential(ForEachOps.java:150) ~[?:?]
	at java.util.stream.ForEachOps$ForEachOp$OfRef.evaluateSequential(ForEachOps.java:173) ~[?:?]
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:234) ~[?:?]
	at java.util.stream.ReferencePipeline.forEach(ReferencePipeline.java:596) ~[?:?]
	at java.util.stream.ReferencePipeline$7$1.accept(ReferencePipeline.java:276) ~[?:?]
	at java.util.ArrayList$ArrayListSpliterator.forEachRemaining(ArrayList.java:1625) ~[?:?]
	at java.util.stream.AbstractPipeline.copyInto(AbstractPipeline.java:509) ~[?:?]
	at java.util.stream.AbstractPipeline.wrapAndCopyInto(AbstractPipeline.java:499) ~[?:?]
	at java.util.stream.ReduceOps$ReduceOp.evaluateSequential(ReduceOps.java:921) ~[?:?]
	at java.util.stream.AbstractPipeline.evaluate(AbstractPipeline.java:234) ~[?:?]
	at java.util.stream.ReferencePipeline.collect(ReferencePipeline.java:682) ~[?:?]
	at net.minecraftforge.fml.ModLoader.<init>(ModLoader.java:95) ~[fmlcore-1.18.2-40.1.84.jar%2361!/:?]
	at net.minecraftforge.fml.ModLoader.get(ModLoader.java:127) ~[fmlcore-1.18.2-40.1.84.jar%2361!/:?]
	at net.minecraftforge.client.loading.ClientModLoader.lambda$begin$1(ClientModLoader.java:92) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?]
	at net.minecraftforge.client.loading.ClientModLoader.lambda$createRunnableWithCatch$4(ClientModLoader.java:112) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?]
	at net.minecraftforge.client.loading.ClientModLoader.begin(ClientModLoader.java:92) ~[forge-1.18.2-40.1.84-universal.jar%2365!/:?]
	at net.minecraft.client.Minecraft.<init>(Minecraft.java:459) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?]
	at net.minecraft.client.main.Main.main(Main.java:169) ~[client-1.18.2-20220404.173914-srg.jar%2360!/:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method) ~[?:?]
	at jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:77) ~[?:?]
	at jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43) ~[?:?]
	at java.lang.reflect.Method.invoke(Method.java:568) ~[?:?]
	at net.minecraftforge.fml.loading.targets.CommonClientLaunchHandler.lambda$launchService$0(CommonClientLaunchHandler.java:31) ~[fmlloader-1.18.2-40.1.84.jar%2317!/:?]
	at cpw.mods.modlauncher.LaunchServiceHandlerDecorator.launch(LaunchServiceHandlerDecorator.java:37) [modlauncher-9.1.3.jar%235!/:?]
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:53) [modlauncher-9.1.3.jar%235!/:?]
	at cpw.mods.modlauncher.LaunchServiceHandler.launch(LaunchServiceHandler.java:71) [modlauncher-9.1.3.jar%235!/:?]
	at cpw.mods.modlauncher.Launcher.run(Launcher.java:106) [modlauncher-9.1.3.jar%235!/:?]
	at cpw.mods.modlauncher.Launcher.main(Launcher.java:77) [modlauncher-9.1.3.jar%235!/:?]
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:26) [modlauncher-9.1.3.jar%235!/:?]
	at cpw.mods.modlauncher.BootstrapLaunchConsumer.accept(BootstrapLaunchConsumer.java:23) [modlauncher-9.1.3.jar%235!/:?]
	at cpw.mods.bootstraplauncher.BootstrapLauncher.main(BootstrapLauncher.java:149) [bootstraplauncher-1.0.0.jar:?]
[22אוק׳2022 16:09:12.636] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.sound.SoundLoadEvent to a broken mod state
[22אוק׳2022 16:09:13.118] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.ColorHandlerEvent$Block to a broken mod state
[22אוק׳2022 16:09:13.126] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.ColorHandlerEvent$Item to a broken mod state
[22אוק׳2022 16:09:13.871] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.RenderLevelStageEvent$RegisterStageEvent to a broken mod state
[22אוק׳2022 16:09:14.555] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.ParticleFactoryRegisterEvent to a broken mod state
[22אוק׳2022 16:09:14.650] [Render thread/INFO] [com.mojang.text2speech.NarratorWindows/]: Narrator library for x64 successfully loaded
[22אוק׳2022 16:09:14.746] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.RegisterClientReloadListenersEvent to a broken mod state
[22אוק׳2022 16:09:14.748] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$RegisterLayerDefinitions to a broken mod state
[22אוק׳2022 16:09:14.749] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$RegisterRenderers to a broken mod state
[22אוק׳2022 16:09:15.247] [Render thread/INFO] [net.minecraft.server.packs.resources.ReloadableResourceManager/]: Reloading ResourceManager: Default
[22אוק׳2022 16:09:15.568] [Worker-Main-12/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.ModelRegistryEvent to a broken mod state
[22אוק׳2022 16:09:15.840] [Worker-Main-13/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:15.840] [Worker-Main-14/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:16.002] [Worker-Main-8/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:37.331] [Worker-Main-12/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:39.673] [Worker-Main-12/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:39.707] [Worker-Main-12/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:39.800] [Worker-Main-12/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:39.872] [Worker-Main-12/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:39.892] [Worker-Main-12/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:39.942] [Worker-Main-12/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Pre to a broken mod state
[22אוק׳2022 16:09:40.874] [Render thread/INFO] [com.mojang.blaze3d.audio.Library/]: OpenAL initialized on device OpenAL Soft on רמקולים (Realtek(R) Audio)
[22אוק׳2022 16:09:40.877] [Render thread/INFO] [net.minecraft.client.sounds.SoundEngine/SOUNDS]: Sound engine started
[22אוק׳2022 16:09:41.316] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 1024x512x4 minecraft:textures/atlas/blocks.png-atlas
[22אוק׳2022 16:09:41.494] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:41.495] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 256x128x4 minecraft:textures/atlas/signs.png-atlas
[22אוק׳2022 16:09:41.498] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:41.498] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 512x512x4 minecraft:textures/atlas/banner_patterns.png-atlas
[22אוק׳2022 16:09:41.510] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:41.511] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 512x512x4 minecraft:textures/atlas/shield_patterns.png-atlas
[22אוק׳2022 16:09:41.523] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:41.524] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 256x256x4 minecraft:textures/atlas/chest.png-atlas
[22אוק׳2022 16:09:41.527] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:41.528] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 512x256x4 minecraft:textures/atlas/beds.png-atlas
[22אוק׳2022 16:09:41.535] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:41.536] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 512x256x4 minecraft:textures/atlas/shulker_boxes.png-atlas
[22אוק׳2022 16:09:41.542] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:42.268] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.ModelBakeEvent to a broken mod state
[22אוק׳2022 16:09:42.708] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:42.717] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.061] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.065] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.067] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.083] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.111] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.111] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.112] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.114] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.115] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.116] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.117] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.123] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.124] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.129] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.144] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.146] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.147] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.149] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.173] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.174] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$CreateSkullModels to a broken mod state
[22אוק׳2022 16:09:43.175] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.EntityRenderersEvent$AddLayers to a broken mod state
[22אוק׳2022 16:09:46.612] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.RegisterShadersEvent to a broken mod state
[22אוק׳2022 16:09:47.146] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 256x256x0 minecraft:textures/atlas/particles.png-atlas
[22אוק׳2022 16:09:47.169] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:47.172] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 256x256x0 minecraft:textures/atlas/paintings.png-atlas
[22אוק׳2022 16:09:47.177] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:47.177] [Render thread/INFO] [net.minecraft.client.renderer.texture.TextureAtlas/]: Created: 128x128x0 minecraft:textures/atlas/mob_effects.png-atlas
[22אוק׳2022 16:09:47.182] [Render thread/ERROR] [net.minecraftforge.fml.ModLoader/]: Cowardly refusing to send event net.minecraftforge.client.event.TextureStitchEvent$Post to a broken mod state
[22אוק׳2022 16:09:47.877] [Render thread/WARN] [oshi.util.platform.windows.WmiQueryHandler/]: COM exception: Invalid Class Win32_PerfRawData_PerfOS_PagingFile
[22אוק׳2022 16:09:47.911] [Render thread/FATAL] [net.minecraftforge.client.loading.ClientModLoader/]: Crash report saved to C:\Users\idora\AppData\Roaming\.minecraft\crash-reports\crash-2022-10-22_16.09.47-fml.
