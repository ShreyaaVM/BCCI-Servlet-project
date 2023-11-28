# BCCI-Servlet-project
github-jenkins-tomcat-RDS-Mysql

templates and works

GitHub Repository link ==>>>   https://github.com/sakit333/BCCI-Servlet-project.git
Admin Login==>>> user name - binny@gmail.com
                 password - binny123



<property name="javax.persistence.jdbc.url"    
          value="jdbc:mysql://project-db.cg92sss7amcv.ap-south-1.rds.amazonaws.com:3306/project-db?createDatabaseIfNotExist=true" />
        <property name="javax.persistence.jdbc.user"
          value="admin" />
        <property name="javax.persistence.jdbc.password"
          value="Adminroot" />
          
          
          
          <welcome-file-list>
		<welcome-file>
			Welcome.html
		</welcome-file>
	</welcome-file-list>


 commands to execute in database server
 sudo su -
 yum install mysql -y
 mysql -h <hostname-endpoint> -P 3306 -u admin -p
 show database;
 use bravo;
 select * from TeamDto;
