# AppleCrashScripts

convertFromJSON.swift

- script for converting .ips files from new Apple JSON Crash format (used on iOS15 devices) to old style type crash report (you must put your ips file in the same directory):

`swift convertFromJSON.swift -i {your_json_ips_file} -o {name_for_file_where_crash_will_be_saved}`

e.g. 
`swift convertFromJSON.swift -i xxx.ips -o xxx.crash`


## Documentation
The Apple crash report fields are described in [official article](https://developer.apple.com/documentation/xcode/examining-the-fields-in-a-crash-report)

As Apple likes to remove docs, the copy can be found [here](./docs/apple_crash_report_format.pdf) 
