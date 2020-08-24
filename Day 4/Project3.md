Step1:Create two linux instances,Use the first free linux AMI
Step2:Launch both instances using Mobaxterm
Step4:Host html login webpage on both servers
Step5:Check if the application is deployed on both servers by copy pasting the public ip of the servers into
the browser.
Step6:Create a application Load balancer with the above two instances as targets
Step7:Check the functioning of ELB

Attached the screenshots

The IPs of linux AMIs: 
http://13.233.255.254/
http://13.127.231.123/

And the DNS of ELB:
http://samlb-2094984946.ap-south-1.elb.amazonaws.com/
