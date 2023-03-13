select dept,count(e.id) "NUMBER OF COMPUTERS" from Computer C inner join Employee e on c.compid=e.compid and make= 'Dell' group by e.dept;
