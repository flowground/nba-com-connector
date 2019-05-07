# ![LOGO](logo.png) NBA Stats **flow**ground Connector

## Description

A generated **flow**ground connector for the NBA Stats API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/nba.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:11+03:00

## API Description

The destination for current and historic NBA statistics.

## Authorization

This API does not require authorization.

## Actions

### get_allstarballotpredictor

#### Input Parameters
* `PointCap` - _optional_
* `WestPlayer1` - _required_
* `WestPlayer2` - _required_
* `WestPlayer3` - _required_
* `WestPlayer4` - _required_
* `WestPlayer5` - _required_
* `EastPlayer1` - _required_
* `EastPlayer2` - _required_
* `EastPlayer3` - _required_
* `EastPlayer4` - _required_
* `EastPlayer5` - _required_

### get_boxscore

#### Input Parameters
* `GameID` - _optional_
* `StartPeriod` - _optional_
* `EndPeriod` - _optional_
* `StartRange` - _optional_
* `EndRange` - _optional_
* `RangeType` - _optional_

### get_boxscoreadvanced

#### Input Parameters
* `GameID` - _optional_
* `StartPeriod` - _optional_
* `EndPeriod` - _optional_
* `StartRange` - _optional_
* `EndRange` - _optional_
* `RangeType` - _optional_

### get_boxscoreadvancedv2

#### Input Parameters
* `GameID` - _required_
* `StartPeriod` - _required_
* `EndPeriod` - _required_
* `StartRange` - _required_
* `EndRange` - _required_
* `RangeType` - _required_

### get_boxscorefourfactors

#### Input Parameters
* `GameID` - _optional_
* `StartPeriod` - _optional_
* `EndPeriod` - _optional_
* `StartRange` - _optional_
* `EndRange` - _optional_
* `RangeType` - _optional_

### get_boxscorefourfactorsv2

#### Input Parameters
* `GameID` - _required_
* `StartPeriod` - _required_
* `EndPeriod` - _required_
* `StartRange` - _required_
* `EndRange` - _required_
* `RangeType` - _required_

### get_boxscoremisc

#### Input Parameters
* `GameID` - _optional_
* `StartPeriod` - _optional_
* `EndPeriod` - _optional_
* `StartRange` - _optional_
* `EndRange` - _optional_
* `RangeType` - _optional_

### get_boxscoremiscv2

#### Input Parameters
* `GameID` - _required_
* `StartPeriod` - _required_
* `EndPeriod` - _required_
* `StartRange` - _required_
* `EndRange` - _required_
* `RangeType` - _required_

### get_boxscoreplayertrackv2

#### Input Parameters
* `GameID` - _required_

### get_boxscorescoring

#### Input Parameters
* `GameID` - _optional_
* `StartPeriod` - _optional_
* `EndPeriod` - _optional_
* `StartRange` - _optional_
* `EndRange` - _optional_
* `RangeType` - _optional_

### get_boxscorescoringv2

#### Input Parameters
* `GameID` - _required_
* `StartPeriod` - _required_
* `EndPeriod` - _required_
* `StartRange` - _required_
* `EndRange` - _required_
* `RangeType` - _required_

### get_boxscoresummaryv2

#### Input Parameters
* `GameID` - _required_

### get_boxscoretraditionalv2

#### Input Parameters
* `GameID` - _required_
* `StartPeriod` - _required_
* `EndPeriod` - _required_
* `StartRange` - _required_
* `EndRange` - _required_
* `RangeType` - _required_

### get_boxscoreusage

#### Input Parameters
* `GameID` - _optional_
* `StartPeriod` - _optional_
* `EndPeriod` - _optional_
* `StartRange` - _optional_
* `EndRange` - _optional_
* `RangeType` - _optional_

### get_boxscoreusagev2

#### Input Parameters
* `GameID` - _required_
* `StartPeriod` - _required_
* `EndPeriod` - _required_
* `StartRange` - _required_
* `EndRange` - _required_
* `RangeType` - _required_

### get_commonTeamYears

#### Input Parameters
* `LeagueID` - _required_

### get_commonallplayers

#### Input Parameters
* `LeagueID` - _required_
* `Season` - _required_
* `IsOnlyCurrentSeason` - _required_

### get_commonplayerinfo

#### Input Parameters
* `PlayerID` - _required_

### get_commonplayoffseries

#### Input Parameters
* `LeagueID` - _required_
* `Season` - _required_

### get_commonteamroster

#### Input Parameters
* `Season` - _required_
* `TeamID` - _required_

### get_draftcombinedrillresults

#### Input Parameters
* `LeagueID` - _required_
* `SeasonYear` - _required_

### get_draftcombinenonstationaryshooting

#### Input Parameters
* `LeagueID` - _required_
* `SeasonYear` - _required_

### get_draftcombineplayeranthro

