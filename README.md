# RealmAddonsManual

Manual-install addons and required custom patches for our WoW 3.3.5a realm.

**[Download the latest manual package](https://github.com/Dopey99101/wow-335a-addon-updates-manual/releases/latest)**

Open the release and download `RealmAddonsManual-1.0.rar` (or the newer version shown).
Do not use GitHub's **Code → Download ZIP** or the release's source-code archives:
those contain publishing tools, not the addon collection.

Close WoW, extract the RAR, and follow **READ-ME-FIRST.txt**. Back up the files
being replaced, then copy **Interface**, **Data** and the supplied **Wow.exe**
into the game folder, merging folders and replacing matching files.

The package includes all supplied addon folders, custom patches L/M/N, the
matching standard build-12340 executable needed by the custom interface,
and the Addons-Handbók guide. It contains no installer or command launcher.
Your WTF settings and realmlist are not included or changed by copying these files.

See [installation instructions](INSTALL.txt) and [addon commands](guides/Addons-Handbók-1.0.txt).
Addon commands are unchanged. RealmNotices is automatic; client patches have no commands.

The [installer edition](https://github.com/Dopey99101/wow-335a-addon-updates/releases/latest)
remains available separately. Both links always point to their latest published release.
Releases are published after the owner finishes and checks an update; copying files
on the owner's PC alone does not publish them or update other players automatically.

Publishing tools live under tools/. Large addon files and the executable are attached
to versioned releases, not committed to Git. Existing release versions are preserved.

## Client Links
Link to WoW-3.3.5a-ORIGINAL : https://www.mediafire.com/file_premium/btmvf0q3nqutgyh/RealmVoyager-1.0.rar/file                          
Link to WoW-3.3.5a-ULTRAHD : https://www.mediafire.com/file_premium/67mpwkdfpf1fpw6/RealmVoyagerUltraHD-1.0.rar/file

## Addon list

Installed addons and supporting folders. Some features depend on this realm.

- **_NPCScan** — Rare NPC alerts.
- **!Swatter** — Lua error viewer.
- **AckisRecipeList** — Missing recipe finder.
- **AI_VoiceOver** — Spoken NPC dialogue.
- **AI_VoiceOverData_Vanilla** — Vanilla voice recordings.
- **ArkInventory** — Customizable inventory windows.
- **Auc-Advanced** — Auctioneer pricing tools.
- **Auc-Filter-Basic** — Auction data filters.
- **Auc-ScanData** — Auction scan storage.
- **Auc-Stat-Histogram** — Auction price distributions.
- **Auc-Stat-iLevel** — Item-level price estimates.
- **Auc-Stat-Purchased** — Purchase-based price estimates.
- **Auc-Stat-Simple** — Average auction prices.
- **Auc-Stat-StdDev** — Statistical price estimates.
- **Auc-Util-FixAH** — Auction browsing fixes.
- **Auctionator** — Easier auction trading.
- **Bagnon** — Combined bag windows.
- **Bagnon_Config** — Bagnon settings.
- **Bagnon_Forever** — Saved character inventories.
- **Bagnon_GuildBank** — Combined guild bank.
- **Bagnon_Tooltips** — Item ownership tooltips.
- **BeanCounter** — Auction transaction history.
- **beql** — Enhanced quest log.
- **BonusScanner** — Equipment stat totals.
- **ChannelNoticeCompat** — Chat compatibility fixes.
- **ChatSounds** — Incoming chat sounds.
- **ClassLoot** — Class-based loot ratings.
- **Collectinator** — Pet and mount checklist.
- **Currency** — Money and currency display.
- **DBM-ChamberOfAspects** — Obsidian/Ruby Sanctum alerts.
- **DBM-Coliseum** — Coliseum encounter alerts.
- **DBM-Core** — Boss timers and warnings.
- **DBM-EyeOfEternity** — Malygos encounter alerts.
- **DBM-GUI** — DBM settings.
- **DBM-Icecrown** — Icecrown Citadel alerts.
- **DBM-Naxx** — Naxxramas encounter alerts.
- **DBM-Onyxia** — Onyxia encounter alerts.
- **DBM-Party-WotLK** — Wrath dungeon alerts.
- **DBM-PvP** — Battleground timers.
- **DBM-Ulduar** — Ulduar encounter alerts.
- **DBM-VoA** — Vault of Archavon alerts.
- **DBM-WorldEvents** — Seasonal boss alerts.
- **DrDamage** — Damage and healing estimates.
- **DressMe** — Equipment appearance previews.
- **DungeonClear** — Automated dungeon companion controls.
- **DungeonJournal** — Dungeon and boss guide.
- **Enchantrix** — Disenchanting value estimates.
- **Enchantrix-Barker** — Enchant service advertising.
- **FishingBuddy** — Fishing tools and tracking.
- **FuBar_beqlFu** — FuBar quest-log shortcut.
- **Gatherer** — Gathering location tracking.
- **Gatherer_HUD** — Gathering navigation overlay.
- **GearScore** — Equipment score display.
- **Genie** — Inventory sorting.
- **GTFO** — Dangerous ground-effect alerts.
- **HealBot** — Click-casting healing frames.
- **HunterForge** — Realm Auto Shot support.
- **HunterShotProbe** — Local Auto Shot diagnostic.
- **Informant** — Expanded item tooltips.
- **LinkedText** — Copyable chat URLs.
- **MinimapButtonFrame** — Minimap button organizer.
- **MinimapButtonFrame_SkinPack** — Button-frame appearance options.
- **ModernMapMarkers** — Dungeon and transport markers.
- **MoveAnything** — Move and resize interface elements.
- **MultiBot** — Playerbot control interface.
- **Outfitter** — Equipment outfit management.
- **Overachiever** — Achievement tools.
- **Overachiever_Tabs** — Extra achievement tabs.
- **Overachiever_Trade** — Profession achievement helpers.
- **Pawn** — Equipment upgrade comparisons.
- **Postal** — Improved mailbox tools.
- **Profession_Capper** — Profession leveling suggestions.
- **QuestHelper** — Quest routes and objectives.
- **RealmNotices** — Realm maintenance popups.
- **Recount** — Damage and healing statistics.
- **RelaxedLoot** — Delayed automatic looting.
- **SkyRoutes** — Flight paths and zone levels.
- **SlideBar** — Expandable addon shortcut bar.
- **SmartVendor** — Junk selling and repairs.
- **StarterChauffeur** — Realm chauffeur controls.
- **Stubby** — Auctioneer addon loader.
- **Titan** — Information and shortcut panels.
- **Titanbeql** — Titan quest-log shortcut.
- **TitanHealBot** — Titan HealBot shortcut.
- **TomTom** — Waypoints and navigation arrow.
- **TrinityAdmin** — GM administration interface.

### Built-in Blizzard UI folders

These are native game interface components.

- **Blizzard_AchievementUI** — Achievement window.
- **Blizzard_ArenaUI** — Arena interface.
- **Blizzard_AuctionUI** — Auction house interface.
- **Blizzard_BarbershopUI** — Barbershop interface.
- **Blizzard_BattlefieldMinimap** — Battlefield map.
- **Blizzard_BindingUI** — Keybinding settings.
- **Blizzard_Calendar** — Calendar interface.
- **Blizzard_CombatLog** — Combat log interface.
- **Blizzard_CombatText** — Floating combat text.
- **Blizzard_DebugTools** — Interface debugging tools.
- **Blizzard_GlyphUI** — Glyph interface.
- **Blizzard_GMChatUI** — GM chat interface.
- **Blizzard_GMSurveyUI** — Support survey interface.
- **Blizzard_GuildBankUI** — Guild bank interface.
- **Blizzard_InspectUI** — Character inspection.
- **Blizzard_ItemSocketingUI** — Gem socketing interface.
- **Blizzard_MacroUI** — Macro editor.
- **Blizzard_RaidUI** — Raid management.
- **Blizzard_TalentUI** — Talent interface.
- **Blizzard_TimeManager** — Clock and stopwatch.
- **Blizzard_TokenUI** — Currency interface.
- **Blizzard_TradeSkillUI** — Profession crafting interface.
- **Blizzard_TrainerUI** — Trainer interface.
