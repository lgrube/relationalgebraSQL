# relationalgebraSQL
this is the relational algebra we were trying to do monday in SQL form


Query 1:
          select distinct fname, lname from employee where ssn=super_ssn and ssn=ssn;

Query 2:
          select lname from employee as e, project as p where p.dum=e.dno;
          
Query 3:
          select fname, lname from employee as e, dependent as d where e.sex=d.sex and e.fname=d.dependent_name;
