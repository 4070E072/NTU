CREATE TABLE emp (
  empno INT NOT NULL,
  ename VARCHAR(16) NOT NULL,
  job VARCHAR(16),
  manager INT,
  hiredate DATE,
  salary float(7, 2),
  comm float(7,2),
  deptno INT,
  PRIMARY KEY (empno)
