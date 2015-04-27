testing with cmdb_test.pl
-the existing test in cmdb_tests.csv depend on a 'readonly' user being setup in a 'readonly' group.  otherwise acl tests will fail
-these tests also depend on the lexicon having a 'ipmi_ip' field and the config item 'traffic_control_search_fields' containing
  the 'ipaddress' field

new dependencies:
-log4perl
-perl-DateManip
