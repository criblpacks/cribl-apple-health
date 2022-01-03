# Apple Health
----

This pack will aid in collection, transformation, and routeing of Apple Health metrics.  

Apple Health data is notoriously difficult to collect for custom usecases. This pack is designed to leverage the LogStream observability pipeline to collect,shape, and route your health data. 

## Requirements

Before you begin, ensure that you have met the following requirements:

* Apple iPhone or iPad with Health Kit enabled (thisis where our data comes from)
* Apple Watch (or other device reporting health metrics into the Apple Health Kit)
* iOS App [`Health Auto Export`](https://apps.apple.com/us/app/health-auto-export-json-csv/id1115567069). (this app collects Apple Health Kit data and ships data to LogStream)
* A Splunk destination (This Pack was designed for a Splunk destination, however you may choose to send to another destination if desired)


## Using The Pack

To use this Pack, follow these steps:

1. Configure a Raw_Http source to recieve from data from 'Health Auto Export app'.
2. Configure a Splunk destination (or other destination).
3. Configure Health Auto Export to ship health metrics of your choosing.


## Release Notes
This pack is still in testing and may need further refinements. Please feel free to modifiy as needed and share your improvements to the contact info below.

### Version 0.0.5 - 2022-1-03
In this inital release, we've created the a pipline for captureing and unrolling apple health data

## Contributing to the Pack
To contribute to the Pack, please do the following:

Discuss this pack on our Community Slack channel[`#packs`](https://cribl-community.slack.com/archives/C021UP7ETM3)


## Contact
To contact us please email <jhamblin@cribl.io>.


## License
This Pack uses the following license: [`Apache 2.0`](https://github.com/criblio/appscope/blob/master/LICENSE).
