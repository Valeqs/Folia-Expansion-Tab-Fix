This version is fixing the tab issue:

08.05.2025 - 17:56:47 - [TAB v5.2.0] Player placeholder %folia_tps% generated an error when setting for player HelloWorld
08.05.2025 - 17:56:47 - java.lang.NullPointerException: Cannot invoke "io.papermc.paper.threadedregions.ThreadedRegionizer$ThreadedRegion.getData()" because "currentRegion" is null
08.05.2025 - 17:56:47 - 	at org.dreeam.expansion.folia.FoliaUtils.getTPS(FoliaUtils.java:94)
08.05.2025 - 17:56:47 - 	at org.dreeam.expansion.folia.FoliaExpansion.getFoliaTPS(FoliaExpansion.java:226)
08.05.2025 - 17:56:47 - 	at org.dreeam.expansion.folia.FoliaExpansion.onRequest(FoliaExpansion.java:121)
08.05.2025 - 17:56:47 - 	at PlaceholderAPI-2.11.7-DEV-null.jar//me.clip.placeholderapi.replacer.CharsReplacer.apply(CharsReplacer.java:119)
08.05.2025 - 17:56:47 - 	at PlaceholderAPI-2.11.7-DEV-null.jar//me.clip.placeholderapi.PlaceholderAPI.setPlaceholders(PlaceholderAPI.java:71)
08.05.2025 - 17:56:47 - 	at PlaceholderAPI-2.11.7-DEV-null.jar//me.clip.placeholderapi.PlaceholderAPI.setPlaceholders(PlaceholderAPI.java:99)
08.05.2025 - 17:56:47 - 	at TAB v5.2.0.jar//me.neznamy.tab.platforms.bukkit.platform.BukkitPlatform.lambda$registerUnknownPlaceholder$7(BukkitPlatform.java:227)
08.05.2025 - 17:56:47 - 	at TAB v5.2.0.jar//me.neznamy.tab.shared.placeholders.types.PlayerPlaceholderImpl.request(PlayerPlaceholderImpl.java:153)
08.05.2025 - 17:56:47 - 	at TAB v5.2.0.jar//me.neznamy.tab.shared.placeholders.PlaceholderRefreshTask.run(PlaceholderRefreshTask.java:59)
08.05.2025 - 17:56:47 - 	at TAB v5.2.0.jar//me.neznamy.tab.shared.features.PlaceholderManagerImpl.lambda$refresh$1(PlaceholderManagerImpl.java:91)
08.05.2025 - 17:56:47 - 	at TAB v5.2.0.jar//me.neznamy.tab.shared.cpu.TimedCaughtTask.run(TimedCaughtTask.java:28)
08.05.2025 - 17:56:47 - 	at java.base/java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:572)
08.05.2025 - 17:56:47 - 	at java.base/java.util.concurrent.FutureTask.run(FutureTask.java:317)
08.05.2025 - 17:56:47 - 	at java.base/java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:304)
08.05.2025 - 17:56:47 - 	at java.base/java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1144)
08.05.2025 - 17:56:47 - 	at java.base/java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:642)
08.05.2025 - 17:56:47 - 	at java.base/java.lang.Thread.run(Thread.java:1583)


# Folia-Expansion
![GitHub Actions](https://img.shields.io/github/actions/workflow/status/Winds-Studio/Folia-Expansion/build.yml?style=flat-square)

Add server health related placeholders for Folia.

e.g. global tps and region tps

## Placeholders

Global placeholders

```
%folia_global_tps%
%folia_global_tps_5s%
%folia_global_tps_15s%
%folia_global_tps_1m%
%folia_global_tps_5m%
%folia_global_tps_15m%
%folia_global_tps_5s_colored%
%folia_global_tps_15s_colored%
%folia_global_tps_1m_colored%
%folia_global_tps_5m_colored%
%folia_global_tps_15m_colored%

%folia_global_mspt%
%folia_global_mspt_5s%
%folia_global_mspt_15s%
%folia_global_mspt_1m%
%folia_global_mspt_5m%
%folia_global_mspt_15m%
%folia_global_mspt_5s_colored%
%folia_global_mspt_15s_colored%
%folia_global_mspt_1m_colored%
%folia_global_mspt_5m_colored%
%folia_global_mspt_15m_colored%

%folia_global_util%
%folia_global_util_colored%
```

Region placeholders

```
%folia_tps%
%folia_tps_5s%
%folia_tps_15s%
%folia_tps_1m%
%folia_tps_5m%
%folia_tps_15m%
%folia_tps_5s_colored%
%folia_tps_15s_colored%
%folia_tps_1m_colored%
%folia_tps_5m_colored%
%folia_tps_15m_colored%

%folia_mspt%
%folia_mspt_5s%
%folia_mspt_15s%
%folia_mspt_1m%
%folia_mspt_5m%
%folia_mspt_15m%
%folia_mspt_5s_colored%
%folia_mspt_15s_colored%
%folia_mspt_1m_colored%
%folia_mspt_5m_colored%
%folia_mspt_15m_colored%

%folia_util%
%folia_util_colored%
```