#### Input Parameters
* `LeagueID` - _required_
* `SeasonYear` - _required_

### get_draftcombinespotshooting

#### Input Parameters
* `LeagueID` - _required_
* `SeasonYear` - _required_

### get_draftcombinestats

#### Input Parameters
* `LeagueID` - _required_
* `SeasonYear` - _required_

### get_drafthistory

#### Input Parameters
* `LeagueID` - _required_

### get_franchisehistory

#### Input Parameters
* `LeagueID` - _required_

### get_homepageleaders

#### Input Parameters
* `StatCategory` - _required_
* `LeagueID` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerOrTeam` - _required_
* `Game` - _optional_
* `Player` - _optional_
* `PlayerScope` - _required_
* `GameScope` - _required_

### get_homepagev2

#### Input Parameters
* `StatType` - _required_
* `LeagueID` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerOrTeam` - _required_
* `Game` - _optional_
* `Player` - _optional_
* `PlayerScope` - _required_
* `GameScope` - _required_

### get_leaderstiles

#### Input Parameters
* `Stat` - _required_
* `LeagueID` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerOrTeam` - _required_
* `Game` - _optional_
* `Player` - _optional_
* `PlayerScope` - _required_
* `GameScope` - _required_

### get_leaguedashlineups

#### Input Parameters
* `GroupQuantity` - _required_
* `SeasonType` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_leaguedashplayerbiostats

#### Input Parameters
* `PerMode` - _required_
* `LeagueID` - _required_
* `Season` - _required_
* `SeasonType` - _required_

### get_leaguedashplayerclutch

#### Input Parameters
* `ClutchTime` - _required_
* `AheadBehind` - _required_
* `PointDiff` - _required_
* `GameScope` - _required_
* `PlayerExperience` - _required_
* `PlayerPosition` - _required_
* `StarterBench` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_leaguedashplayerptshot

#### Input Parameters
* `LeagueID` - _required_
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_

### get_leaguedashplayershotlocations

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_
* `DistanceRange` - _required_
* `GameScope` - _required_
* `PlayerExperience` - _required_
* `PlayerPosition` - _required_
* `StarterBench` - _required_

### get_leaguedashplayerstats

#### Input Parameters
* `GameScope` - _required_
* `PlayerExperience` - _required_
* `PlayerPosition` - _required_
* `StarterBench` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_leaguedashptdefend

#### Input Parameters
* `LeagueID` - _required_
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `DefenseCategory` - _required_

### get_leaguedashptteamdefend

#### Input Parameters
* `LeagueID` - _required_
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `DefenseCategory` - _required_

### get_leaguedashteamclutch

#### Input Parameters
* `ClutchTime` - _required_
* `AheadBehind` - _required_
* `PointDiff` - _required_
* `GameScope` - _required_
* `PlayerExperience` - _required_
* `PlayerPosition` - _required_
* `StarterBench` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_leaguedashteamptshot

#### Input Parameters
* `LeagueID` - _required_
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_

### get_leaguedashteamshotlocations

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_
* `DistanceRange` - _required_
* `GameScope` - _required_
* `PlayerExperience` - _required_
* `PlayerPosition` - _required_
* `StarterBench` - _required_

### get_leaguedashteamstats

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_leagueleaders

#### Input Parameters
* `LeagueID` - _required_
* `PerMode` - _required_
* `StatCategory` - _optional_
* `Season` - _required_
* `SeasonType` - _required_
* `Scope` - _required_

### get_playbyplay

#### Input Parameters
* `GameID` - _required_
* `StartPeriod` - _required_
* `EndPeriod` - _required_

### get_playbyplayv2

#### Input Parameters
* `GameID` - _required_
* `StartPeriod` - _required_
* `EndPeriod` - _required_

### get_playercareerstats

#### Input Parameters
* `PerMode` - _required_
* `PlayerID` - _required_

### get_playercompare

#### Input Parameters
* `PlayerIDList` - _required_
* `VsPlayerIDList` - _required_
* `SeasonType` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashboardbyclutch

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashboardbygamesplits

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashboardbygeneralsplits

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashboardbylastngames

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashboardbyopponent

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashboardbyshootingsplits

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashboardbyteamperformance

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashboardbyyearoveryear

#### Input Parameters
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashptpass

#### Input Parameters
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `TeamID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `LastNGames` - _required_

### get_playerdashptreb

#### Input Parameters
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `TeamID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashptreboundlogs

#### Input Parameters
* `Season` - _optional_
* `SeasonType` - _optional_
* `PlayerID` - _optional_
* `TeamID` - _optional_
* `Outcome` - _optional_
* `Location` - _optional_
* `Month` - _optional_
* `SeasonSegment` - _optional_
* `DateFrom` - _optional_
* `DateTo` - _optional_
* `OpponentTeamID` - _optional_
* `VsConference` - _optional_
* `VsDivision` - _optional_
* `GameSegment` - _optional_
* `Period` - _optional_
* `LastNGames` - _optional_

### get_playerdashptshotdefend

#### Input Parameters
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `TeamID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playerdashptshotlog

