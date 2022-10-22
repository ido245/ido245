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
