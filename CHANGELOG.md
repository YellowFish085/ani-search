# Changelog

## v2.0.2 (16/01/2025)

### Changes

- [Changes] Re-set focus on search input when search is done.
- [Changes] Changed some error messages.
- [Add] Search delay is now configurable.
- [Add] Invalid access token now display a special error.
- [Fix] Remove some tests leftovers.

## v2.0.1 (12/11/2024)

### Changes

- [Fix] Fixed popup height issue
- [Fix] Re-added add-on shortcut on Firefox

## v2.0.0 (11/11/2024)

Note: This is mostly a backend update because of code rewrite, but it contains a few minor changes listed below.

- Code rewrite + manifest v3 support.
- Removed web integration for unavailable websites and fixed web web integration for those still up.
- More accurate data displayed by search results.
- Slight changes in UI (font sizes, spacing, ...) due to rewrite.
- More notifications for important actions + all notifications are now browser notifications.


## v1.3.7 (19/03/2022)

### Changes
- [Add] Add customizable shortcut to open the add-on popup (f8f633b)
- (dev stuff) Updated packages

## v1.3.6 (12/07/2021)

### Changes
- (dev stuff) Updated packages

## v1.3.5 (02/04/2021)

### Changes
- (dev stuff) Updated packages

## v1.3.4 (10/12/2020)

### Changes

- [Changes] Search input autofocus when popup is opened (c14fe22)
- [Fix] Fixed autofocus on search input after search is done on Chrome (61ee0c5)
- (dev stuff) Updated packages

## v1.3.3 (01/11/2020)

### Changes

- [Fix] Fixed some issues with AnimeLab web integration (PR #9, thanks [SuperSonic16](https://github.com/thesupersonic16))
- (dev stuff) Updated packages

## v1.3.2 (11/09/2020)

### New features

- Global search results and results from your lists are now displayed in separate foldable lists (606a68a, 4c8ac5d)

### Changes

- [Changes] More placeholder media cards (708398b)
- [Changes] Delay between keyup and autosearch has been bumped up a bit (ef5756f)
- [Add] Added text when search results are empty (46966a0)
- [Add] Added ADN web integration (2348996)
- (dev stuff) Updated packages

## v1.3.1 (14/06/2020)

### Changes

- [Change] (dev stuff) App now use real graphql files (89b3ffa)
- (dev stuff) Updated packages & build commands

## v1.3.0 (03/05/2020)

### New features

- Added card layout switcher to display cards as cover, chart or table (da45a6e, 1a15d18, 32bf4d2)

### Changes

- [Change] Updated themes and cards layout following AniList recent update (4c5fc14, 38e8e5e, 3b679aa)
- [Change] (dev stuff) Web integration button postion can be overriden (9c91828)
- [Fix] Fixed login/logout settings container content overflowing (27e79f5, 7f19a4b)
- [Fix] Fixed weird bug in Firefox Developer Edition where activity was not stored (23797ce)
- [Fix] Fixed Chrome inputs and focus style (2eb7939, 8fb0d9f)
- Various minor fixes and dev stuff

## v1.2.0 (25/04/2020)

### New features

- Web integration button position can now be configured (00ba57b)
- Web integration button can be inserted near page title instead (7d48f5a)

### Changes

- [Change] Web integration buttons now open links in new tab (6f300d8)
- [Add] Added Hidive web integration (80d1c6b)
- [Change] (dev stuff) Rework settings to make it easier to maintain (c0a55a0)
- Various fixes and code improvement

## v1.1.3 (19/04/2020)

- [Add] Added AnimeLab web integration (PR #5, thanks [SuperSonic16](https://github.com/thesupersonic16))
- Fixed typos

## v1.1.2 (19/04/2020)

- [Fix] Fixed media studio link click (c48df95)
- [Change] Web integration now use different value for display and search (8ada1e1)
- [Fix] Added missing web integration translations (904b849)
- [Add] Added Wakanim web integration (be9cfe5, 2296fe3)
- [Add] Added Funimation web integration (cf42d8e)
- [Add] Added missing pages for Crunchyroll web integration (2296fe3)
- Various css fixes

## v1.1.1 (18/04/2020)

- [Fix] Fixed external links not opening on Chrome (d12df24)
- [Remove] Removed unused Firefox extension parameter (aa0dad5)

## v1.1.0 (18/04/2020)

### New features
- Added UI translation in English and French (715e60c)
- Added web integration feature (c73e86f)
  - Currently only for Crunchyroll

### Changes
- [Change] Updated logo 128 for Chrome (9da6cf5)
- [Fix] Fixed notification popup z-index (36338cf)
- [Fix] Speed up popup opening (635f908)

## v1.0.4 (16/04/2020)

- [Fix] Fixed header height (54739bc)
- [Fix] Fixed Firefox popup arrow color (3323b91)
- [Add] Added logo 128 (0e8bf4e)

## v1.0.3 (13/04/2020)

- [Remove] Removed search provider for Chrome (47597b6)
- [Remove] Removed unused tabs permission (8add3ee)
- Renamed (once again) extension to Ani-Search

## v1.0.2 (11/04/2020)

- Renamed extension to AniListSearch

## v1.0.1 (11/04/2020)

- [Add] Added enums strings (d9204fc)
- [Change] Changed used images in certain parts of the extension (33b61cd)
- [Change] Changed the order of the search Year filter (8831adc)
- [Add] Added an About section in the settings page (936249d)
- [Upadte] Packages update + npm audit (d652448)
- Various css changes


## v1.0.0 (11/04/2020)

- Initial release
