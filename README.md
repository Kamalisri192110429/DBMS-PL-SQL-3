# DBMS-PL-SQL-3
CREATE DEFINER=`root`@`localhost` PROCEDURE `addition`()
BEGIN
declare a,b,c int(4);
set a=20,b=30;
set c=a+b;
select c;
END

OUTPUT
c=50
