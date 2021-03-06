Release notes
=============
### 0.14.0 (2018-08-27)
* Add template combinations commands ([#3969](http://projects.theforeman.org/issues/3969))
* Fix and extend tests for user update ([#23996](http://projects.theforeman.org/issues/23996))
* Hammer asks for user password though -p option provided ([#23996](http://projects.theforeman.org/issues/23996))
* Stop overriding apipie help for host flags ([PR #380](https://github.com/theforeman/hammer-cli-foreman/pull/380)) ([#24490](http://projects.theforeman.org/issues/24490))
* Hammer report info doesn't show logs resources and messages ([PR #375](https://github.com/theforeman/hammer-cli-foreman/pull/375)) ([#12189](http://projects.theforeman.org/issues/12189))
* Remove legacy code for Ruby < 2.0 ([#21360](http://projects.theforeman.org/issues/21360))
* Add disassociate command to host ([#15674](http://projects.theforeman.org/issues/15674))
* Align subnet translations in hammer with UI ([#9906](http://projects.theforeman.org/issues/9906))
* Propagate the error message from core ([#24285](http://projects.theforeman.org/issues/24285))
* Hammer uses /config_reports rather than /reports ([PR #374](https://github.com/theforeman/hammer-cli-foreman/pull/374)) ([#14510](http://projects.theforeman.org/issues/14510))
* Setting list should show full names ([#20360](http://projects.theforeman.org/issues/20360))
* Show cidr notation ([#22988](http://projects.theforeman.org/issues/22988))
* Removed redundant info about OS from hostgroup ([#23722](http://projects.theforeman.org/issues/23722))
* Add MTU to subnet info ([#23401](http://projects.theforeman.org/issues/23401))

### 0.13.0 (2018-05-09)
* Listing all auth sources ([#19651](http://projects.theforeman.org/issues/19651))
* Tests are green with 1.18 API docs ([#23219](http://projects.theforeman.org/issues/23219))
* Add commands for Audits ([#2921](http://projects.theforeman.org/issues/2921))
* fix logging by requiring logger ([PR #364](https://github.com/theforeman/hammer-cli-foreman/pull/364)) ([#23108](http://projects.theforeman.org/issues/23108))
* Add personal access token cli support ([#21514](http://projects.theforeman.org/issues/21514))
* Update to API doc form 1.17 ([PR #362](https://github.com/theforeman/hammer-cli-foreman/pull/362)) ([#22989](http://projects.theforeman.org/issues/22989))
* Improve class import output ([#4609](http://projects.theforeman.org/issues/4609))
* Some numeric options are no longer recognized as numeric ([#22964](http://projects.theforeman.org/issues/22964))
* Pull in the latest strings from Dev ([#22866](http://projects.theforeman.org/issues/22866))
* Temporary fix for override values ([#22751](http://projects.theforeman.org/issues/22751))
* Raise error when wrong number of ids is resolved ([#22718](http://projects.theforeman.org/issues/22718))
* Puppetrun command is moved from hosts to puppet hosts ([#22658](http://projects.theforeman.org/issues/22658))
* Hammer should provide commands for showing host's ENC YAML ([#16423](http://projects.theforeman.org/issues/16423))
* Remove deprecation warning from --root-password in host create/update ([#18636](http://projects.theforeman.org/issues/18636))

### 0.12.0 (2018-02-19)
* Do not resolve already resolved id params ([#22517](http://projects.theforeman.org/issues/22517))
* Generate --provision-method from apidoc ([#22552](http://projects.theforeman.org/issues/22552))
* Review whitespace in extracted strings ([#7451](http://projects.theforeman.org/issues/7451))
* Allow nil searchables ([#21768](http://projects.theforeman.org/issues/21768))
* Fix typo for hostgroup in functional test ([#22094](http://projects.theforeman.org/issues/22094))
* Rename add-override-value to add-matcher ([#12999](http://projects.theforeman.org/issues/12999))
* Handle 400 bad request - concat response message ([#21627](http://projects.theforeman.org/issues/21627))
* Make hammer host reports work ([#20742](http://projects.theforeman.org/issues/20742))
* "unknown template kind" message translated ([#4573](http://projects.theforeman.org/issues/4573))
* Add status for Void authenticator ([#20505](http://projects.theforeman.org/issues/20505))
* Add show command for ssh-keys ([#20476](http://projects.theforeman.org/issues/20476))
* Add org/loc in ptable info command ([#21264](http://projects.theforeman.org/issues/21264))
* Create compute-resource VMware - URL optional ([#17568](http://projects.theforeman.org/issues/17568))
* Test to expect integer params as a number ([#21013](http://projects.theforeman.org/issues/21013))
* Add ssh-keys commands ([#20476](http://projects.theforeman.org/issues/20476))
* Remove --include and --thin from host-hostgroup list ([#20754](http://projects.theforeman.org/issues/20754))
* Added fields info to hostgroup/host info command ([#18750](http://projects.theforeman.org/issues/18750))
* Don't store session_id for unauthorized responses ([#20575](http://projects.theforeman.org/issues/20575))
* Owner Name is shown in hammer host info command ([#20709](http://projects.theforeman.org/issues/20709))
* Show empty table field with ReferenceFormatter ([#20758](http://projects.theforeman.org/issues/20758))
* Better logging of 403 responses ([#20120](http://projects.theforeman.org/issues/20120))
* Update documentation for sessions ([#20315](http://projects.theforeman.org/issues/20315))

### 0.11.0 (2017-08-01)
* Adding a list normalizer to override-value-order ([#17135](http://projects.theforeman.org/issues/17135))
* Correctly reset taxonomies for overriding filters ([#20117](http://projects.theforeman.org/issues/20117))
* Sessions mutually exclusive with basic auth ([#20315](http://projects.theforeman.org/issues/20315))
* Disable auth login when sessions are off ([#19602](http://projects.theforeman.org/issues/19602))
* Add all_parameters to host info ([#20286](http://projects.theforeman.org/issues/20286))
* Fix Hammer-cli display groups base dn ([#20227](http://projects.theforeman.org/issues/20227))
* Fix Hammer-cli current user password update ([#18005](http://projects.theforeman.org/issues/18005))
* Don't send snippet flag when --type is undefined ([#20145](http://projects.theforeman.org/issues/20145))
* Fix merging .edit.po into .po files ([#17671](http://projects.theforeman.org/issues/17671))
* Enable taxonomy titles ([#19157](http://projects.theforeman.org/issues/19157))
* Provide default exception handler ([#19470](http://projects.theforeman.org/issues/19470))
* Accept hostgroup title in host create ([#19048](http://projects.theforeman.org/issues/19048))
* Retry command on session expiry ([#19431](http://projects.theforeman.org/issues/19431))
* More detailed instructions on SSL verification fail ([#19390](http://projects.theforeman.org/issues/19390))
* Add additional attributes on user list command ([#4396](http://projects.theforeman.org/issues/4396))
* Add description to hostgroup ([#19361](http://projects.theforeman.org/issues/19361))
* Require apipie-bindings >= 0.2.0 ([#19362](http://projects.theforeman.org/issues/19362))
* Require rest-client >= 1.8.0 ([#19358](http://projects.theforeman.org/issues/19358))
* Rustom error for 401 unauthorized ([#19362](http://projects.theforeman.org/issues/19362))
* Correctly resolve empty arrays ([#18742](http://projects.theforeman.org/issues/18742))
* Use Array for empty attributes ([#19312](http://projects.theforeman.org/issues/19312))
* Compute-resources has images subcommand ([#19156](http://projects.theforeman.org/issues/19156))
* Prevent sending nil values in hostgroup update ([#14872](http://projects.theforeman.org/issues/14872))
* Install server CA cert without root access ([#19083](http://projects.theforeman.org/issues/19083))
* Add description to subnet ([#19172](http://projects.theforeman.org/issues/19172))
* Replaces --subnet-parameters-attributes with parameter commands ([#18663](http://projects.theforeman.org/issues/18663))
* Make session authenticator compatible with rest-client 1.8 ([#19159](http://projects.theforeman.org/issues/19159))
* Add vlan id field to subnet ([#19134](http://projects.theforeman.org/issues/19134))

### 0.10.0 (2017-03-28)
* Adding --hidden-value option to parameters (#290) ([#18878](http://projects.theforeman.org/issues/18878))
* Add command to clone user role ([#18318](http://projects.theforeman.org/issues/18318))
* Default organization/location work with authenticators ([#17936](http://projects.theforeman.org/issues/17936))
* Display hostgroup title on host actions ([#18739](http://projects.theforeman.org/issues/18739))
* Respect original request_params ([#18790](http://projects.theforeman.org/issues/18790))
* Rename config template to provisioning template ([#18654](http://projects.theforeman.org/issues/18654))
* User create/update accepts organization/location name ([#17923](http://projects.theforeman.org/issues/17923))
* Skip generating option --root-pass for host create ([#18337](http://projects.theforeman.org/issues/18337))
* Session authenticator keeps asking for user ([#18170](http://projects.theforeman.org/issues/18170))
* Host create uses name options ([#18339](http://projects.theforeman.org/issues/18339))
* Only include .mo files below locale/ ([#18439](http://projects.theforeman.org/issues/18439))
* Add config group commands ([#7520](http://projects.theforeman.org/issues/7520))
* Poweroff hosts when using --force option ([#18319](http://projects.theforeman.org/issues/18319))
* Resolve subnet and domain for host create/update (#273) ([#17247](http://projects.theforeman.org/issues/17247))
* Prevent from setting taxonomies for non-overriding filters ([#17730](http://projects.theforeman.org/issues/17730))

### 0.9.0 (2016-12-15)
* Auth overrides only unauthorized exception ([PR #271](https://github.com/theforeman/hammer-cli-foreman/pull/271)) ([#17650](http://projects.theforeman.org/issues/17650))
* Session auth in hammer ([PR #269](https://github.com/theforeman/hammer-cli-foreman/pull/269)) ([#8016](http://projects.theforeman.org/issues/8016))
* Display override value order as long text ([#17355](http://projects.theforeman.org/issues/17355))
* Showing roles inherited from usergroups ([#16016](http://projects.theforeman.org/issues/16016))
* The 'start' key always needs a 1 or 0 ([#17393](http://projects.theforeman.org/issues/17393))
* Compute resource specific details in host help ([PR #263](https://github.com/theforeman/hammer-cli-foreman/pull/263)) ([#12472](http://projects.theforeman.org/issues/12472))
* Fix compute-resource info ([#17077](http://projects.theforeman.org/issues/17077))
* List override in filter output ([#17109](http://projects.theforeman.org/issues/17109))
* Added description field to User in hammer ([#16772](http://projects.theforeman.org/issues/16772))
* Added description field to Roles in hammer ([#16771](http://projects.theforeman.org/issues/16771))
* add taxonomies to role info ([#16799](http://projects.theforeman.org/issues/16799))
* Adds 'builtin' attribute to Role list ([#16406](http://projects.theforeman.org/issues/16406))

### 0.8.0 (2016-09-01)
* add realm commands to hammer ([PR #240](https://github.com/theforeman/hammer-cli-foreman/pull/240)) ([#4918](http://projects.theforeman.org/issues/4918))
* Renamed name to variable for smart_variables ([#16119](http://projects.theforeman.org/issues/16119))
* displaying use_puppet_default in sc-param info ([#16059](http://projects.theforeman.org/issues/16059))
* show admin flag in user-group listing ([#12473](http://projects.theforeman.org/issues/12473))
* pin fast_gettext to < 1.1.0 for ruby < 2.1 ([PR #257](https://github.com/theforeman/hammer-cli-foreman/pull/257)) ([#16141](http://projects.theforeman.org/issues/16141))
* Remove parameters api call from host info command ([#15585](http://projects.theforeman.org/issues/15585))
* Add hostgroup create/update tests ([#15312](http://projects.theforeman.org/issues/15312))
* Add description to organization and location list ([PR #247](https://github.com/theforeman/hammer-cli-foreman/pull/247)) ([#15502](http://projects.theforeman.org/issues/15502))
* Add add/remove location command to organization ([PR #248](https://github.com/theforeman/hammer-cli-foreman/pull/248)) ([#15501](http://projects.theforeman.org/issues/15501))
* Update documented test data path ([PR #246](https://github.com/theforeman/hammer-cli-foreman/pull/246)) ([#15433](http://projects.theforeman.org/issues/15433))

### 0.7.0 (2016-06-14)
* Let print adapters decide whether to paginate ([#15257](http://projects.theforeman.org/issues/15257))
* Forbid setting smart param override value and puppet default ([#13832](http://projects.theforeman.org/issues/13832))
* Add rebuild config option for host ([PR#231](https://github.com/theforeman/hammer-cli-foreman/pull/231)) ([#12103](http://projects.theforeman.org/issues/12103))
* Removing wrong colons from host create docs
* i18n - remove underscore from override value error message
* Typo in MissingSeachOptions ([#14007](http://projects.theforeman.org/issues/14007))
* Add Catalan language ([#14947](http://projects.theforeman.org/issues/14947))
* Hammer shows incorrect admin status when assign admin role using user group ([#14606](http://projects.theforeman.org/issues/14606))
* Fixed response parsing for puppetclasses parameter ([#14930](http://projects.theforeman.org/issues/14930))
* Display locked flag for templates and ptables ([#14943](http://projects.theforeman.org/issues/14943))
* Document vmware `start` parameter
* Fixes VMware name in docs for host create
* Respect per_page set in config file ([#14530](http://projects.theforeman.org/issues/14530))
* Provide success/failure message for associating commands ([#7492](http://projects.theforeman.org/issues/7492))
* Add support for Gemfile.local.rb ([#14466](http://projects.theforeman.org/issues/14466))
* Fixing path in docs for generated test json ([PR#226](https://github.com/theforeman/hammer-cli-foreman/pull/226))
* Added clone command to config templates ([#13946](http://projects.theforeman.org/issues/13946))
* Handle API request redirects with useful message ([#11147](http://projects.theforeman.org/issues/11147))
* Newer version of apipie validates types for arrays ([#13966](http://projects.theforeman.org/issues/13966))
* Show auth source name for all auth sources ([#7468](http://projects.theforeman.org/issues/7468))
* Environment and Puppet proxy is not required ([#13926](http://projects.theforeman.org/issues/13926))
* Added special method for dealing with puppetclasses ([#11880](http://projects.theforeman.org/issues/11880))
* Make primary and provision flag optional ([#13927](http://projects.theforeman.org/issues/13927))

### 0.6.0 (2016-02-25)
* Names of sc-params are immutable ([#13830](http://projects.theforeman.org/issues/13830))
* Support for command testing moved to core ([#4118](http://projects.theforeman.org/issues/4118))
* Adding parent to taxonomies info command ([#13758](http://projects.theforeman.org/issues/13758))
* Showing hidden_value? for smart variables and class parameters ([#13750](http://projects.theforeman.org/issues/13750))
* Executing "hammer role filters" command throws SQL errors ([#13064](http://projects.theforeman.org/issues/13064))
* Remove psych require from Gemfile ([#12797](http://projects.theforeman.org/issues/12797))
* Hammer listing the sc-params shows puppetclass ([#12998](http://projects.theforeman.org/issues/12998))

### 0.5.1 (2015-12-14)
* Fixing dependency issues

### 0.5.0 (2015-12-14)
* Addng info command to role ([#7412](http://projects.theforeman.org/issues/7412))
* Add defaults support for location/organization ([#11402](http://projects.theforeman.org/issues/11402))
* Tests updated to work with Foreman 1.10 API ([#12260](http://projects.theforeman.org/issues/12260))
* Commands for setting parameters at taxonomies ([#12699](http://projects.theforeman.org/issues/12699))
* Change once to one in error message ([#12695](http://projects.theforeman.org/issues/12695))
* Host create VMware docs update ([#12087](http://projects.theforeman.org/issues/12087))
* Add option to overwrite conflicts on host changes ([#9208](http://projects.theforeman.org/issues/9208))
* String parameters get double-quoted ([#12202](http://projects.theforeman.org/issues/12202))
* Added IPAM desc on info command ([#11074](http://projects.theforeman.org/issues/11074))

### 0.4.0 (2015-09-21)
* Adding match_default to smart variables and smart class parameters ([#10731](http://projects.theforeman.org/issues/10731))
* Missing field for VMWare host creation docs ([#11088](http://projects.theforeman.org/issues/11088))
* Delete direct dependencies (refs [#11452](http://projects.theforeman.org/issues/11452))
* Messages in associating commands weren't translated ([#7236](http://projects.theforeman.org/issues/7236))
* Add root_pass option ([#11236](http://projects.theforeman.org/issues/11236))
* Drop Ruby 1.8 support (refs [#11280](http://projects.theforeman.org/issues/11280))


### 0.3.0 (2015-07-29)
* Add normalizer converting id parameter values to numbers ([#11137](http://projects.theforeman.org/issues/11137))
* Docs - updated information about host creation
* Added some rough docs showing HammerCLIForeman::Command
* Adding a command for building PXE default ([#3968](http://projects.theforeman.org/issues/3968))
* Turn off pagination by default ([#10534](http://projects.theforeman.org/issues/10534))
* Can't set array parameters on hosts ([#10547](http://projects.theforeman.org/issues/10547))


### 0.2.0 (2015-04-23)
* Adding default org and loc to user info ([#10251](http://projects.theforeman.org/issues/10251))
* Host update resets some attributes ([#10215](http://projects.theforeman.org/issues/10215))
* Improve handling of id search errors ([#9971](http://projects.theforeman.org/issues/9971))
* Commands for managing host's interfaces ([#3849](http://projects.theforeman.org/issues/3849))
* Support for smart variables and override values ([#2928](http://projects.theforeman.org/issues/2928))
* Can't convert nil into Array in compute resouce info ([#7699](http://projects.theforeman.org/issues/7699))
* Use correct domain for system locales, only load one domain ([#9648](http://projects.theforeman.org/issues/9648))
* Allow disablement of record_to_common_format ([#8227](http://projects.theforeman.org/issues/8227))
* Puppet-classes in host and hostgroup returns without an error ([#7473](http://projects.theforeman.org/issues/7473))
* Does not resolve a nested host group to id when updating a host ([#9318](http://projects.theforeman.org/issues/9318))
* User info doesn't display timezone and locale ([#9114](http://projects.theforeman.org/issues/9114))
* Update to gettext 3.x ([#8980](http://projects.theforeman.org/issues/8980))
* Commands for settings ([#2918](http://projects.theforeman.org/issues/2918))
* Adds dns name association to domain cli ([#3630](http://projects.theforeman.org/issues/3630))
* List of host facts is shown correctly ([#7187](http://projects.theforeman.org/issues/7187))
* Add config directory to gemspec ([#8829](http://projects.theforeman.org/issues/8829))
* List commands should not be interactive for csv output ([#3898](http://projects.theforeman.org/issues/3898))


### 0.1.4 (2014-12-11)
* sending puppet class ids ([#8651](http://projects.theforeman.org/issues/8651))
* setting --puppet-class-ids on host create/update throws api exception ([#8642](http://projects.theforeman.org/issues/8642))
* adding name equivalents to params in host/hostgroup create/update ([#8299](http://projects.theforeman.org/issues/8299))
* id resolution for associted resources ([#8246](http://projects.theforeman.org/issues/8246))
* added missing search option error message ([#5556](http://projects.theforeman.org/issues/5556))
* OSs referenced by title ([#8247](http://projects.theforeman.org/issues/8247))
* credentials definition moved to ApipieBindings ([#7408](http://projects.theforeman.org/issues/7408))
* listing filters for roles always fail with an exception ([#7913](http://projects.theforeman.org/issues/7913))
* api for operating systems now uses field 'title' ([#7917](http://projects.theforeman.org/issues/7917))
* i18n - add zh_CN language
* i18n - add de, it, pt_BR, zh_TW, ru, ja, ko languages
* external user groups CLI ([#6879](http://projects.theforeman.org/issues/6879))
* moved LDAP auth sources to separate command
* adds command to manage ldap auth sources ([#2924](http://projects.theforeman.org/issues/2924))
* avoid locale domain name conflict ([#7262](http://projects.theforeman.org/issues/7262))


### 0.1.3 (2014-08-20)
* Update foreman.yml
* Update the zanata.xml file to push to de-DE and es-ES ([#7112](http://projects.theforeman.org/issues/7112))
* Adding system locale domain ([#7083](http://projects.theforeman.org/issues/7083))
* Name options for puppet proxies in hostgroup ([#7085](http://projects.theforeman.org/issues/7085))
* I18n - extracting new, pulling from tx


### 0.1.2
* Docs for name->id resolution
* Update with installation details and IRC channel
* Lazy loaded subcommands ([#6761](http://projects.theforeman.org/issues/6761))
* I18n - fix some broken subcommand description extractions
* I18n - fix strings to be properly extracted without interpolation
* I18n - add en_GB locale
* I18n - extracting new, pulling from tx
* Initial update of translations, fixed Makefile
* Fixed pagination ([#6766](http://projects.theforeman.org/issues/6766))
* Restrict ci_reporter gem to less than 2.0.0 to fix CI ([#6779](http://projects.theforeman.org/issues/6779))
* Add proxy refresh-features command ([#3387](http://projects.theforeman.org/issues/3387))
* Fixed simplecov dependences
* Params from searchables are not wrapped ([#6343](http://projects.theforeman.org/issues/6343))
* rest-client > 1.7 does not support ruby 1.8 ([#6534](http://projects.theforeman.org/issues/6534))
* Tests updated to use apidoc export for v1.6 ([#2922](http://projects.theforeman.org/issues/2922))
* Commands for managing roles, filters, permissions and usergroups ([#2922](http://projects.theforeman.org/issues/2922), [#4004](http://projects.theforeman.org/issues/4004))
* Obey refresh_cache default of false ([#6478](http://projects.theforeman.org/issues/6478))
* Creating a more generic hook for search_options ([#6203](http://projects.theforeman.org/issues/6203))
* Permit only --hostgroup when creating host ([#6335](http://projects.theforeman.org/issues/6335))
* Better option descriptions ([#6093](http://projects.theforeman.org/issues/6093))
* Mapping resource names in options ([#6092](http://projects.theforeman.org/issues/6092))
* Add --server cli option ([#6219](http://projects.theforeman.org/issues/6219))
* Fix for wrong parameters in proxy import ([#6090](http://projects.theforeman.org/issues/6090))
* Resolving ids in foreman base command ([#6090](http://projects.theforeman.org/issues/6090))
* Documentation for fine grained control over name expansion ([#5747](http://projects.theforeman.org/issues/5747))
* Fine grained control over name expansion ([#5747](http://projects.theforeman.org/issues/5747))
* Scoped options were not cleaning original options ([#5873](http://projects.theforeman.org/issues/5873))
* List actions don't resolve ids for optional parameters ([#5873](http://projects.theforeman.org/issues/5873))
* Help for associating commands is too generic ([#3512](http://projects.theforeman.org/issues/3512))
* Add pkg:generate_source task to generate gem ([#5793](http://projects.theforeman.org/issues/5793))

### 0.1.1
* Support for os default templates ([#3970](http://projects.theforeman.org/issues/3970))
* Searching all resources by name ([#4311](http://projects.theforeman.org/issues/4311))
* Listing associated resources ([#3102](http://projects.theforeman.org/issues/3102))
* Fix setting infinite timeouts ([#5209](http://projects.theforeman.org/issues/5209))
* Support for API localization ([#4478](http://projects.theforeman.org/issues/4478))
* Removed `log_api_calls` setting

### 0.1.0
* Fix for Hammer failing silently when no cache is generated ([#4849](http://projects.theforeman.org/issues/4849))
* Request localized api responses ([#4476](http://projects.theforeman.org/issues/4476))
* Setting request timeout ([#3598](http://projects.theforeman.org/issues/3598))
* Added provision_method to host creation
* Unified format of hammer commands ([#4697](http://projects.theforeman.org/issues/4697))
* Fix for server formatter failing on not symbol keys ([#4674](http://projects.theforeman.org/issues/4674))
* Support for dynamic bindings ([#3897](http://projects.theforeman.org/issues/3897))
* Adds host option to pass root password ([#4587](http://projects.theforeman.org/issues/4587))
* Adds conditional output field to show network interfaces ([#4589](http://projects.theforeman.org/issues/4589))
* i18n support ([#4473](http://projects.theforeman.org/issues/4473))
* Default value for proxy import_puppetclasses --dryrun ([#4130](http://projects.theforeman.org/issues/4130))
* Fixes DNS proxy id field in subnet list ([#4558](http://projects.theforeman.org/issues/4558))
* Fixes assigning puppet classes to hostgroups ([#4585](http://projects.theforeman.org/issues/4585))
* Adds more fields for hostgroup list ([#4588](http://projects.theforeman.org/issues/4588))
* Fixes createion and update of templates ([#4352](http://projects.theforeman.org/issues/4352))
* Fixes failing proxy import_classes ([#4517](http://projects.theforeman.org/issues/4517))
* Fixes displaying errors related to operating system commands ([#4467](http://projects.theforeman.org/issues/4467), [#4466](http://projects.theforeman.org/issues/4466), [#3360](http://projects.theforeman.org/issues/3360))
* Credentials moved to Foreman
* Unmanaged host can be now created empty ([#4358](http://projects.theforeman.org/issues/4358))
* Fixes 500 error messages being ignored ([#4355](http://projects.theforeman.org/issues/4355))
