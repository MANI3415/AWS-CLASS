# AWS-CLASS(Afternoon batch)
- Training Start Date:  24th Jan 2022, *Time:*2pm to 3pm
- Zoom Link: https://zoom.us/j/97718944532?pwd=cmhuOGVrbVVrMkc3b0QwQ3BJYmJWUT09 
- Zoom Credentials:  Zoom id: 977 1894 4532 
- Passcode:aws

--------------------------------------------------------------------------------
**DAY-1 (24-01-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=1whG3utFlLI&t=17s
- TOPICS COVERED ON (24-01-2022)
  - AWS INTRODUCTION
  - DEMO OF EC2 INSTANCE LAUNCH
  
  -------------------------------------------------------------------------------
**DAY-2 (28-01-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=3Esb-FUQnXc
- TOPICS COVERED ON (25-01-2022)
  - AMAZON DATA CENTERS
  - CLOUD COMPUTING MODELS
    - INFRASTRUCTURE AS A SERVICES(IAAS)--ALL MAINTANCES ARE PROVIDED(SYSTEM MAINTANCE ARE SERVER MAINTANCE)
    - PLATFORM AS A SERVICES(PAAS)--ALL LICENSES SERVER ARE PROVIDED IT IS EASY ACCESSABILITY
    - SOFTWARE AS A SERVICES(SAAS)--FREE DEFINED TEMPLATES ARE PROVIDED
  - EC2 SERVER LAUNCH (ELASTIC CLOUD COMPUTING) 
  
----------------------------------------------------------------------------------
**DAY-3 (29-01-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=9zb1QMaodhE&t=397s
- TOPICS COVERED ON (29-01-2022)
  - IAM(IDENTITY ACCESS MANAGEMENT)
  - MFA(MULTI FACTOR AUTHANTICATION)
    - DASHBOARD
    - USER--CREATE USER
    - ROLES--CREATE RULES(HOW MANY SERVICES ARE YOU NEED)
    - POLICES--CREATE POLICES(SERVER ACCESSABILITY TIME EXAMPLE:SOMETIMES SERVER ACCESSABILITY INCREASED AND SOMETIME LOW)
    - IDENTITY PRIVIDER
  - S3 BUCKET(SIMPLE STORAGE SERVICE) 

----------------------------------------------------------------------------------
**DAY-4 (01-02-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=ca_xgAJJzCg
- TOPICS COVERED ON (01-02-2022)
- NATGATE WAY

Load Balancing–
Auto Scaling–High Availability

- Elastic Load Balancer(ELB)
  - microservices
    - /user
    - /app
    - /user-name
  - target group
    - customized apps
    - (nginx)(apache)
  - round robin mechanism
    - Request–Response

  - EFS(Elastic File System)
            
### Network Load Balancer is a Faster Then Application Load Balancer

**NETWORK LOAD BALANCER:
- NLB IS WORKS ON TCP/UDP PROTOCOL
- OSI LAYER
- PORT BASED ROUTING

**APPLICATION LOAD BALANCER:
- ALB——HTTP/HTTPS
- APPLICATION LAYER
- PATH BASED ROUTING

----------------------------------------------------------------------------------------------
**DAY-5 (02-02-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=eA0N_elaO7I
- TOPICS DISCUSSED ON 02/02/2022

- first we launch the EC2 Instances

- load balancing
    - Load Balancers             
    - Target Groups

- STEP-1:-
                                - FIRST WE CREATING TARGET GROUPS:-

   - CREATE TARGET GROUPS FOLLOW THE APPICATION LOAD BALANCER PROTOCOL(HTTP/HTTPS)
   - SELECT TARGET GROUPS-CREATE TARGET GROUPS--GIVE THE TARGET NAME AND SELECT APPLICATION LOAD BALANCER PROTOCOL--AND SELECT TO REGISTER TARGETS INSTANCES--INCLUDE AS PENDING      BELOW--CREATE TARGET GROUP
 
   - CREATE TARGET GROUPS FOLLOW THE NETWORK LOAD BALANCER PROTOCOL(TCP/UDP/TLS)
   - SELECT TARGET GROUPS-CREATE TARGET GROUPS--GIVE THE TARGET NAME AND SELECT NETWORK LOAD BALANCER PROTOCOL--AND SELECT TO REGISTER TARGETS INSTANCES--INCLUDE AS PENDING          BELOW--CREATE TARGET GROUP

- STEP-2:-
                                        - LOAD BALANCERS:-
  - ALB CREATION:-
    - SELECT CREATE LOAD BALANCER--SELECT APPLICATION LOAD BALANCER--GIVE THE LOAD BALANCER NAME AND SELECT THE ALP TARGET GROUP--CREATE LOAD BALANCER
  - NLB CREATION:-
    - SELECT CREATE LOAD BALANCER--SELECT NETWORK LOAD BALANCER--GIVE THE LOAD BALANCER NAME AND SELECT THE NLB TARGET GROUP--CREATE LOAD BALANCER

- Auto Scaling
    - Launch Configurations
    - Auto Scaling Groups

- STEP-3:-
                                     - Launch Configurations:-
  
  -- Select the Launch Configurations create Launch Configurations--first we create the launch templates--and give the template name and select AMI(amazon machine image)--and        select any one of security group--create launch template
   - now create Launch Configurations--give name,select any one of AMI and select instance(t2-micro),and select key pair is requried or not--create Launch Configurations

- STEP-4:-
                                      - Auto Scaling Groups:-

  -- Select Auto Scaling Groups--Create Auto Scaling Groups--

  - Step 1:
    - Choose launch template or configuration:-
      -- and give name And Select Switch to Launch configuration And Select A Launch configuration --Next
  - Step 2:
    - Choose instance launch options:-
      -- Select Availabiliy Zones--Next
  - Step 3 (optional)
    - Configure advanced options:-
      -- Select Attach to an existing load balancer--Select Existing load balancer target groups--Select Health check type(ELB)--Next
  - Step 4 (optional)
    - Configure group size and scaling policies:-
      -- Next
  - Step 5 (optional)
    - Add notifications:-
      -- Next
  - Step 6 (optional)
    - Add tags:-
      -- Next
  - Step 7
    - Review:-
      -- Create Auto Scaling Groups
   
   -----------------------------------------------------------------------------------------------------
- **DAY-06 (03-02-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=FjZyVZJvEg0
- TOPICS DISCUSSED ON 03/02/2022
- Config Group Size & Scaling Polices

- Config Group Size
  - Group Size Optimal
  - Check The Activity--Check The Instances

- Scaling polices
  - none
  - key and value optional
 
- create a dynamic scaling policy
- create a cloud watch
  - select matric--alarm
  
   - static                              
   - greater>=threshold             
   - value-70                                      

   - select ec2 
   - auto scaling group

   -  matric name
   -   cpu  utilization
   -   Auto scaling group

- simple notification service()

------------------------------------------------------------------------------------------------------
 **DAY-07 (04-02-2022)
- VIDEO LINK:https://www.youtube.com/watch?v=FjZyVZJvEg0&t=20s
- TOPICS DISCUSSED ON 04/02/2022
- cloudwatch

-----------------------------------------------------------------------------

**DAY-08 (05-02-2022)
- VIDEO LINK:https:https://www.youtube.com/watch?v=GnhaFyLmJMQ
- TOPICS DISCUSSED ON 05/02/2022
- ec2 server launch using redhat
- ec2 server launch using ubantu

--------------------------------------------------------------------------
  **DAY-09 (07-02-2022)
- VIDEO LINK:https://youtu.be/GxSXp6Qw7XE
- TOPICS DISCUSSED ON 07/02/2022
- Terraform-Hashicorp
  - steps in Terrafoem
    - configuration file
    - init--plan--apply
- IAC tools
- Docker Ansible,puppet,saltstack,cloudformation

-------------------------------------------------------------------------
**DAY-10 (08-02-2022)

VIDEO LINK:
TOPICS DISCUSSED ON 08/02/2022

 
