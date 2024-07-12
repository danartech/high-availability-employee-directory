# High Availability Employee Directory

## Description
This project demonstrates how to configure high availability for an Employee Directory application using AWS services. The setup includes an Application Load Balancer, a Launch Template, and an Auto Scaling group to ensure the application can handle varying levels of traffic and maintain availability.

## Key Steps
1. **Create an Application Load Balancer:**
   - Configured load balancer settings, security groups, and target groups.
   - Verified the setup by accessing the Employee Directory application via the load balancer.

   ![Create Application Load Balancer](https://github.com/your-username/high-availability-employee-directory/blob/main/images/file-xIKDhS9EVOg0SniqW40RnpNs.png)

2. **Create a Launch Template:**
   - Set up a launch template with the necessary configurations for EC2 instances.
   - Included user data script for instance initialization.

   ![Create Launch Template](https://github.com/your-username/high-availability-employee-directory/blob/main/images/file-POFfRe7gKpY5c65xn3EQZHEA.png)

3. **Set Up an Auto Scaling Group:**
   - Created an Auto Scaling group using the launch template.
   - Configured scaling policies and notifications.

   ![Set Up Auto Scaling Group](https://github.com/your-username/high-availability-employee-directory/blob/main/images/file-VkdP1XGR2VE7AlJ6IqcSxz4Y.png)

4. **Test the Application:**
   - Conducted a stress test to trigger scaling events.
   - Verified the high availability and horizontal scaling of the application.

   ![Test Application](https://github.com/your-username/high-availability-employee-directory/blob/main/images/file-b0BylMFdfVU26RIxKouGBuwC.png)
