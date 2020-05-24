# DevOps3
Lesson 3 in Udacity's DevOps program

I used two sets of files instead of one because this is in accordance to best practices. The project goals seems to assume one set of files, but do not explicitly rule out using 2 sets of files. With 2 sets of files it is necessary to first create the network stack before creating the other stack. 

In the rubric,

"SSH Key: There shouldn’t be a ‘keyname’ property in the launch config"
and
"Bastion Host: Any resource of type AWS::EC2::Instance, optional, but nice to have."

seem to contradict each other, but since one is optional, I won't dwell on this.

I checked the docs for health check grace period syntax, but the second doc below reported, "Looking for something?"
https://aws.amazon.com/about-aws/whats-new/2017/12/amazon-ecs-adds-elb-health-check-grace-period/

https://docs.aws.amazon.com/sdkfornet1/latest/apidocs.html/P_Amazon_AutoScaling_Model_AutoScalingGroup_HealthCheckGracePeriod.htm

