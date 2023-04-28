# create a checkin’s table by normalizing date column

CREATE TABLE data230.res_checkin_byid_norm AS
SELECT SPLIT(Date,',') as Date, business_id
FROM ( SELECT * FROM data230.checkin_data);
