Description of Bennu library import - customised library by author, this version is not available upstream

modifications:
1/ removed ereg functions deprecated as of php 5.3 (18 Nov 2009)
2/ replaced mbstring functions with moodle core_text (28 Nov 2011)
3/ replaced explode in iCalendar_component::unserialize() with preg_split to support various line breaks (20 Nov 2012)
4/ updated rfc2445_is_valid_value() to accept single part rrule as a valid value (16 Jun 2014)
5/ updated DTEND;TZID and DTSTAR;TZID values to support quotations (7 Nov 2014)
6/ added calendar_normalize_tz function to convert region timezone to php supported timezone (7 Nov 2014)
