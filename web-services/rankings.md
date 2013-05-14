Rankings usage
--------------

ManiaPlanet offers a ladder for each title (made by Nadeo or by players).

The class used to retreive ranking for players depends on the title, you can get the good one by using:

```
$service = \Nadeo\Services\Rankings\RankingService::GetServiceForTitleId('SMStorm');
$service->