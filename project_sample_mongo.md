# mongoDB project example

## Version V
```sh
mongos> db.P_metadata.V.findOne({ProjectID:{$eq:'drupal.com_project_drupalorg_drupalcon'}})
{
	"_id" : ObjectId("651b3bb5ea9eb967dbc1424f"),
	"NumFiles" : 202,
	"Gender" : {
		"male" : 12,
		"female" : 1
	},
	"NumActiveMon" : 67,
	"MonNauth" : {
		"2017-10" : 2,
		"2018-09" : 4,
		"2016-05" : 1,
		"2019-06" : 1,
		"2018-07" : 3,
		"2020-05" : 1,
		"2016-06" : 1,
		"2016-09" : 1,
		"2019-07" : 2,
		"2015-01" : 1,
		"2016-01" : 1,
		"2020-03" : 1,
		"2020-07" : 2,
		"2014-01" : 1,
		"2015-03" : 1,
		"2013-04" : 1,
		"2018-06" : 2,
		"2013-03" : 1,
		"2015-11" : 1,
		"2016-08" : 2,
		"2016-07" : 2,
		"2013-05" : 1,
		"2017-11" : 3,
		"2020-02" : 1,
		"2018-03" : 1,
		"2012-07" : 2,
		"2013-01" : 2,
		"2019-09" : 1,
		"2014-05" : 1,
		"2015-06" : 3,
		"2015-04" : 1,
		"2015-05" : 1,
		"2012-04" : 1,
		"2012-05" : 1,
		"2018-11" : 3,
		"2019-12" : 1,
		"2018-05" : 2,
		"2015-09" : 1,
		"2012-10" : 1,
		"2014-02" : 1,
		"2018-08" : 3,
		"2017-03" : 1,
		"2018-04" : 4,
		"2015-02" : 2,
		"2017-06" : 1,
		"2020-01" : 1,
		"2015-12" : 1,
		"2013-08" : 2,
		"2014-03" : 1,
		"2013-07" : 1,
		"2018-10" : 2,
		"2020-08" : 1,
		"2017-09" : 2,
		"2016-12" : 1,
		"2018-12" : 1,
		"2014-10" : 1,
		"2014-06" : 1,
		"2013-06" : 1,
		"2019-01" : 1,
		"2012-02" : 1,
		"2015-10" : 1,
		"2013-12" : 1,
		"2017-02" : 1,
		"2020-06" : 1,
		"2013-02" : 1,
		"2019-08" : 3,
		"2014-09" : 1
	},
	"MonNcmt" : {
		"2013-08" : 3,
		"2014-03" : 1,
		"2013-07" : 2,
		"2015-12" : 5,
		"2018-08" : 11,
		"2017-03" : 4,
		"2018-04" : 10,
		"2020-01" : 6,
		"2015-02" : 10,
		"2017-06" : 1,
		"2015-09" : 2,
		"2018-05" : 5,
		"2019-12" : 2,
		"2014-02" : 2,
		"2012-10" : 1,
		"2013-02" : 9,
		"2019-08" : 11,
		"2017-02" : 2,
		"2020-06" : 1,
		"2014-09" : 2,
		"2012-02" : 2,
		"2013-12" : 1,
		"2015-10" : 2,
		"2019-01" : 4,
		"2014-06" : 2,
		"2013-06" : 1,
		"2018-10" : 5,
		"2016-12" : 2,
		"2018-12" : 2,
		"2014-10" : 2,
		"2020-08" : 7,
		"2017-09" : 10,
		"2014-01" : 11,
		"2019-07" : 17,
		"2015-01" : 10,
		"2016-01" : 14,
		"2018-07" : 4,
		"2020-05" : 1,
		"2016-09" : 2,
		"2016-06" : 2,
		"2020-07" : 2,
		"2020-03" : 1,
		"2016-05" : 1,
		"2019-06" : 1,
		"2017-10" : 9,
		"2018-09" : 11,
		"2015-06" : 14,
		"2012-05" : 2,
		"2018-11" : 12,
		"2015-04" : 2,
		"2015-05" : 5,
		"2012-04" : 3,
		"2017-11" : 24,
		"2020-02" : 4,
		"2015-11" : 4,
		"2016-08" : 5,
		"2013-05" : 8,
		"2016-07" : 5,
		"2012-07" : 6,
		"2013-01" : 2,
		"2019-09" : 1,
		"2014-05" : 1,
		"2018-03" : 1,
		"2018-06" : 5,
		"2013-03" : 3,
		"2015-03" : 9,
		"2013-04" : 5
	},
	"CommunitySize" : 2,
	"ProjectID" : "drupal.com_project_drupalorg_drupalcon",
	"LatestCommitDate" : 1598649415,
	"EarliestCommitDate" : 1329338787,
	"NumForks" : 0,
	"FileInfo" : {
		"PHP" : 9,
		"other" : 191,
		"JavaScript" : 2
	},
	"NumCommits" : 337,
	"NumCore" : 5,
	"Core" : {
		"Ralkeon <ralkeon@gmail.com>" : "56",
		"Jakob Perry <japerry@45640.no-reply.drupal.org>" : "89",
		"Neil Drumm <drumm@delocalizedham.com>" : "67",
		"Tyler Ward <twardnw@gmail.com>" : "37",
		"B_man <brendan@association.drupal.org>" : "23"
	},
	"NumAuthors" : 15,
	"NumBlobs" : 798
}
mongos> 
```
