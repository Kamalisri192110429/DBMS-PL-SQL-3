# DBMS-PL-SQL-3
CREATE DEFINER=`root`@`localhost` PROCEDURE `addition`()
BEGIN
declare a,b,c int(4);
set a=10,b=40;
set c=a+b;
select c;
END

OUTPUT
c=50