#### Input Parameters
* `LeagueID` - _optional_
* `Season` - _optional_
* `SeasonType` - _optional_
* `PlayerID` - _optional_
* `TeamID` - _optional_

### get_playerdashptshots

#### Input Parameters
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `PlayerID` - _required_
* `TeamID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playergamelog

#### Input Parameters
* `PlayerID` - _required_
* `Season` - _required_
* `SeasonType` - _required_

### get_playerprofile

#### Input Parameters
* `LeagueID` - _required_
* `PlayerID` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `GraphStartSeason` - _required_
* `GraphEndSeason` - _required_
* `GraphStat` - _required_

### get_playerprofilev2

#### Input Parameters
* `PerMode` - _required_
* `PlayerID` - _required_

### get_playersvsplayers

#### Input Parameters
* `PlayerTeamID` - _required_
* `PlayerID1` - _required_
* `PlayerID2` - _required_
* `PlayerID3` - _required_
* `PlayerID4` - _required_
* `PlayerID5` - _required_
* `VsTeamID` - _required_
* `VsPlayerID1` - _required_
* `VsPlayerID2` - _required_
* `VsPlayerID3` - _required_
* `VsPlayerID4` - _required_
* `VsPlayerID5` - _required_
* `SeasonType` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playervsplayer

#### Input Parameters
* `PlayerID` - _required_
* `VsPlayerID` - _required_
* `SeasonType` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_playoffpicture

#### Input Parameters
* `LeagueID` - _required_
* `SeasonID` - _required_

### get_scoreboard

#### Input Parameters
* `GameDate` - _required_
* `LeagueID` - _required_
* `DayOffset` - _required_

### get_scoreboardV2

#### Input Parameters
* `GameDate` - _required_
* `LeagueID` - _required_
* `DayOffset` - _required_

### get_shotchartdetail

#### Input Parameters
* `SeasonType` - _required_
* `TeamID` - _required_
* `PlayerID` - _required_
* `GameID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `Position` - _required_
* `RookieYear` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_
* `ContextMeasure` - _required_

### get_shotchartlineupdetail

#### Input Parameters
* `LeagueID` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `TeamID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_
* `GameID` - _required_
* `GROUP_ID` - _required_
* `ContextMeasure` - _required_
* `ContextFilter` - _required_

### get_teamdashboardbyclutch

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashboardbygamesplits

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashboardbygeneralsplits

#### Input Parameters
* `SeasonType` - _required_
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashboardbylastngames

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashboardbyopponent

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashboardbyshootingsplits

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashboardbyteamperformance

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashboardbyyearoveryear

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashlineups

#### Input Parameters
* `GroupQuantity` - _required_
* `GameID` - _required_
* `SeasonType` - _required_
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashptpass

#### Input Parameters
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `TeamID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `LastNGames` - _required_

### get_teamdashptreb

#### Input Parameters
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `TeamID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamdashptshots

#### Input Parameters
* `PerMode` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `TeamID` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamgamelog

#### Input Parameters
* `TeamID` - _required_
* `Season` - _required_
* `SeasonType` - _required_

### get_teaminfocommon

#### Input Parameters
* `Season` - _required_
* `TeamID` - _required_
* `LeagueID` - _required_
* `SeasonType` - _required_

### get_teamplayerdashboard

#### Input Parameters
* `SeasonType` - _required_
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamplayeronoffdetails

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamplayeronoffsummary

#### Input Parameters
* `TeamID` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `SeasonType` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamvsplayer

#### Input Parameters
* `TeamID` - _required_
* `VsPlayerID` - _required_
* `SeasonType` - _required_
* `MeasureType` - _required_
* `PerMode` - _required_
* `PlusMinus` - _required_
* `PaceAdjust` - _required_
* `Rank` - _required_
* `Season` - _required_
* `Outcome` - _required_
* `Location` - _required_
* `Month` - _required_
* `SeasonSegment` - _required_
* `DateFrom` - _required_
* `DateTo` - _required_
* `OpponentTeamID` - _required_
* `VsConference` - _required_
* `VsDivision` - _required_
* `GameSegment` - _required_
* `Period` - _required_
* `LastNGames` - _required_

### get_teamyearbyyearstats

#### Input Parameters
* `LeagueID` - _required_
* `SeasonType` - _required_
* `PerMode` - _required_
* `TeamID` - _required_

### get_videoStatus

#### Input Parameters
* `LeagueID` - _required_
* `GameDate` - _required_

## License

**flow**ground :- Telekom iPaaS / nba-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
