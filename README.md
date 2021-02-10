# NJC
assignment:

First Create DB and run the SQL script to create emp table and insert records.

drop TABLE emp;

create table emp(eid number,ename varchar2(24),esal number);

insert into emp(eid,ename,esal) values(101,'charan8',10000);
insert into emp(eid,ename,esal) values(102,'charan7',30000);
insert into emp(eid,ename,esal) values(103,'charan6',50000);
insert into emp(eid,ename,esal) values(108,'charan2',70000);
insert into emp(eid,ename,esal) values(109,'charan3',60000);
insert into emp(eid,ename,esal) values(110,'charan4',50000);


select * from emp

select * from emp where eid='102'
