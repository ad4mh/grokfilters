# grokfilters

Some Grok filters for different firewall log formats.

copy the needed files/patetrns to /opt/logstash/patterns/ or any other folder used for patterns. Make sure you specify the right folder in your logstash.conf file ( patterns_dir => "<path to your patterns>")

These filters make use of the predefined Grok filters - make sure they are present in the same directory.

To test that filters work properly for you go to the following address for debugging: 
    http://grokdebug.herokuapp.com/


Corrections/optimizations/suggestions are welcomed.



