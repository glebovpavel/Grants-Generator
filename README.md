Grants-Generator
=================================

##About

Generating grants for all DB-Objects used in APEX-application. 

##Before Using


grant execute on #APEX_SCHEMA#.wwv_flow_theme_manager to #APPLICATION_SCHEMA#;
create synonym #APPLICATION_SCHEMA#.WWV_FLOW_THEME_MANAGER for #APEX_SCHEMA#.wwv_flow_theme_manager;

Please replace #APPLICATION_SCHEMA# to DB schema where Grants-Generator will be installed.
           and #APEX_SCHEMA# to current apex schema, for example apex_050000.

##Requirements

APEX 5.0

##Current Stable Version

Version 1.00

##License

See LICENSE.md (MIT)
