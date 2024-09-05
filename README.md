**THE PROCESS OF CREATHING AN RDS AWS DATABASE_INSTANCE ON CLI**



#The creation of VPC
##The creation of two SUBNETS
  * yuor two subnets has to be connected on the vpc using the vpc id
  * The creation of two subnet_groups
         * yuor two subnet_groups must make use of yuor main subnet id
###* Creation of two security groups, 
       * one for mysql port and secondry HTTPS port
       * yuor VPC id must be attached to yuor security_group
####* Creation internet gatway 
      * attach it with yuor gatway id with yuor vpc id
  #####* Creation of a routtable 
        * attach with yuor vpc id 
######* Routable associations
 * yuor routable id and yuor subnet id
* db-instance-class db.t3.micro   
* engine mysql
* allocated-storage 20 
* master-username admin
* master-user-password 
* publicly-accessible

