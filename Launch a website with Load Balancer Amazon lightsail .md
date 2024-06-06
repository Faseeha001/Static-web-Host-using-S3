## Hands-On : Using Amazon LightSail Launch a website with Load Balancer

Setting up two web servers, connecting them to a load balancer on Amazon Lightsail, and pointing them to a domain involves several steps. Here's a detailed guide to help you through the process:

1. Set Up Two Web Servers on Amazon Lightsail
Step 1: Create Two Lightsail Instances

1.Log in to your AWS Management Console.
sss
2.Navigate to Lightsail.

3.Create an instance:

* Choose the region where you want your instance to be located.


*Select a blueprint (OS or application). For a web server, you can choose Linux/Unix and then select the appropriate app or stack (Here Wordpress is used ).

*Choose an instance plan based on your needs.

*Name your instance (e.g., webserver-1).

*Create the instance.