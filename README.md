# Apple Health
----

This pack will aid in collection, transformation, and routeing of Apple Health metrics.  

Apple Health data is notoriously difficult to collect for custome usecases. This pack is designed to leverage the LogStream observability pipeline to collect,shape, and route your health data. 

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
In this inital release, we've created the a pipleing for captureing and unrolling 

## Contributing to the Pack
To contribute to the Pack, please do the following:

[Contributor instructions go here.]


## Contact
To contact us please email <jhamblin@cribl.io>.


## License
This Pack uses the following license: [`<license_name>`](https://link-to-license-example.com).
