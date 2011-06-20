# Version 0.2.0

Release date: 2011-06-20

### Dependencies
* Upgrade to Selenium 2.0 RC2 (package Selenium directly again, until it becomes available as a nuget dependency)

### Added
* Hover(Func<Element>)
* Click(Func<Element>)
* Scoping within iframes
* Support id ends with, for buttons and fields
* HasContentMatch for regex, HasContent for text

### Changed
* Convert to VS2010, reference selenium+watin nuget packages, refine end-to-end examples
* SeleniumWebDriver optimisation
* End session checks for ActiveSession

# Version 0.1.3

Release date: 2011-05-27

2011-05-27

### Added
* WithinFieldset and WithinSection
* Configurable wait between find & click
* Much more support for WatiN driver (see driver_test_results.txt)
* MIT Licence 
* Nuget

### Changed
* Section headers may contain other markup, e.g. links 
* Reuse scope within individual driver methods
* Close any alerts on disposing SeleniumWebDriver 

# Version 0.1.2

Release date: 2011-05-12

### Added

* Configure the AppHost, Port and SSL globally
* Simple ExecuteScript in SeleniumWebDriver
* Set file upload paths with FillIn.With
* Scoping of HasContent
* ClickLink and ClickButton now have TryUntil overloads

### Changed

* Visit now takes a virtual path
* Renamed WaitAndRetryRobustWrapper to RetryUntilTimeoutRobustWrapper 

